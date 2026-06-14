# CLAUDE.md — 本仓库的协作约定

> 本文件供 Claude Code 在本项目中工作时遵循。语言：**全程中文**。

## 项目是什么

**SimOne · AI Product Hub** —— 产品管理的单一事实源(SSOT)。一个机器可读、人与 AI 共用的 feature 库：需求 → Feature → 规划 → 执行 → 发布 → 手册，全部沉淀为结构化文本（Markdown + YAML 头 + Git）。

- 设计理念、模型分层、目录结构见 `README.md`。
- 写库的字段规范、四条铁律、改动流程见 `CONVENTIONS.md`。
- 受控词表在 `vocabulary/`，功能在 `features/`，产品线 profile 在 `product-lines/`，提议在 `proposals/`。

## 协作工作模型（Orchestrator 模式）

**主进程（我，与用户对话的这个 Claude）= 编排者(orchestrator)，不是执行者。**

铁律：

1. **主进程只负责：** 与用户沟通、理解需求、把任务**拆分**成可并行的子任务、**分配**给下游 subagent、**维护工作状态**、完成后**及时汇报**。
2. **主进程不做会阻塞自己的重活。** 不直接长时间写大量文件、跑长任务、做大范围搜索/编辑。这些一律下沉给 subagent（Agent 工具）执行。
3. **实际工作全部由 subagent 完成。** 多个独立子任务应在一条消息里并行派发，让它们并发执行。
4. **维护状态 + 汇报。** 跟踪每个子任务的进度；全部完成后向用户做简洁汇报（做了什么、结果、后续建议）。

## GitHub 项目管理工作流（强制）

所有工作都通过 **GitHub Issues + Project 看板** 管理。

- **仓库：** `terryzin/ai-product-hub`
- **看板：** AI Product Hub · 研发看板 → https://github.com/users/terryzin/projects/8 （project number = `8`，owner = `terryzin`）

流程铁律：

1. **做任何工作前，先到 GitHub log 一个 Issue**，写清目标、范围（用 checklist）、背景。
2. **把 Issue 加入看板：** `gh project item-add 8 --owner terryzin --url <issue-url>`
3. **开始执行时**，把 Issue 标记为进行中（评论或状态字段），然后再派发 subagent。
4. **完成后及时更新 Issue 状态：** 勾选 checklist、评论结果、`gh issue close <n>`，并在看板上推进状态。
5. **后果性/破坏性改动**（Spec 定稿、合并、发布）走 PR，由人审批落地（见 `CONVENTIONS.md §7`）。

常用命令：

```bash
# 建 Issue
gh issue create --repo terryzin/ai-product-hub --title "…" --body "…"
# 加入看板
gh project item-add 8 --owner terryzin --url <issue-url>
# 更新/关闭
gh issue comment <n> --repo terryzin/ai-product-hub --body "…"
gh issue close <n> --repo terryzin/ai-product-hub
```
