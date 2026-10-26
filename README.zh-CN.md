<div align="center">

# 改进版 FT 叛逆者飞翼

**一张 KT 板就能切完、大约 30 分钟拼好的飞翼，<br>
带激光切割的木质机舱，可以装 FPV 设备，电机前拉、尾推都行。**

基于 [Flite Test Versa Wing（叛逆者飞翼）](https://www.flitetest.com/articles/ft-versa-wing-build) 改进。

[![图纸](https://img.shields.io/badge/plans-DXF-e5484d)](plans/)
[![板材](https://img.shields.io/badge/sheet-1200%20%C3%97%20900%20mm-2f81f7)](#基本参数)
[![许可证](https://img.shields.io/badge/license-CC%20BY--NC--SA%204.0-lightgrey)](LICENSE)

[English](README.md) · **简体中文**

### [⬇ 下载切割图纸（.zip）](https://github.com/chchaoo/Modified-FTVersaWing/releases/latest/download/versa-wing-plans.zip)

<img src="docs/images/photo-1.jpg" width="49%" alt="成品飞翼，尾推电机"> <img src="docs/images/photo-2.jpg" width="49%" alt="俯视图，中间是木质机舱，前面是备用的机舱侧板">

</div>

## 基本参数

| | |
|---|---|
| **机身** | 5 mm 厚 KT 板（冷板），一张 1200 × 900 mm |
| **机舱** | 2 mm 厚木板，激光切割 |
| **板材成本** | 约 5 元 |
| **拼装时间** | 约 30 分钟 |
| **电机布局** | 前拉 / 尾推 / 前拉 + 尾推 任选 |
| **FPV** | 预留 M2.5、30.5 × 30.5 mm 穿越机通用尺寸的图传安装孔位，以及摄像头安装孔位 |
| **试过的最重配置** | 尾推 2317 电机 1400 KV，8060 双叶桨，4S2P 3300 mAh 电池配平 |

## 切割图纸

| 文件 | 内容 |
|---|---|
| [`plans/versa-wing-foam-v2-1200x900.dxf`](plans/versa-wing-foam-v2-1200x900.dxf) | 全部 KT 板零件，排版在 1200 × 900 mm 的板上（原文件名：v2切割 x1 (1200x900).dxf） |
| [`plans/versa-wing-wood-bay.dxf`](plans/versa-wing-wood-bay.dxf) | 木质机舱，2 mm 木板（原文件名：木质结构.dxf） |

<p align="center"><img src="docs/images/plan-foam.svg" alt="KT 板排版" width="860"></p>

> [!IMPORTANT]
> **红线：切一半深度**（折弯线、舵面铰链）。**黑线和蓝线：切透。**

<p align="center"><img src="docs/images/plan-wood.svg" alt="木质机舱零件" width="560"></p>

图纸是以毫米为单位的普通 DXF 文件，激光切割软件、LightBurn、LibreCAD、AutoCAD 都能直接打开。没有激光切割机的话，按 1:1 打印出来手工切也可以。

## 制作要点

- 电机可以装在前面（前拉）、后面（尾推），或者前后都装。
- 木质机舱已经预留了 30.5 × 30.5 mm 图传的 M2.5 安装孔和摄像头安装孔。
- GPS 和图传天线需要自己在飞机**上表面**开洞安装。
- **只要重心能配平**，电机和桨叶的尺寸可以任选，靠前后移动电池来调整重心。

## 需要准备

**工具：**（激光切割机）、热熔胶枪、裁纸刀、钢尺、钳子。

**材料：** 5 mm 厚 KT 板冷板、2 mm 厚木板、舵角、金属调节器、铁丝拉杆、魔术贴、纤维胶带、透明或有色胶带、泡沫胶带、502 胶、魔术贴扎带。

**电子设备：** 电机、桨、电调、电池、舵机 × 2、遥控器、接收机。做 FPV 的话还需要：飞控、图传、摄像头、图传接收设备。

## 致谢

原版 FT Versa Wing 由 [Flite Test](https://www.flitetest.com/articles/ft-versa-wing-build) 设计。本仓库是在它基础上修改的排版，以及新设计的木质机舱。

## 其他设计

- [RCPlane-SU27](https://github.com/chchaoo/RCPlane-SU27)：5 mm KT 板苏-27，有涵道版和螺旋桨版，大约 15 分钟拼好。

## 许可证

[CC BY-NC-SA 4.0](LICENSE)：可以自由制作、修改和分享，需要署名、不能商用，改版也要用同样的协议。原版 Versa Wing 的设计版权属于 Flite Test，本许可证只覆盖本仓库中的修改部分和文件。
