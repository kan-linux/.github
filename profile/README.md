# Kan Linux

Purity, Source-Built & Agentic Linux

*See through the delusions, return to simplicity*

**勘破遮蔽，回归本真**

---

## About

**Kan Linux** is a minimalist and pure modern Wayland desktop distribution\. The name **Kan** derives from *Instructions for Practical Living* by Wang Yangming, representing the philosophy of breaking through technical obscurations and returning to the system’s original simplicity\.

This project thoroughly abandons the bloated legacy desktop stack including GTK, Cairo and Pango, eliminating decades of accumulated technical debt on traditional Linux desktops\. Based on lightweight musl libc \+ busybox foundation, it adopts a modern Qt \+ Hyprland Wayland architecture, keeping the system idle\-quiet and responsive on demand\.

## Design Philosophy

- **Purity** — Remove redundant dependencies and legacy rendering layers (similar to the core principle of ggml/llama.cpp)

- **Minimalism** — Lightweight musl base with zero useless overhead

- **Modernity** — Pure Wayland\-native desktop, drop outdated X11 stack

- **Agent\-First \& Agent\-Friendly** — designed for AI agent autonomous operation, auto\-compilation, component deployment and intelligent troubleshooting

- **llama.cpp-First** — Built-in native llama.cpp edge inference engine for local AI deployment
  
- **Source-Built** — The entire OS and all components are built from source, enabling AI agents to intelligently build, deploy and repair the system autonomously

---

## Projects

- [ggml-hexagon](https://github.com/kan-linux/ggml-hexagon/discussions/84):Original FastRPC-based ggml-hexagon, Alternative llama.cpp backend for Qualcomm Hexagon NPU (Android / WoS(Windows on Snapdragon) / Linux)
  
- kan-linux: Built an Agent-First and Agent-Friendly modern Linux desktop from scratch， TBD

---

## Roadmap

Kan Linux is progressively ported and verified across multiple hardware and virtual platforms:

- QEMU virtual machine
- x86-64 desktop devices
- x86-64 laptop devices
- aarch64 laptop devices(Snapdraon on Linux)

---

## Acknowledgements
- Inspired by [Omarchy Linux](https://github.com/omacom/omarchy)
- Thanks to [LFS (Linux From Scratch)](https://www.linuxfromscratch.org/)
- Thanks to [Pop!\_OS ISO](https://github.com/pop-os/iso)
- Thanks to [try-omarchy-linux](https://github.com/zhouwg/try-omarchy-linux)
- Thanks to the entire Linux community(various tech stacks)
- Thanks to [llama.cpp](https://github.com/ggml-org/llama.cpp)

---

## License
This project is licensed under the MIT License.

You are welcome to fork this repository and submit pull requests.
If you reuse the code or materials from this project, **please retain attribution to this source**.

---


## 简介

**Kan（勘）Linux** 是一款极简、纯净、现代化的 Wayland 桌面 Linux 发行版。

名称取自王阳明《传习录》：**“此处能勘得破，方是简易透彻功夫。”**

项目以「勘破遮蔽、去芜存真」为核心设计理念，彻底剥离传统 Linux 桌面老旧臃肿的 GTK 图形体系与历史技术债。以 musl \+ busybox 构建极致精简的底层基座，搭配 Qt \+ Hyprland 现代化 Wayland 桌面栈，实现系统**寂然不动，感而遂通**的运行状态，闲时沉静无冗余，响应交互通透高效。

## 核心设计理念

- **纯粹性** — 剔除冗余依赖与老旧渲染层级，摒弃无效技术负担

- **极简性** — 轻量化底层架构，无多余系统开销

- **现代化** — 纯 Wayland 原生架构，彻底舍弃过时 X11 体系

- **Agent First \& Agent Friendly** — 面向智能代理设计，支持 AI Agent 自主编译部署、组件安装、系统自查与问题修复

- **llama.cpp 优先** — 内置原生 llama.cpp 端侧推理引擎，原生支持本地 AI 部署与端侧智能计算
  
- **源码构建** — 整套系统及所有组件均支持从源代码编译构建，适配 AI Agent 智能编译、自动部署与智能修复

---

## 项目

- [ggml-hexagon](https://github.com/kan-linux/ggml-hexagon):Original FastRPC-based ggml-hexagon, Alternative llama.cpp backend for Qualcomm Hexagon NPU (Android / WoS(Windows on Snapdragon) / Linux)
  
- kan-linux: 从源代码构建Agent优先&Agent友好的现代桌面Linux, 敬请期待

---

## 路线图

Kan Linux 逐步适配虚拟化环境与主流硬件平台，覆盖日常开发与桌面使用场景：

- QEMU 虚拟机环境
- x86-64 台式机
- x86-64 笔记本
- aarch64 笔记本(Snapdraon on Linux)

---

## 致谢
- 感谢 [Omarchy Linux](https://github.com/omacom/omarchy) 带来的启发
- 感谢 [LFS (Linux From Scratch)](https://www.linuxfromscratch.org/)项目
- 感谢 [Pop!\_OS ISO](https://github.com/pop-os/iso)
- 感谢 [try-omarchy-linux](https://github.com/zhouwg/try-omarchy-linux)
- 感谢全体 Linux 社区（各种复杂的技术栈）
- 感谢 [llama.cpp](https://github.com/ggml-org/llama.cpp)

---

## 许可证
本项目采用 MIT 许可证。

欢迎 Fork 本仓库并提交 Pull Request。
若复用本项目的代码或相关资料，**请注明来源**。
