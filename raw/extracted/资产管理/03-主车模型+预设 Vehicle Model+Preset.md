---
source_file: "仿真平台资源汇总.xlsx"
sheet: "🚘 主车模型+预设 Vehicle Model+Preset"
header_row: 3
data_rows: 161
columns: 28
note: "【注释📌】 整行高亮为绿色：表示该资产为基线「主车模型」或「主车预设」。出现两条一样的，主要为【主车模型】和【主车预设】两条分别记录，更新规则——主车预设默认带有主车模型\n【公告📣】 51Sim产品线定义    |  【企业版】和【科研版】资源一致，教学版有阉割。【企业版】【教学版】「主车模型」和「主车预设」无差别\n【注意⚠】 新增【主车后轴中心到box中心几何中心】字段，外挂插件对应字段需要补充。"
groups:
  "版本管理": [G, H, I, J, K]
  "基础信息": [B, C, D, E]
extracted: 2026-06-21
---

# 🚘 主车模型+预设 Vehicle Model+Preset

## 说明

> 【注释📌】 整行高亮为绿色：表示该资产为基线「主车模型」或「主车预设」。出现两条一样的，主要为【主车模型】和【主车预设】两条分别记录，更新规则——主车预设默认带有主车模型<br>【公告📣】 51Sim产品线定义    \|  【企业版】和【科研版】资源一致，教学版有阉割。【企业版】【教学版】「主车模型」和「主车预设」无差别<br>【注意⚠】 新增【主车后轴中心到box中心几何中心】字段，外挂插件对应字段需要补充。

## 字段字典

| # | 列 | 字段名 | 分组 |
|---|---|---|---|
| 1 | A | 细分-中英文⭐ |  |
| 2 | B | 资源-中文 | 基础信息 |
| 3 | C | 资源-英文 | 基础信息 |
| 4 | D | 缩略图 | 基础信息 |
| 5 | E | 俯视图 | 基础信息 |
| 6 | F | 备注 |  |
| 7 | G | 企业版⭐科研版 | 版本管理 |
| 8 | H | 教学版 | 版本管理 |
| 9 | I | 项目版本⭐ | 版本管理 |
| 10 | J | 实现版本 | 版本管理 |
| 11 | K | 更新版本 | 版本管理 |
| 12 | L | Tag |  |
| 13 | M | Size |  |
| 14 | N | UE类别（一级） |  |
| 15 | O | UE类别（二级） |  |
| 16 | P | 公有云 |  |
| 17 | Q | 社区版 |  |
| 18 | R | 企业版-单机版 |  |
| 19 | S | 企业版-云端版 |  |
| 20 | T | 教育版（含教学版） |  |
| 21 | U | 同济 |  |
| 22 | V | 尺寸（cm） |  |
| 23 | W | UE_名称 |  |
| 24 | X | 所属关卡 |  |
| 25 | Y | UE路径 |  |
| 26 | Z | 制作碰撞包围盒 |  |
| 27 | AA | 车灯与大灯 |  |
| 28 | AB | 主车后轴中心到box中心几何中心 |  |

## 数据（161 行）

