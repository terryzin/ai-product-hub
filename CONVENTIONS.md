# CONVENTIONS — 怎么写这个库

## 1. 一个功能 = 一个 `.md`(单一事实源)

YAML 头装机器可读的一切,正文写人读的 Spec。最小骨架:

```yaml
---
id: F-0001                 # 稳定 ID,永不复用
title: 功能名
level: feature             # capability | feature | subitem(判定尺:一人一周期能否独立发布)
tags: {area: 区域, module: 模块, capabilities: [业务能力…], domain: generic}
status: 已发布             # 见 vocabulary/enums.yaml
revision: {version: "3.4.0", state: approved, implements_iface: "1.0"}
interface: {version: "1.0", contract: "对外承诺一句话"}
presence: all              # 适用性,见 §3
override: []               # 行为差异,见 §4
parameter: null            # 结构化参数,见 §4
dependencies: []           # 依赖边,见 §5
scope: 核心                # 核心 | 可晋升 | 客户独占,见 §6
---

## 契约
（人读的 Spec）

## 验收
- … <!-- machine_checkable -->
```

## 2. 四条铁律(系统/评审要强制)

1. **revision 不可变** —— 任何改动 = 一个新 revision,**永不原地改**。旧版本靠 pin 冻结,不是靠人维护。
2. **改共享 feature 的优先级**:能加法别破坏 → 能参数化别开版本 → 能新增 B′ 别动 B → 真要双版本才付"扛两份直到迁移"的代价。
3. **破坏性改动 = interface major bump**,旧 interface 版本保留,供老消费者继续 pin。
4. **被 ≥1 个依赖 pin 的 revision 不得退役**,直到消费者迁移。

## 3. 适用性 presence(默认 default-on)

不写 = 全 6 个变体单元适用。只标例外:
```yaml
presence:
  exclude: [collab_cloud]        # 这些单元不适用
# 或
presence:
  only: [collab_cloud, teach_collab]   # 仅这些单元适用
```
变体单元(= 形态×商业版 出货组合)见 `vocabulary/dimensions.yaml > variant_cells`。

## 4. 行为差异:override vs parameter

- **结构化参数**(优先,可机检、可渲染):
```yaml
parameter:
  name: max_ego_count
  type: "int | inf"
  by_cell: {standalone: inf, teach_standalone: 50}   # 缺省继承基线;未知填 TODO
```
- **散文 delta + 继承指针**(非参数化的差异):
```yaml
override:
  - {cell: collab_client, delta: "不限制登录，仅限制创建任务"}
  - {cell: teach_collab, inherit_from: collab_client}   # 继承,不复制
```

## 5. 依赖 `dependencies`(DAG,A 依赖 B 的接口)

```yaml
dependencies:
  - {to: F-0102, kind: composes, pin: "exact:rev@3.6"}        # 锁死某 revision
  - {to: F-0203, kind: requires, pin: "compatible:>=1.2,<2.0"} # 接口不破即可升
  - {to: F-0050, kind: extends,  pin: "interface_only"}        # 只认接口
```
`kind`:composes(内部积木)/ requires(要它在场)/ extends(在它之上补充)。
改一个被共享的 B 前,跑**影响分析**:沿依赖边反向找消费者,看谁 pin 的契约被破。

## 6. 作用域 `scope` 与产品线 profile

- `核心` —— 进 baseline,所有线默认收。
- `可晋升` —— 通用但还没进 baseline;改成核心即"晋升"(在 `baseline.yaml` 收入,**无需 merge**)。
- `客户独占` —— 仅某客户;约束**禁止进 baseline**,只在该客户 profile 里 include。

产品线 = `product-lines/*.yaml` 的 profile:`follow_core`(默认收核心)+ `include_exclusive` + `overrides`(继承指针)+ `excludes`。
**禁止用 git branch 表达客户线。**

## 7. 改动流程

走 PR;merge = 审批落地。agent 可起草 PR(抽需求/漂移检测/影响分析),人做决策。risk_tier 低/中/高,高风险(Spec 定稿/合分支/发布)必须人审。
