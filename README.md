# os-porting-tutorial

# 2025 OS 移植训练营专业阶段作业

### 作业 1: ArceOS 环境搭建与基本 QEMU 运行

**目标**：熟悉 ArceOS 构建环境，运行内核在 QEMU 上，理解模块化结构和独立 crates（如 axhal）。

**说明**：效果为内核在 QEMU 中启动并输出基本消息，展示 Unikernel 启动过程。

**预期输出**：QEMU 控制台日志，显示 "Hello, world!" 或类似启动消息。

### 作业 2: QEMU 平台适配与 UART 测试

**目标**：移植 ArceOS 到 QEMU virt 平台，测试 UART 输出，学习 HAL 抽象（axhal crate）和设备配置。

**说明**：效果为在 QEMU 中通过串口输出自定义消息，验证 HAL 和设备交互。

**预期输出**：串口日志，显示自定义消息如 "Test UART"。

### 作业 3: 简单模块扩展与网络测试

**目标**：扩展内核，使用独立 crates（如 axalloc）添加网络支持，测试基本输出。

**说明**：效果为在 QEMU 中加载网络模块并输出初始化消息，展示模块扩展能力。

**预期输出**：日志，显示网络模块加载如 "Net init"。

## 提交要求

* 运行的效果截图与必要的日志说明
* 代码仓库地址

作业提交地址：https://github.com/kunyuanxu-star/os-porting-tutorial/issues/1