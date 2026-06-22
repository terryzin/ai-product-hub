---
source_file: "仿真平台资源汇总.xlsx"
sheet: "传感器 Sensor"
header_row: 3
data_rows: 40
columns: 33
note: "1. 劢勤，定位传感器GNSS和IMU分开，原本的定位传感器要不要删 SimOne新增激光雷达模型\n 2 . 目标传感器和物理传感器的区别"
groups:
  "版本管理": [E, F, G, H, I]
  "型号信息": [P, Q, R, S, T, U]
extracted: 2026-06-21
---

# 传感器 Sensor

## 说明

> 1. 劢勤，定位传感器GNSS和IMU分开，原本的定位传感器要不要删 SimOne新增激光雷达模型<br> 2 . 目标传感器和物理传感器的区别

## 字段字典

| # | 列 | 字段名 | 分组 |
|---|---|---|---|
| 1 | A | 细分-中英文 |  |
| 2 | B | 资源-中文 |  |
| 3 | C | 资源-英文 |  |
| 4 | D | 缩略图 |  |
| 5 | E | 企业版⭐科研版 | 版本管理 |
| 6 | F | 教学版 | 版本管理 |
| 7 | G | 项目版本⭐ | 版本管理 |
| 8 | H | 实现版本 | 版本管理 |
| 9 | I | 更新版本 | 版本管理 |
| 10 | J | 备注 |  |
| 11 | K | 公有云 |  |
| 12 | L | 社区版 |  |
| 13 | M | 协作版 |  |
| 14 | N | 企业版-单机版 |  |
| 15 | O | 企业版-云端版 |  |
| 16 | P | 型号-软件配置项 | 型号信息 |
| 17 | Q | 模组/相机整机型号Model | 型号信息 |
| 18 | R | 图像传感器芯片Sensor | 型号信息 |
| 19 | S | 镜头型号Lens | 型号信息 |
| 20 | T | 水平视场角HFOV | 型号信息 |
| 21 | U | 分辨率 | 型号信息 |
| 22 | V | Tag |  |
| 23 | W | 项目-毫末 |  |
| 24 | X | 项目-清华模拟器 |  |
| 25 | Y | 项目-均胜 |  |
| 26 | Z | 项目-国创大赛 |  |
| 27 | AA | 人工智能大赛 |  |
| 28 | AB | 地平线二期 |  |
| 29 | AC | 劢擎港机 |  |
| 30 | AD | Comments |  |
| 31 | AE | Source |  |
| 32 | AF | Release Version |  |
| 33 | AG | 适用场景 |  |

## 数据（40 行）

