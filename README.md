# SimOne · AI Product Hub

产品管理的单一事实源(SSOT)。一个机器可读、人与 AI 共用的 feature 库 —— 需求 → Feature → 规划 → 执行 → 发布 → 手册,全部沉淀为结构化文本。

> **核心理念:** 功能只定义一次,差异用标签和增量表达,视图靠筛选生成,分支靠 profile 而非 fork,血缘靠不可变版本追溯。复杂性下沉,日常只有三个动作:打开卡片 / 贴标签 / 按标签筛。

---

## 为什么是 Markdown + Git

这套底座本身就是"AI-native"的兑现,而且 Git 顺手提供了设计需要的几个原语:

| 设计需要 | Git 提供 |
|---|---|
| Spec 是人与 AI 共用的契约 | `.md` = 头(机器读)+ 正文(人读),一份文件两用 |
| FEATURE_REVISION 不可变留痕 | 提交历史 |
| 提议 → 人审批 门禁 | Pull Request / Merge |
| agent 可访问的机器可读底座 | 纯文本 + YAML 头,可被 MCP/脚本直接消费 |

**一条铁律先行:** 客户线(长城/江淮/…)用 `product-lines/` 下的 **profile 文件**表达,**绝不用 git branch 按客户分** —— 否则双向 merge 地狱会原样请回来。

---

## 目录

- **`vocabulary/`** —— 受控词表,所有视图/筛选/AI 上下文的引擎。维度取值必须来自这里。
  - `dimensions.yaml` 变体维度(形态/OS/配置/商业版/领域)+ 出货组合
  - `taxonomy.yaml` 区域→模块 两级树 + 业务能力标签(真实 harvest)
  - `enums.yaml` status / scope / pin / lifecycle 等受控取值
- **`features/`** —— 功能 = 单一事实源,一功能一文件(按区域分目录)。头装机器可读的一切(层级/标签/presence/override/参数/依赖/接口/scope),正文写人读的 Spec。
- **`product-lines/`** —— 产品线 = profile(勾选 + override + 排除)。`baseline.yaml` 主基线;每个客户一个文件。
- **`proposals/`** —— 提议 → 审批门禁(推荐直接用 GitHub PR/Issue)。

---

## 模型(四层 + 两层增量)

1. **骨架层** —— 功能、层级(能力/功能/子项)、版本化 Spec、验收标准。
2. **变体层** —— 适用性(presence)与行为差异(override/参数)分离;支持继承。
3. **基线/分支层** —— 产品线 = profile;`scope` 决定能否进 baseline;血缘靠不可变版本。
4. **治理层** —— 后果性改动皆为提议,经审批落地;risk_tier 是渐进放权旋钮。
5. **依赖层(增量)** —— `FEATURE_DEPENDENCY` 边(DAG):A 依赖 B 的**接口契约**而非实现;依赖 pin 一个 revision。
6. **作用域(增量)** —— `核心 / 可晋升 / 客户独占`:把"双向 merge"塌缩成"一次性归属决定"。

详见 `CONVENTIONS.md`。

---

## 快速上手

- 加一个功能:复制 `features/` 里任一 `.md`,改头里的字段,写正文契约。字段含义见 `CONVENTIONS.md`。
- 拉一条产品线的清单:读对应 `product-lines/*.yaml`(follow_core + 独占 + 排除)。
- 改动:走 PR;merge 即审批落地。
