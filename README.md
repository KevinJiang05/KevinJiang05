<h1 align="center">Kevin Jiang</h1>

<p align="center">水下机器人 · 计算机视觉 · 地面站开发</p>

## 关于我

我主要做水下机器人相关的软件，工作内容横跨相机、视觉处理、地面站和实际设备联调。

比起做一个只能演示的原型，我更关心它在现场是否稳定、问题是否容易定位，以及修改之后能不能复现。

## 最近在做

- 多相机接入、标定、投影与环视拼接
- QGroundControl 定制和低延迟视频链路
- 工程工具、运行状态监测与硬件联调

## 项目

### [DeepShark View Studio](https://github.com/KevinJiang05/DeepSharkViewStudio)

一个独立的多相机开发工具，包含实时预览、相机标定、投影实验、环视拼接、运行诊断和 QGC 视频输出。主要使用 Python、PySide6 和 OpenCV。

### [QGC for GRobot](https://github.com/KevinJiang05/QGC_for_GRobot)

面向 DeepShark 水下机器人的 QGroundControl 定制版本，主要涉及 C++、Qt/QML 和 MAVLink。

## 常用技术

Python · C++ · PySide6 · Qt/QML · OpenCV · GitHub Actions

我习惯先把运行状态和边界条件弄清楚，再逐步解决问题；涉及硬件的改动，尽量留下可复现的测试和记录。