| 细分-中英文 | 资源-中文 | 资源-英文 | 缩略图 | 企业版⭐科研版 | 教学版 | 项目版本⭐ | 实现版本 | 更新版本 | 备注 | 公有云 | 社区版 | 协作版 | 企业版-单机版 | 企业版-云端版 | 型号-软件配置项 | 模组/相机整机型号Model | 图像传感器芯片Sensor | 镜头型号Lens | 水平视场角HFOV | 分辨率 | Tag | 项目-毫末 | 项目-清华模拟器 | 项目-均胜 | 项目-国创大赛 | 人工智能大赛 | 地平线二期 | 劢擎港机 | Comments | Source | Release Version | 适用场景 |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 目标级传感器 Object Sensor | 理想传感器 | Ideal Sensor |  | 是 | 是 |  |  |  |  | TRUE | TRUE | TRUE | TRUE | TRUE |  |  |  |  |  |  |  | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE |  |  |  | 2.0.0 |  |
| 目标级传感器 Object Sensor | 目标级激光雷达 | Object Lidar |  | 是 | 是 |  |  |  |  | TRUE | TRUE | TRUE | TRUE | TRUE |  |  |  |  |  |  |  | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE |  |  |  | 2.0.0 |  |
| 目标级传感器 Object Sensor | 目标级摄像头 | Object Camera |  | 是 | 是 |  |  |  |  | TRUE | TRUE | TRUE | TRUE | TRUE |  |  |  |  |  |  |  | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE |  |  |  | 2.0.0 |  |
| 目标级传感器 Object Sensor | 目标级毫米波雷达 | Object Radar |  | 是 | 是 |  |  |  |  | TRUE | TRUE | TRUE | TRUE | TRUE |  |  |  |  |  |  |  | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE |  |  |  | 2.0.0 |  |
| 目标级传感器 Object Sensor | 目标级超声波雷达 | Object Ultrasonic Sensor |  | 是 | 是 |  |  |  |  | TRUE | TRUE | TRUE | TRUE | TRUE |  |  |  |  |  |  |  | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE |  |  |  | 2.0.0 |  |
| 摄像头 Camera | 摄像头 | Camera |  | 是 | 是 |  |  |  |  | FALSE | TRUE | TRUE | TRUE | FALSE | 内置自定义 |  |  |  | 60 | 1920x1080 |  | TRUE | TRUE | TRUE | FALSE | TRUE | TRUE |  |  |  | 2.0.0 |  |
| 摄像头 Camera | 720P 鱼眼 | 720P Fisheye |  | 是 | 是 |  |  |  |  | FALSE | TRUE | TRUE | TRUE | FALSE | 内置自定义 |  |  |  | 150 | 1282*720 |  | TRUE | TRUE | TRUE | FALSE | TRUE | TRUE |  |  |  | 2.0.0 |  |
| 摄像头 Camera | 1200P F60° S | 1200P F60° S |  | 是 | 是 |  |  |  | 中距视角，自动驾驶常用 | FALSE | TRUE | TRUE | TRUE | FALSE | AR0231_Sekonix60 | 世高光 Sekonix 3325-100 | 安森美 Onsemi AR0231 | 世高光 Sekonix NA6062 | 60 | 1920x1200 |  | TRUE | TRUE | TRUE | FALSE | TRUE | TRUE |  |  |  | 2.0.0 | 车载/室外 |
| 摄像头 Camera | 1200P F120° S | 1200P F120° S |  | 是 | 是 |  |  |  | 广角，自动驾驶常用 | FALSE | TRUE | TRUE | TRUE | FALSE | AR0231_Sekonix120 | 世高光 Sekonix 3324-100 | 安森美 Onsemi AR0231 | 世高光 Sekonix NA1262 | 120 | 1920x1200 |  | TRUE | TRUE | TRUE | FALSE | TRUE | TRUE |  |  |  | 2.0.0 | 车载/室外 |
| 摄像头 Camera | 1200P F50° R | 1200P F50° R |  | 是 | 是 |  |  |  | 同一相机换不同镜头 | FALSE | TRUE | TRUE | TRUE | FALSE | IMX249_Richo50 | 宝视纳 Basler acA1920-40gc | 索尼 Sony IMX249 | 理光 RICOH_FL-BC1220-9M | 50 | 1920x1200 |  | TRUE | TRUE | TRUE | FALSE | TRUE | TRUE |  |  |  | 2.0.0 | 工业/室内/高速 |
| 摄像头 Camera | 1200P F25° R | 1200P F25° R |  | 是 | 是 |  |  |  | 同一相机换不同镜头 | FALSE | TRUE | TRUE | TRUE | FALSE | IMX249_Richo25 | 宝视纳 Basler acA1920-40gc | 索尼 Sony IMX249 | 理光 RICOH_FL-BC2518-9M | 25 | 1920x1200 |  | TRUE | TRUE | TRUE | FALSE | TRUE | TRUE |  |  |  | 2.0.0 | 工业/室内/高速 |
| 摄像头 Camera | 1200P F50° M | 1200P F50° M |  | 是 | 是 |  |  |  | 同一相机换不同镜头 | FALSE | TRUE | TRUE | TRUE | FALSE | IMX249_Moritex50 | 宝视纳 Basler acA1920-40gc | 索尼 Sony IMX249 | 茉丽特 MORITEX_ML-U1217SR-18C | 50 | 1920x1200 |  | TRUE | TRUE | TRUE | FALSE | TRUE | TRUE |  |  |  | 2.0.0 | 工业/室内/高速 |
| 摄像头 Camera | 1200P F25° M | 1200P F25° M |  | 是 | 是 |  |  |  | 同一相机换不同镜头 | FALSE | TRUE | TRUE | TRUE | FALSE | IMX249_Moritex25 | 宝视纳 Basler acA1920-40gc | 索尼 Sony IMX249 | 茉丽特 MORITEX_ML-U2515SR-18C | 25 | 1920x1200 |  | TRUE | TRUE | TRUE | FALSE | TRUE | TRUE |  |  |  | 2.0.0 | 工业/室内/高速 |
| 摄像头 Camera | 1200P F80° K | 1200P F80° K |  | 是 | 是 |  |  |  | 同一相机换不同镜头 | FALSE | TRUE | TRUE | TRUE | FALSE | IMX249_Kowa80 | 宝视纳 Basler acA1920-40gc | 索尼 Sony IMX249 | 兴和 Kowa_LM6HC | 80 | 1920x1200 |  | TRUE | TRUE | TRUE | FALSE | TRUE | TRUE |  |  |  | 2.0.0 | 工业/室内/高速 |
| 摄像头 Camera | 960P F31.2° E | 960P F31.2° E |  | 是 | 是 |  |  |  |  | FALSE | TRUE | TRUE | TRUE | FALSE | ICX267_Edmund312 | 灰点 PointGrey FL3-GE-14S3C-C | 索尼 Sony ICX267 | 爱特蒙特光学 Edmund Optics NT58-365 | 31.2 | 1280x960 |  | TRUE | TRUE | TRUE | FALSE | TRUE | TRUE |  |  |  | 2.0.0 |  |
| 摄像头 Camera | 960P F93.6° E | 960P F93.6° E |  | 是 | 是 |  |  |  |  | FALSE | TRUE | TRUE | TRUE | FALSE | ICX267_Edmund936 | 灰点 PointGrey FL3-GE-14S3C-C | 索尼 Sony ICX267 | 爱特蒙特光学 Edmund Optics NT58-365 | 93.6 | 1280x960 |  | TRUE | TRUE | TRUE | FALSE | TRUE | TRUE |  |  |  | 2.0.0 |  |
| 激光雷达 Lidar | 激光雷达 | Lidar |  | 是 | 是 |  |  |  |  | FALSE | TRUE | TRUE | TRUE | FALSE | 内置自定义（机械扫描） |  |  |  |  |  |  | TRUE | TRUE | TRUE | FALSE | TRUE | TRUE |  |  |  | 2.0.0 |  |
| 激光雷达 Lidar | F360° HS-P64 | F360° HS-P64 |  | 是 | 是 |  |  |  |  | FALSE | TRUE | TRUE | TRUE | FALSE | 禾塞 Pandar64（机械扫描） |  |  |  |  |  |  | TRUE | TRUE | TRUE | FALSE | TRUE | TRUE |  |  |  | 2.0.0 |  |
| 激光雷达 Lidar | F120° HS-AT128 | F120° HS-AT128 |  | 是 | 是 |  |  |  |  |  |  | TRUE | TRUE | FALSE | 禾塞 AT128（混合固态） |  |  |  |  |  |  | TRUE | TRUE | TRUE | FALSE | TRUE | TRUE |  |  |  |  |  |
| 激光雷达 Lidar | F360° HS-P128 | F360° HS-P128 |  | 是 | 是 | 地平线二期 3.4 |  |  | 地平线2期要求的 |  |  | TRUE | TRUE | FALSE | 禾塞 Pandar128（机械扫描） |  |  |  |  |  |  |  |  |  | FALSE |  | TRUE |  |  |  |  |  |
| 激光雷达 Lidar | F360° V-HDL64 | F360° V-HDL64 |  | 否 | 否 |  |  |  | 国内基本没人用，可通过默认参数配置进行支持 | FALSE | TRUE | FALSE | FALSE | FALSE | 威力登 Velodyne-HDL64（自定义机械扫描） |  |  |  |  |  |  | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE |  |  |  | 2.0.0 |  |
| 激光雷达 Lidar | F360° V-VLP16 | F360° V-VLP16 |  | 是 | 是 |  |  |  |  | FALSE | TRUE | TRUE | TRUE | FALSE | 威力登 Velodyne-VLP16（机械扫描） |  |  |  |  |  |  | TRUE | TRUE | TRUE | FALSE | TRUE | TRUE |  |  |  | 2.0.0 |  |
| 激光雷达 Lidar | F360° RS-L32 | F360° RS-L32 |  | 是 | 是 |  |  |  |  | FALSE | TRUE | TRUE | TRUE | FALSE | 速腾 Robosense-L32（混合固态） |  |  |  |  |  |  | TRUE | TRUE | TRUE | FALSE | TRUE | TRUE |  |  |  | 2.0.0 |  |
| 激光雷达 Lidar | F120° RS-M1 | F120° RS-M1 |  | 是 | 是 |  |  |  |  | FALSE | TRUE | TRUE | TRUE | FALSE | 速腾 Robosense-M1（半固态） |  |  |  |  |  |  | TRUE | TRUE | TRUE | FALSE | TRUE | TRUE |  |  |  | 3.1.0 |  |
| 激光雷达 Lidar | F70.4° L-Mid70 | F70.4° L-Mid70 |  | 是 | 是 |  |  |  |  | FALSE | TRUE | TRUE | TRUE | FALSE | 览沃 Livox-Mid70（固态） |  |  |  |  |  |  | TRUE | TRUE | TRUE | FALSE | TRUE | TRUE |  |  |  | 3.1.0 |  |
| 激光雷达 Lidar | F81.7° L-Horizon | F81.7° L-Horizon |  | 是 | 是 |  |  |  |  | FALSE | TRUE | TRUE | TRUE | FALSE | 览沃 Livox-Horizon（固态） |  |  |  |  |  |  | TRUE | TRUE | TRUE | FALSE | TRUE | TRUE |  |  |  | 3.1.0 |  |
| 毫米波雷达 Radar | 毫米波雷达 | Radar |  | 是 | 是 |  |  |  |  | FALSE | TRUE | TRUE | TRUE | FALSE |  |  |  |  |  |  |  | TRUE | TRUE | TRUE | FALSE | TRUE | TRUE |  |  |  | 3.1.0 |  |
| 毫米波雷达 Radar | 4D毫米波雷达 | 4D Millimeter Wave Radar |  | 是 | 是 | 奔驰 3.4 | 3.6.0 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 定位传感器 GPS/GNSS/IMU | 定位传感器 | GPS/GNSS |  | 是 | 是 |  |  |  | 原本版本可以删除，GNSS和IMU两个分开使用 | TRUE | TRUE | TRUE | TRUE | TRUE |  |  |  |  |  |  |  | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE |  |  |  | 2.0.0 |  |
| 车载单元 OBU | OBU | OBU |  | 是 | 是 |  |  |  |  | TRUE | TRUE | TRUE | TRUE | TRUE |  |  |  |  |  |  |  | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE |  |  |  | 2.0.0 |  |
| 超声波雷达 Utrasonic | 超声波雷达 | Ultrasonic |  | 是 | 待分配 | 现代三期 3.6, 长城 3.6 | 3.7.0 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 激光雷达 Lidar | LivoxMid360 | LivoxMid360 |  | 待进基线 | 待进基线 | 劢勤 3.6 | 3.9.0 |  | 劢擎港机项目 | TRUE | TRUE | TRUE | TRUE | TRUE | 览沃 Livox-Mid360（固态） |  |  |  |  |  |  | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | TRUE |  |  | 3.6.0 |  |
| 激光雷达 Lidar | LivoxAvia | LivoxAvia |  | 待进基线 | 待进基线 | 劢勤 3.6 | 3.9.0 |  | 劢擎港机项目 | TRUE | TRUE | TRUE | TRUE | TRUE | 览沃 Livox-Avia（固态） |  |  |  |  |  |  | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | TRUE |  |  | 3.6.0 |  |
| 激光雷达 Lidar | LivoxHap | LivoxHap |  | 待进基线 | 待进基线 | 劢勤 3.6 | 3.9.0 |  | 劢擎港机项目 | TRUE | TRUE | TRUE | TRUE | TRUE | 览沃 Livox-Hap（固态） |  |  |  |  |  |  | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | TRUE |  |  | 3.6.0 |  |
| 定位传感器 GPS/GNSS/IMU | GNSS | GNSS |  | 待分配 | 待分配 | 劢勤 3.6 |  |  | 劢擎港机项目 | TRUE | TRUE | TRUE | TRUE | TRUE |  |  |  |  |  |  |  | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | TRUE |  |  | 3.6.0 |  |
| 定位传感器 GPS/GNSS/IMU | IMU | IMU |  | 待分配 | 待分配 | 劢勤 3.6 |  |  | 劢擎港机项目，原”定位传感器“ | TRUE | TRUE | TRUE | TRUE | TRUE |  |  |  |  |  |  |  | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | TRUE |  |  | 3.6.0 |  |
| 激光雷达 Lidar | F360° OS-1-128 | F360° OS-1-128 |  | 否 | 否 | 比亚迪HIL 3.6 |  |  | 比亚迪项目 |  |  |  |  |  | Ouster OS1-128 (自定义机械扫描) |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 激光雷达 Lidar | F180° LS-CH64W | F180° LS-CH64W |  | 是 | 是 | 五菱 |  |  | 五菱汽车 |  |  |  |  |  | 镭神（CH64）混合固态 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 激光雷达 Lidar | F120° HS-ATX | F120° HS-ATX |  | 待分配 | 待分配 | 长城 3.6, 博世 3.7 |  |  | 其他参数和F120 HS-AT128一致 |  |  |  |  |  | 禾赛 ATX（混合固态） |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 激光雷达 Lidar |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
