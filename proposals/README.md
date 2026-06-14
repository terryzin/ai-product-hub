# proposals/ —— 提议 → 审批门禁

所有"后果性改动"(改 Spec / 改 presence / 合分支 / 晋升 / 发布)都先成为一个**提议**，经人(或将来低风险自动)审批后才落地。

## 推荐做法：直接用 GitHub PR/Issue 当门禁
- **PR = 提议**：任何对 `features/` `product-lines/` `vocabulary/` 的改动走 PR。
- **Merge = 审批落地**：人 review → 合并即生效。提交历史 = 不可变留痕(≈ FEATURE_REVISION)。
- **risk_tier 标签**：低/中/高。低风险(如状态同步)将来可配置自动合；高风险(Spec 定稿/合分支/发布)必须人审。
- **AI agent 起草**：agent 产出 PR(抽需求/漂移检测/手册 diff/影响分析)，人只做决策。

## 铁律
1. revision 不可变 —— 改动 = 新 revision，永不原地改。
2. 改共享 feature：能加法别破坏，能参数化别开版本，能新增 B′ 别动 B。
3. 破坏性改动 = interface major bump，旧 interface 保留供老消费者 pin。
4. 被 pin 的 revision 不得退役，直到消费者迁移。
