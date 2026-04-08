# PCILeech FPGA Custom Development Guide

## Overview 

This project is a customized development implementation based on PCILeech FPGA, providing hardware-accelerated memory access and Direct Memory Access (DMA) capabilities. Through FPGA hardware implementation, it enables high-performance memory operations and supports various application scenarios including digital forensics, system debugging, and security research. 

## Features
 
- 🚀 **Hardware-Accelerated Memory Access** - High-speed DMA operations using FPGA
- 📈 **PCIe Device Initialization Flowchart** - Complete device initialization process analysis
- 🕵️ **Simulating Shadow Space of Acquisition Devices** - Simulation techniques for device shadow space
- 🛠️ **How to Generate Projects in Vivado** - Detailed steps for Vivado project creation
- ⚙️ **Opening Top Module to Modify Parameters** - Top-level module parameter configuration methods
- 🔍 **Simulating CORETOP (Configuration Space) Parameters and Pointers** - Configuration space simulation basics
- 🔎 **Advanced Parameter Simulation for Core Top Configuration Space** - Advanced configuration space simulation
- 📦 **Modifying Allocatable Maximum Load** - Load capacity adjustment guide
- 🖊️ **Write Mask (Writemask)** - Detailed explanation of write mask functionality
- ✅ **Adding RW1C Mask to Projects** - RW1C mask implementation methods
- 🗺️ **Configuring Correct BAR Mapping Size and Base Address Transfer** - BAR mapping configuration
- 📊 **Simulating Memory Data (TLP) in BAR** - BAR memory data simulation
- ➕ **TLP Simulation: Adding More BAR Response Modules** - Multi-BAR response module expansion
- 💾 **How to Write TLP for Special Devices (Dynamic Memory)** - Dynamic memory TLP writing techniques
- 🚫 **Zero 4K Space Memory Simulation** - Zero space memory simulation methods
- 🐧 **Linux System MMIOTrace Memory Mapping Logs** - Linux memory mapping tracking
- 🖥️ **LINUX+QEMU Virtual Machine Tracing MMIO Operations in Windows Systems** - Cross-system MMIO tracking
- 🔄 **Advanced TLP: Asymmetric Memory Processing** - Asymmetric memory processing techniques
- ⚡ **Interrupt Operations (Making Devices Active)** - Interrupt mechanism configuration
- 🔒 **Locking Board ID (DNA)** - Device identity locking
- 🎮 **Experience Module** - Functional experience module
- 📤 **Exporting Firmware** - Firmware export methods

## Detailed Documentation

For complete development guide:

[📚[Custom firmware guide](https://newworldproject.feishu.cn/docx/PQ75dtZiNomx9zxXED1caAZxnRc)]

[💬[Discord](https://particledma.top/)]

For translation the page has it built-in, just create lark account and at the top there are 3 dots press that and translate it to your prepared language instead of translating it word by word.

## Contributing

We welcome community contributions! Please read our contribution guidelines and submit Pull Requests.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Technical Support

For questions or suggestions, please contact us through:
- Submitting Issues
- Project discussion board
- Email support

---

**Note**: Please comply with relevant laws and regulations when using this tool. Use only for authorized testing and research purposes.

---

# PCILeech FPGA 自定义开发指南

## 概述

本项目是基于PCILeech FPGA的定制化开发实现，提供硬件加速的内存访问和直接内存访问（DMA）功能。通过FPGA硬件实现，能够进行高性能内存操作，支持包括数字取证、系统调试和安全研究在内的多种应用场景。

## 功能特性

- 🚀 **硬件加速内存访问** - 使用FPGA实现高速DMA操作
- 📈 **PCIE 设备初始化流程图** - 完整的设备初始化流程解析
- 🕵️ **仿真采集设备的影子空间** - 设备影子空间的仿真技术
- 🛠️ **如何 Vivado 中生成项目** - Vivado项目创建详细步骤
- ⚙️ **打开顶部模块修改参数** - 顶层模块参数配置方法
- 🔍 **仿真 CORETOP（配置空间）参数以及指针** - 配置空间仿真基础
- 🔎 **进一步的 Core Top 配置空间 的参数仿真** - 高级配置空间仿真
- 📦 **修改可分配最大负载** - 负载容量调整指南
- 🖊️ **写掩码 Writemask** - 写掩码功能详解
- ✅ **为项目添加 RW1C 掩码** - RW1C掩码实现方法
- 🗺️ **配置正确的Bar 映射大小，以及基地址传递** - BAR映射配置
- 📊 **仿真 BAR 内内存数据（TLP）** - BAR内存数据仿真
- ➕ **TLP 仿真之添加更多的 BAR 回应模块** - 多BAR回应模块扩展
- 💾 **特殊设备（动态内存）TLP 如何写入？** - 动态内存TLP写入技术
- 🚫 **Zero 4K 空间内存仿真** - 零空间内存仿真方法
- 🐧 **LINUX 系统 MMIOTrace 内存映射日志** - Linux内存映射跟踪
- 🖥️ **LINUX+QEMU 虚拟机 Trace Windows 系统下的 MMIO 操作** - 跨系统MMIO跟踪
- 🔄 **TLP进阶之非对称内存处理** - 非对称内存处理技术
- ⚡ **中断操作（使设备活跃**） - 中断机制配置
- 🔒 **锁板子 ID（DNA)** - 设备身份锁定
- 🎮 **体验模块** - 功能体验模块
- 📤 **导出固件** - 固件导出方法

## 详细文档

完整开发指南：
[📚[自定义固件指南](https://newworldproject.feishu.cn/docx/PQ75dtZiNomx9zxXED1caAZxnRc)]

[💬[Discord](https://discord.gg/GvCKVegSbr)]

页面内置翻译功能，只需创建飞书账号，点击顶部三个点即可将文档翻译成您需要的语言，无需逐字翻译。

## 贡献指南

我们欢迎社区贡献！请阅读我们的贡献指南并提交Pull Request。

## 许可证

本项目采用MIT许可证 - 详见LICENSE文件。

## 技术支持

如有问题或建议，请通过以下方式联系：
- 提交Issue
- 项目讨论区
- 电子邮件支持

---

**注意**：使用本工具请遵守相关法律法规，仅用于授权的测试和研究目的。