| 细分-中英文⭐ | 资源-中文 | 资源-英文 | 缩略图 | 俯视图 | 备注 | 企业版⭐科研版 | 教学版 | 项目版本⭐ | 实现版本 | 更新版本 | Tag | Size | UE类别（一级） | UE类别（二级） | 公有云 | 社区版 | 企业版-单机版 | 企业版-云端版 | 教育版（含教学版） | 同济 | 尺寸（cm） | UE_名称 | 所属关卡 | UE路径 | 制作碰撞包围盒 | 车灯与大灯 | 主车后轴中心到box中心几何中心 |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 主车预设 Vehicle Preset | 自动驾驶-决策规划 | 自动驾驶-决策规划 |  |  | 用于Apollo决策、控制算法测试 | 否 | 否 |  | 2.0.0 | 3.5.0 删 | 决策规划 |  |  |  | TRUE | FALSE | TRUE | TRUE | TRUE |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 自动驾驶-决策规划-OBU | 自动驾驶-决策规划-OBU |  |  | 搭在用于V2X通讯的OBU设备，用于Apollo决策、控制算法测试 | 否 | 否 |  | 2.0.0 | 3.5.0 删 | 决策规划 |  |  |  | TRUE | FALSE | TRUE | TRUE | TRUE |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 手动控制-默认 | 手动控制-默认 |  |  | 用户可以通过键盘输入对主车进行控制 | 否 | 否 |  | 2.0.0 | 3.5.0 删 | 感知、手动控制 |  |  |  | TRUE | TRUE | TRUE | TRUE | TRUE |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 手动控制-感知-摄像头 | 手动控制-感知-摄像头 |  |  |  | 否 | 否 |  | 2.0.0 | 3.5.0 删 | 感知、手动控制 |  |  |  | FALSE | TRUE | TRUE | FALSE | TRUE |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 手动控制-理想传感器 | 手动控制-理想传感器 |  |  |  | 否 | 否 |  | 2.0.0 | 3.5.0 删 | 决策、手动控制 |  |  |  | FALSE | TRUE | TRUE | TRUE | TRUE |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 手动控制-激光雷达 | 手动控制-激光雷达 |  |  |  | 否 | 否 |  | 2.0.0 | 3.5.0 删 | 感知、手动控制 |  |  |  | FALSE | TRUE | TRUE | FALSE | TRUE |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | SimOneDriver控制 | SimOneDriver控制 |  |  |  | 否 | 否 |  | 2.0.0 | 3.5.0 删 | SimoneDriver |  |  |  | TRUE | TRUE | TRUE | TRUE | TRUE |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | API控制-OBU | API控制-OBU |  |  |  | 否 | 否 |  | 2.0.0 | 3.5.0 删 | API控制、OBU |  |  |  | TRUE | TRUE | TRUE | TRUE | TRUE |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | AEB | AEB |  |  | 用于测试ADAS - AEB辅助控制算法 | 否 | 否 |  | 2.0.0 | 3.5.0 删 | AEB |  |  |  | TRUE | TRUE | TRUE | TRUE | TRUE |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 手动控制-物流车 |  |  |  |  | 否 | 否 |  | 2.2.0 | 3.5.0 删 | 物流车、手动控制 |  |  |  | TRUE | TRUE | TRUE | TRUE | TRUE |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | API控制 | API Controller |  |  | 通过API接口控制主车 | 否 | 否 |  | 3.3.0 | 3.5.0 删 | API控制 |  |  |  | TRUE | TRUE | TRUE | TRUE | TRUE |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 手动控制-乘用车 | 手动控制-乘用车 |  |  | 与“手动控制-默认”可能重复 | 否 | 否 |  | 3.1.0 | 3.5.0 删 |  |  |  |  | FALSE | FALSE | TRUE |  | TRUE |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 均胜定制主车 | 均胜定制主车 |  |  |  | 否 | 否 | 均胜 |  |  |  |  |  |  | FALSE | FALSE | FALSE |  | FALSE |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 均胜定制主车 | 均胜定制主车 |  |  |  | 否 | 否 | 均胜 |  |  |  |  |  |  | FALSE | FALSE | FALSE |  | FALSE |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 挑战赛 | 挑战赛 |  |  |  | 否 | 否 |  |  |  |  |  |  |  | FALSE | FALSE | FALSE | FALSE | FALSE |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 挑战赛 | 挑战赛 |  |  |  | 否 | 否 |  |  |  |  |  |  |  | FALSE | FALSE | FALSE | FALSE | FALSE |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | API控制-默认 | API控制-默认 |  |  |  | 否 | 否 |  |  |  |  |  |  |  | TRUE | TRUE | TRUE | TRUE | TRUE |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 轿车 | Car👉Sedan |  |  |  | 是 | 是 |  | 2.0.0 |  | 轿车 |  |  |  | TRUE | TRUE | TRUE | TRUE | TRUE |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | SUV | SUV |  |  |  | 是 | 是 |  | 2.0.0 |  | SUV |  | car | suv | TRUE | TRUE | TRUE | TRUE | TRUE |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 客车 | Bus |  |  |  | 是 | 是 |  | 2.0.0 |  | 客车 |  |  |  | TRUE | TRUE | TRUE | TRUE | TRUE |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 货车 | Truck |  |  |  | 是 | 是 |  | 2.0.0 |  | 货车 |  |  |  | TRUE | TRUE | TRUE | TRUE | TRUE |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 物流车 | Autonomous Delivery Vehicle👉Delivery_Vehicle |  |  |  | 是 | 是 |  | 2.2.0 |  | 物流车 |  |  |  | TRUE | TRUE | TRUE | TRUE | TRUE |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 毫末物流车 | 毫末物流车 |  |  |  | 否 | 否 | 毫末 3.1 |  |  | 物流车 |  |  |  | FALSE | FALSE | FALSE |  | FALSE |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 毫末物流车 | 毫末物流车 |  |  |  | 否 | 否 | 毫末 3.1 |  |  | 物流车 |  |  |  | FALSE | FALSE | FALSE |  | FALSE |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 毫末乘用车 | 毫末乘用车 |  |  |  | 否 | 否 | 毫末 3.1 |  |  | SUV |  |  |  | FALSE | FALSE | FALSE |  | FALSE |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 毫末乘用车 | 毫末乘用车 |  |  |  | 否 | 否 | 毫末 3.1 |  |  | SUV |  |  |  | FALSE | FALSE | FALSE |  | FALSE |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 五菱观光车 | 五菱观光车 |  |  |  | 否 | 否 | 广西五菱 2.2 |  |  | 低速小巴 |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 五菱观光车 | 五菱观光车 |  |  |  | 否 | 否 | 广西五菱 2.2 |  |  | 低速小巴 |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 五菱太空舱 | 五菱太空舱 |  |  |  | 否 | 否 | 广西五菱 2.2 |  |  | 低速小巴 |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 五菱太空舱 | 五菱太空舱 |  |  |  | 否 | 否 | 广西五菱 2.2 |  |  | 低速小巴 |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 北航实验小车 | 北航实验小车 |  |  |  | 否 | 否 | 北航 |  |  | 实验小车、V2X |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 北航实验小车 | 北航实验小车 |  |  |  | 否 | 否 | 北航 |  |  | 实验小车、V2X |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 九曜牵引车 | JY_Tractor |  |  | 上海汽检WAIC大赛定制模型 | 否 | 否 | 人工智能大赛 |  |  | 牵引车、机场 |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 九曜牵引车 | JY_Tractor |  |  | 上海汽检WAIC大赛定制模型 | 否 | 否 | 人工智能大赛 |  |  | 牵引车、机场 |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 仓擎牵引车 | 仓擎牵引车 |  |  | 上海汽检WAIC大赛定制模型 | 否 | 否 | 人工智能大赛 |  |  | 牵引车、机场 |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 仓擎牵引车 | 仓擎牵引车 |  |  | 上海汽检WAIC大赛定制模型 | 否 | 否 | 人工智能大赛 |  |  | 牵引车、机场 |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 博雷顿重卡 | 博雷顿重卡 |  |  | 上海汽检WAIC大赛定制模型 | 否 | 否 | 人工智能大赛 |  |  | 货运车、港口 |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 博雷顿重卡 | 博雷顿重卡 |  |  | 上海汽检WAIC大赛定制模型 | 否 | 否 | 人工智能大赛 |  |  | 货运车、港口 |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 友道智途重卡 | 友道智途重卡 |  |  | 上海汽检WAIC大赛定制模型 | 否 | 否 | 人工智能大赛 |  |  | 货运车、港口 |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 友道智途重卡 | 友道智途重卡 |  |  | 上海汽检WAIC大赛定制模型 | 否 | 否 | 人工智能大赛 |  |  | 货运车、港口 |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 同润科技重卡 | 同润科技重卡 |  |  | 上海汽检WAIC大赛定制模型 | 否 | 否 | 人工智能大赛 |  |  | 货运车、港口 |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 同润科技重卡 | 同润科技重卡 |  |  | 上海汽检WAIC大赛定制模型 | 否 | 否 | 人工智能大赛 |  |  | 货运车、港口 |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 小马智行无人车 | 小马智行无人车 |  |  | 上海汽检WAIC大赛定制模型 | 否 | 否 | 人工智能大赛 |  |  | 无人出租 |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 小马智行无人车 | 小马智行无人车 |  |  | 上海汽检WAIC大赛定制模型 | 否 | 否 | 人工智能大赛 |  |  | 无人出租 |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 斯润天朗无人车 | 斯润天朗无人车 |  |  | 上海汽检WAIC大赛定制模型 | 否 | 否 | 人工智能大赛 |  |  | 无人出租 |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 斯润天朗无人车 | 斯润天朗无人车 |  |  | 上海汽检WAIC大赛定制模型 | 否 | 否 | 人工智能大赛 |  |  | 无人出租 |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 赛可无人车 | 赛可无人车 |  |  | 上海汽检WAIC大赛定制模型 | 否 | 否 | 人工智能大赛 |  |  | 无人出租 |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 赛可无人车 | 赛可无人车 |  |  | 上海汽检WAIC大赛定制模型 | 否 | 否 | 人工智能大赛 |  |  | 无人出租 |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 无人清扫车 | Sweeper |  |  |  | 否 | 否 | 郑州大赛 |  |  | 无人清扫车 |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 牵引车 | Aircraft Tractor |  |  |  | 否 | 否 | 郑州大赛 |  |  | 牵引车、机场 |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 重卡 | Heavy Truck |  |  |  | 否 | 否 | 郑州大赛 |  |  | 货运车、港口 |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 主车-API | MKZ-API |  |  |  | 否 | 否 | 郑州大赛 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 牵引车-API | Tractor-API |  |  |  | 否 | 否 | 郑州大赛 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 重卡-API | Heavy Truck-API |  |  |  | 否 | 否 | 郑州大赛 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 大巴-API | Bus-API |  |  |  | 否 | 否 | 郑州大赛 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 物流车-API | Cargo Van-API |  |  |  | 否 | 否 | 郑州大赛 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 主车-Simulink | MKZ-Simulink |  |  |  | 否 | 否 | 郑州大赛 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 牵引车-Simulink | Tractor-Simulink |  |  |  | 否 | 否 | 郑州大赛 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 重卡-Simulink | Heavy Truck-Simulink |  |  |  | 否 | 否 | 郑州大赛 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 大巴-Simulink | Bus-Simulink |  |  |  | 否 | 否 | 郑州大赛 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 物流车-Simulink | Cargo Van-Simulink |  |  |  | 否 | 否 | 郑州大赛 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 上汽大众主车 | VW_MKZ |  |  |  | 否 | 否 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 上汽大众主车 | VW_MKZ |  |  |  | 否 | 否 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 天一牵引车 | TY_Tractor |  |  |  | 否 | 否 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 天一牵引车 | TY_Tractor |  |  |  | 否 | 否 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 英博超算物流车 | YBCS_CargoVan |  |  |  | 否 | 否 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 英博超算物流车 | YBCS_CargoVan |  |  |  | 否 | 否 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 北理工物流车 | BIT_CargoVan |  |  |  | 否 | 否 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 北理工物流车 | BIT_CargoVan |  |  |  | 否 | 否 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 酷黑物流车 | KH_CargoVan |  |  |  | 否 | 否 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 酷黑物流车 | KH_CargoVan |  |  |  | 否 | 否 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 禾多大巴 | HD_Bus |  |  |  | 否 | 否 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 禾多大巴 | HD_Bus |  |  |  | 否 | 否 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 帆一重卡 | FY_HeavyTruck |  |  |  | 否 | 否 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 帆一重卡 | FY_HeavyTruck |  |  |  | 否 | 否 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 盟识重卡 | MS_HeavyTruck |  |  |  | 否 | 否 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 盟识重卡 | MS_HeavyTruck |  |  |  | 否 | 否 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 九曜重卡 | JY_HeavyTruck |  |  |  | 否 | 否 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 九曜重卡 | JY_HeavyTruck |  |  |  | 否 | 否 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 小车01 | Car01 |  |  |  | 否 | 否 | 同济 3.4 sim_tj_vil |  |  |  |  |  |  |  |  |  |  |  | TRUE |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 小车01 | Car01 |  |  |  | 否 | 否 | 同济 3.4 sim_tj_vil |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 贩卖车01 | VendorTruck01 |  |  |  | 否 | 否 | 同济 3.4 sim_tj_vil |  |  |  |  |  |  |  |  |  |  |  | TRUE |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 贩卖车01 | VendorTruck01 |  |  |  | 否 | 否 | 同济 3.4 sim_tj_vil |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 公交车01 | Bus01 |  |  |  | 否 | 否 | 同济 3.4 sim_tj_vil |  |  |  |  |  |  |  |  |  |  |  | TRUE |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 公交车01 | Bus01 |  |  |  | 否 | 否 | 同济 3.4 sim_tj_vil |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 牵引车01 | TractorTruck01 |  |  |  | 否 | 否 | 同济 3.4 sim_tj_vil |  |  |  |  |  |  |  |  |  |  |  | TRUE |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 牵引车01 | TractorTruck01 |  |  |  | 否 | 否 | 同济 3.4 sim_tj_vil |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 行李车01 | LuggageCar01 |  |  |  | 否 | 否 | 同济 3.4 sim_tj_vil |  |  |  |  |  |  |  |  |  |  |  | TRUE |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 行李车01 | LuggageCar01 |  |  |  | 否 | 否 | 同济 3.4 sim_tj_vil |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 出租车01 | Taxi01 |  |  |  | 否 | 否 | 同济 3.4 sim_tj_vil |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 出租车01 | Taxi01 |  |  |  | 否 | 否 | 同济 3.4 sim_tj_vil |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 卡车01 | Truck01 |  |  |  | 否 | 否 | 同济 3.4 sim_tj_vil |  |  |  |  |  |  |  |  |  |  |  | TRUE |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 卡车01 | Truck01 |  |  |  | 否 | 否 | 同济 3.4 sim_tj_vil |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 卡车02 | Truck02 |  |  |  | 否 | 否 | 云南交通职业学院 3.4 |  |  | 卡车 |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 卡车02 | Truck02 |  |  |  | 否 | 否 | 云南交通职业学院 3.4 |  |  | 卡车 |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 公交车02 | Bus02 |  |  |  | 否 | 否 | 云南交通职业学院 3.4 |  |  | 公交车 |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 公交车02 | Bus02 |  |  |  | 否 | 否 | 云南交通职业学院 3.4 |  |  | 公交车 |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 小车02 | Car02 |  |  | 云南交通职业学院项目驾培用车 | 否 | 否 | 云南交通职业学院 3.4 |  |  | 小车、桑塔纳2021 |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 小车02 | Car02 |  |  | 云南交通职业学院项目驾培用车 | 否 | 否 | 云南交通职业学院 3.4 |  |  | 小车、桑塔纳2021 |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 坦克01 | Tank01 |  |  |  | 否 | 否 | 长沙理工大学 3.4 |  |  | 坦克 |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 坦克01 | Tank01 |  |  |  | 否 | 否 | 长沙理工大学 3.4 |  |  | 坦克 |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 主车 | 主车 |  |  | 默认主车 | 是 | 是 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | OBU主车 | OBU主车 |  |  | 默认OBU主车，协作版已支持 | 是 | 是 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 长城旅行车01 | ChangChengCar01 |  |  |  | 否 | 否 | 长城 3.6 sim_gwm |  |  | 旅行车 |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 长城旅行车01 | ChangChengCar01 |  |  |  | 否 | 否 | 长城 3.6 sim_gwm |  |  | 旅行车 |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 小车03 | Car03 |  |  |  | 否 | 否 | 航一102所 3.4 sim_aim |  |  | 小车、桑塔纳2021、迷彩喷漆 |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 小车03 | Car03 |  |  |  | 否 | 否 | 航一102所 3.4 sim_aim |  |  | 小车、桑塔纳2021、迷彩喷漆 |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 智己L6 | ZhiJiL6 |  |  |  | 否 | 否 | 上汽平台POC 3.6 sim_sheitc |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 智己L6 | ZhiJiL6 |  |  |  | 否 | 否 | 上汽平台POC 3.6 sim_sheitc |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 中耕机_220_P7000 | P7000_Narrow_220_Cult |  |  | 高密玉米地垄宽110cm，跨两垄，窄胎 | 否 | 否 | 潍柴 3.6 sim_lovol |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 中耕机_220_P7000 | P7000_Narrow_220_Cult |  |  | 高密玉米地垄宽110cm，跨两垄，窄胎 | 否 | 否 | 潍柴 3.6 sim_lovol |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 中耕机_260_P7000 | P7000_Narrow_260_Cult |  |  | 高密玉米地垄宽130cm，跨两垄，窄胎 | 否 | 否 | 潍柴 3.6 sim_lovol |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 中耕机_260_P7000 | P7000_Narrow_260_Cult |  |  | 高密玉米地垄宽130cm，跨两垄，窄胎 | 否 | 否 | 潍柴 3.6 sim_lovol |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 翻转犁_P7000 | P7000_Std_RevPlow |  |  | 马司农场，标胎 | 否 | 否 | 潍柴 3.6 sim_lovol |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 翻转犁_P7000 | P7000_Std_RevPlow |  |  | 马司农场，标胎 | 否 | 否 | 潍柴 3.6 sim_lovol |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 播种机_P7000 | P7000_Std_Seeder |  |  | 马司农场，标胎 | 否 | 否 | 潍柴 3.6 sim_lovol |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 播种机_P7000 | P7000_Std_Seeder |  |  | 马司农场，标胎 | 否 | 否 | 潍柴 3.6 sim_lovol |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 播种机_260_P7000 | P7000_Std_260_Seeder |  |  | 马司高密都用，窄胎 | 否 | 否 | 潍柴 3.6 sim_lovol |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 播种机_260_P7000 | P7000_Std_260_Seeder |  |  | 马司高密都用，窄胎 | 否 | 否 | 潍柴 3.6 sim_lovol |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | CICV观光车 | CICV_ShuttleBus |  |  |  | 否 | 否 | 国汽智联国赛 cicv_synth |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | CICV观光车 | CICV_ShuttleBus |  |  |  | 否 | 否 | 国汽智联国赛 cicv_synth |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | Nissan01 | Nissan01 |  |  |  | 否 | 否 | 日产POC 3.6 sim_vnrc |  |  |  |  |  |  |  |  |  |  |  |  | 460*217*168 | BP_VEH_AriyaCar |  | /Game/Library2025/06_EgoVehicle/Project/RC/BP_VEH_AriyaCar.BP_VEH_AriyaCar | □ | □ |  |
| 主车预设 Vehicle Preset | Nissan01 | Nissan01 |  |  |  | 否 | 否 | 日产POC 3.6 sim_vnrc |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | RTG01 | RTG01 |  |  |  | 否 | 否 | 劢擎 3.6 sim_matchine_tech |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | RTG01 | RTG01 |  |  |  | 否 | 否 | 劢擎 3.6 sim_matchine_tech |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | RTG02 | RTG02 |  |  | 带吊具线缆 | 否 | 否 | 劢擎 3.6 sim_matchine_tech |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | RTG02 | RTG02 |  |  | 带吊具线缆 | 否 | 否 | 劢擎 3.6 sim_matchine_tech |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | CQJS01 | CQJS01 |  |  |  | 否 | 否 | 重庆建设工业集团（296）3.6售前 sim_cqjsi |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | CQJS01 | CQJS01 |  |  |  | 否 | 否 | 重庆建设工业集团（296）3.6售前 sim_cqjsi |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | CQJS_机器狗01 | CQJS_RobotDog01 |  |  |  | 否 | 否 | 重庆建设工业集团（296）3.6售前 sim_cqjsi |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | CQJS_机器狗01 | CQJS_RobotDog01 |  |  |  | 否 | 否 | 重庆建设工业集团（296）3.6售前 sim_cqjsi |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | CQJS_坦克01 | CQJS_Tank01 |  |  |  | 否 | 否 | 重庆建设工业集团（296）3.6售前 sim_cqjsi |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | CQJS_坦克01 | CQJS_Tank01 |  |  |  | 否 | 否 | 重庆建设工业集团（296）3.6售前 sim_cqjsi |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 拖拉机01 | Tractor01 |  |  |  | 否 | 否 | 潍柴 3.6 sim_lovol |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 拖拉机01 | Tractor01 |  |  |  | 否 | 否 | 潍柴 3.6 sim_lovol |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 平地机01 | Grader01 |  |  |  | 否 | 否 | 潍柴 3.6 sim_lovol |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 平地机01 | Grader01 |  |  |  | 否 | 否 | 潍柴 3.6 sim_lovol |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 矿卡01 | Truck01 |  |  |  | 否 | 否 | 中联重工POC zoomlion_hil_poc |  |  |  |  |  |  |  |  |  |  |  |  | 1040*556*436 | BP_VEH_ConstructionTruck |  | /Game/Library2025/06_EgoVehicle/Project/UEStandardize/BP_VEH_GeCaoJi.BP_VEH_GeCaoJi | □ | □ |  |
| 主车预设 Vehicle Preset | 矿卡01 | Truck01 |  |  |  | 否 | 否 | 中联重工POC zoomlion_hil_poc |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 自动割草机01 | RoboticMower01 |  |  |  | 否 | 否 | 苏州宝时得POC UEStandardize |  |  |  |  |  |  |  |  |  |  |  |  | 186*117*79 | BP_VEH_GeCaoJi |  | /Game/ArtMap/2024/99_DemoPOC/Mesh/GeCaoJi/BP_VEH_GeCaoJi.BP_VEH_GeCaoJi | □ | □ |  |
| 主车预设 Vehicle Preset | 自动割草机01 | RoboticMower01 |  |  |  | 否 | 否 | 苏州宝时得POC UEStandardize |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | □ | □ |  |
| 主车模型 Vehicle Model | 轿车_右舵 | Sedan_Right👉Sedan_RHD |  |  | 因为国际化所以后续需要进基线 | 是 | 待分配 | release HKPC | 3.7.0 |  | 轿车，右舵 |  |  |  |  |  |  |  |  |  | 502*213*150 | BP_VEH_MKZ2017_RHD | Release_AssetMap | /Game/Library2025/06_EgoVehicle/Release/MKZ2017_RHD/BP_VEH_MKZ2017_RHD.BP_VEH_MKZ2017_RHD | □ | □ |  |
| 主车预设 Vehicle Preset | 轿车_右舵 | Sedan_Right |  |  | 因为国际化所以后续需要进基线 | 否 | 待分配 | release HKPC |  |  |  |  |  |  |  |  |  |  |  |  | 502*213*175 | BP_VEH_MKZ2017_RHD | Release_AssetMap | /Game/Library2025/06_EgoVehicle/Release/MKZ2017_RHD/BP_VEH_MKZ2017_RHD.BP_VEH_MKZ2017_RHD | □ | □ |  |
| 主车模型 Vehicle Model | VW313 | VW313 |  |  | 无车体 | 否 | 否 | 酷睿程 3.5 sim_carizon |  |  |  |  |  |  |  |  |  |  |  |  | 485*211*136 | BP_VEH_Carizon_01 | Carizon_Asset | /Game/Library2025/06_EgoVehicle/Project/Carizon/BP_VEH_Carizon_01.BP_VEH_Carizon_01 | □ | □ |  |
| 主车模型 Vehicle Model | 长城蓝山2023 | GWM_WEY_Blue Mountain2023 |  |  |  | 否 | 否 | 东软智行 |  |  |  |  |  |  |  |  |  |  |  |  | 514*223*178 | BP_VEH_ChangChengLanShan | Neusoft_Assetmap | /Game/Library2025/06_EgoVehicle/Project/neusoft/BP_VEH_ChangChengLanShan.BP_VEH_ChangChengLanShan | □ | □ | 145 |
| 主车预设 Vehicle Preset | 长城蓝山2023 | GWM_WEY_Blue Mountain2023 |  |  |  | 否 | 否 | 东软智行 |  |  |  |  |  |  |  |  |  |  |  |  | 514*223*178 | BP_VEH_ChangChengLanShan | Neusoft_Assetmap | /Game/Library2025/06_EgoVehicle/Project/neusoft/BP_VEH_ChangChengLanShan.BP_VEH_ChangChengLanShan | □ | □ | 145 |
| 主车模型 Vehicle Model | 极氪001 | Geely_Zeekr001 |  |  |  | 否 | 否 | 吉利 geely_hil |  |  |  |  |  |  |  |  |  |  |  |  | 498*227*177 | BP_VEH_Zeekr001 | Asset_Geely | /Game/Library2025/06_EgoVehicle/Project/geely/BP_VEH_Zeekr001.BP_VEH_Zeekr001 | □ | □ |  |
| 主车模型 Vehicle Model | 吉利星越L | Geely_XingYue_L |  |  |  | 否 | 否 | 吉利 geely_hil |  |  |  |  |  |  |  |  |  |  |  |  | 500*223*204 | BP_VEH_XingYue | Asset_Geely | /Game/Library2025/06_EgoVehicle/Project/geely/BP_VEH_XingYue.BP_VEH_XingYue | □ | □ |  |
| 主车模型 Vehicle Model | ACAR | ACAR |  |  |  | 否 | 否 | 酷睿程 3.5 sim_carizon |  |  |  |  |  |  |  |  |  |  |  |  | 481*206*152 | ACAR | L_Carizon_Asset_01 | /Game/ArtMap/95_Carizon/BP_Main_01/ACAR.ACAR_C | □ | □ |  |
| 主车模型 Vehicle Model | CCAR | CCAR |  |  |  | 否 | 否 | 酷睿程 3.5 sim_carizon |  |  |  |  |  |  |  |  |  |  |  |  | 453*208*141 | CCAR | L_Carizon_Asset_01 | /Game/ArtMap/95_Carizon/BP_Main_01/ACAR.CCAR_C | □ | □ |  |
| 主车模型 Vehicle Model | J01 | J01 |  |  |  | 否 | 否 | 酷睿程 3.5 sim_carizon |  |  |  |  |  |  |  |  |  |  |  |  | 479*210*149 | J01 | L_Carizon_Asset_01 | /Game/ArtMap/95_Carizon/BP_Main_01/ACAR.J01_C | □ | □ |  |
| 主车模型 Vehicle Model | 奔驰CLA2025 | BenzCLA2025 |  |  |  | 否 | 否 | 奔驰二期 |  |  |  |  |  |  |  |  |  |  |  |  | 480*202*152 | BP_Benz_CLA_01 | Benz_Asset | /Game/Library2025/06_EgoVehicle/Project/Benz/BP_Benz_CLA_01.BP_Benz_CLA_01_C | □ | □ |  |
| 主车模型 Vehicle Model | ZT160HEV | ZT160HEV |  |  |  | 否 | 否 | 中联重科 3.8 zoomlion_hil |  |  |  |  |  |  |  |  |  |  |  |  | 1130*515*465 |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | ZT160HEV_空载 | ZT160HEV_Empty |  |  |  | 否 | 否 | 中联重科 3.8 zoomlion_hil |  |  |  |  |  |  |  |  |  |  |  |  | 1130*515*465 |  |  |  | □ | □ |  |
| 主车预设 Vehicle Preset | 现代伊兰特 | HyundaiAVANTEN |  |  |  | 否 | 否 | 现代UX |  |  |  |  |  |  |  |  |  |  |  |  | 468*213*144 | BP_VEH_AVANTEN_01 | L_Huyundai_Dil_Assetmap | /Game/Library2025/06_EgoVehicle/Project/Hyundai_DIL/BP_VEH_AVANTEN_01.BP_VEH_AVANTEN_01 | □ | □ | 128 |
| 主车预设 Vehicle Preset | 中联重卡 | Zoomlion_Truck |  |  |  | 否 | 否 | 中联重科 3.8 zoomlion_hil |  |  |  |  |  |  |  |  |  |  |  |  | 1756*313*466 | BP_Zoomlion_Truck_02 | zoomlion_hil_poc_Assetmap | /Game/Library2025/06_EgoVehicle/Project/zoomlion_hil_poc/BP_Zoomlion_Truck_02.BP_Zoomlion_Truck_02 | □ | □ |  |
| 主车预设 Vehicle Preset | 中联重卡_空载 | Zoomlion_Truck_Empty |  |  |  | 否 | 否 | 中联重科 3.8 zoomlion_hil |  |  |  |  |  |  |  |  |  |  |  |  |  | BP_Zoomlion_Truck_03 | zoomlion_hil_poc_Assetmap | /Game/Library2025/06_EgoVehicle/Project/zoomlion_hil_poc/BP_Zoomlion_Truck_03.BP_Zoomlion_Truck_03 | □ | □ |  |
| 主车预设 Vehicle Preset | 吉利银河 | Geely_Galaxy_A7 |  |  |  | 否 | 否 | 吉利 geely_hil |  |  |  |  |  |  |  |  |  |  |  |  | 506*210*151 | BP_VEH_Geely_Galaxy_A7 | Asset_Geely | /Game/Library2025/06_EgoVehicle/Project/geely/BP_VEH_Geely_Galaxy_A7.BP_VEH_Geely_Galaxy_A7 | □ | □ |  |
| 主车预设 Vehicle Preset | 毅力号 | Perseverance |  |  |  | 否 | 否 | 深空探测 3.8 dsel_sim |  |  |  |  |  |  |  |  |  |  |  |  | 408*270*223 | BP_Perseverance | L_SKFZ_Assets | /Game/ArtMap/2024/22_SKFZ/Jezero/Perseverance/BP_VEH_Perseverance.BP_VEH_Perseverance | □ | □ |  |
| 主车预设 Vehicle Preset | 机智号 | Ingenuity |  |  |  | 否 | 否 | 深空探测 3.8 dsel_sim |  |  |  |  |  |  |  |  |  |  |  |  | 98*110*56 | BP_Ingenuity | L_SKFZ_Assets | /Game/ArtMap/2024/22_SKFZ/Jezero/ingenuity/BP_VEH_Ingenuity.BP_VEH_Ingenuity | □ | □ |  |
| 主车预设 Vehicle Preset | 中联重卡 | Zoomlion_Excavator |  |  |  | 否 | 否 | 中联重科 3.8 zoomlion_hil |  |  |  |  |  |  |  |  |  |  |  |  | 596*235*542 | BP_Zoomlion_Excavator | zoomlion_hil_poc_Assetmap | /Game/Library2025/06_EgoVehicle/Project/zoomlion_hil_poc/BP_Zoomlion_Excavator.BP_Zoomlion_Excavator | □ | □ |  |
