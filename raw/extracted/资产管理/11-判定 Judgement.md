---
source_file: "仿真平台资源汇总.xlsx"
sheet: "判定 Judgement"
header_row: 2
data_rows: 15
columns: 10
note: "扩展这个判定在哪里"
extracted: 2026-06-21
---

# 判定 Judgement

## 说明

> 扩展这个判定在哪里

## 字段字典

| # | 列 | 字段名 | 分组 |
|---|---|---|---|
| 1 | A | 细分-中英文 |  |
| 2 | B | 资源-中文 |  |
| 3 | C | 资源-英文 |  |
| 4 | D | 备注 |  |
| 5 | E | 缩略图 |  |
| 6 | F | Tag |  |
| 7 | G | 企业版&科研版 |  |
| 8 | H | 教学版 |  |
| 9 | I | 项目版本⭐ |  |
| 10 | J | 实现版本 |  |

## 数据（15 行）

| 细分-中英文 | 资源-中文 | 资源-英文 | 备注 | 缩略图 | Tag | 企业版&科研版 | 教学版 | 项目版本⭐ | 实现版本 |
|---|---|---|---|---|---|---|---|---|---|
| 原子判定 Atomic Judgement | 停车 | Parking |  |  |  | 是 | 是 |  | 2.0.0 |
| 原子判定 Atomic Judgement | 停车启动 | Stop and Go |  |  |  | 是 | 是 |  | 2.0.0 |
| 原子判定 Atomic Judgement | 压线 | Straddling The Line |  |  |  | 是 | 是 |  | 2.0.0 |
| 原子判定 Atomic Judgement | 变道 | Lane Change |  |  |  | 是 | 是 |  | 2.0.0 |
| 原子判定 Atomic Judgement | 扩展 | Extension |  |  |  | 是 | 是 |  |  |
| 原子判定 Atomic Judgement | 灯光 | Light Control |  |  |  | 是 | 是 |  | 2.0.0 |
| 原子判定 Atomic Judgement | 碰撞 | Collision |  |  |  | 是 | 是 |  | 2.0.0 |
| 原子判定 Atomic Judgement | 自定义 | Customized |  |  |  | 是 | 是 |  | 2.0.0 |
| 原子判定 Atomic Judgement | 超时 | Timeout |  |  |  | 是 | 是 |  | 2.0.0 |
| 原子判定 Atomic Judgement | 靠边停车 | Pull Over |  |  |  | 是 | 是 |  | 2.0.0 |
| 原子判定 Atomic Judgement | 驶出道路 | Offtrack |  |  |  | 是 | 是 |  | 2.0.0 |
| 原子判定 Atomic Judgement | 停车入库 | Park | 之前的实现与国创赛题里的路绑定死了不能改 |  |  | 否 | 否 |  | 2.0.0 |
| 原子判定 Atomic Judgement | 指令响应 | Commanded Response | 技术反馈之前实现有问题，代码没合，不具备相关功能 |  |  | 否 | 否 |  | 2.0.0 |
| 原子判定 Atomic Judgement | 事件区域 | Event Area |  |  |  | 否 | 否 | 清华 3.1 |  |
| lua脚本 lua Judgement | 停车入库 | Park | 为实现OD灵活可配，技术用lua重写了停车入库 |  |  | 否 | 否 | 国创大赛 |  |
