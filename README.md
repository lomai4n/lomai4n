<div align="center">

# 你好，我是 lomai4n 👋

**把实际需求做成能用的工具。**

Building practical tools for media workflows, macOS, and device integration.

Python · Swift · C++ · Vue · TypeScript

[查看我的项目](https://github.com/lomai4n?tab=repositories) · [LomVideo](https://github.com/lomai4n/LomVideo) · [Brother Drop Print](https://github.com/lomai4n/brother-drop-print)

</div>

---

## 关于我

我围绕具体的使用场景开发软件：把重复的视频处理流程串起来，让文件拖一下就能打印，或为设备事件接入搭建清晰的接口。

目前的公开项目覆盖 **视频自动化、macOS 原生应用和设备接入**，涉及从交互界面、处理流程到底层协议的不同层面。我希望作品既能解决问题，也能让使用者看懂如何安装、如何使用，以及当前能力的边界。

## 项目作品

### 🎬 [LomVideo](https://github.com/lomai4n/LomVideo)

**本地自动视频生产工作台，将素材导入、语音转写、分集、混音与成片检查串成工作流。**

- 支持剪辑模板、批量处理，以及 MP4、SRT 和脚本 JSON 导出。
- 使用 Python、FFmpeg 与 Vue / TypeScript 构建处理流程和 Web 工作台，提供 Windows 联网安装入口。
- 在开源项目 NarratoAI 基础上改造，保留上游致谢与许可证；具体版本能力和验收范围见项目文档。

[项目介绍](https://github.com/lomai4n/LomVideo#readme) · [安装与版本](https://github.com/lomai4n/LomVideo/releases) · [反馈问题](https://github.com/lomai4n/LomVideo/issues)

### 🖨️ [Brother Drop Print](https://github.com/lomai4n/brother-drop-print)

**面向 macOS 的原生菜单栏打印工具，把 PDF 或图片拖到浮窗，即可发送到打印机。**

- 文件在本机排版、转换，通过 TCP 9100 发送，无需安装系统打印驱动。
- 涉及 Swift、CoreGraphics、C++ 与 brlaser，包含多合一、手动双面、预设和打印机状态查询。
- 当前为实验性项目，已在 DCP-1618W 上确认部分功能；其他机型与部分打印选项仍待实机验证。

[项目介绍](https://github.com/lomai4n/brother-drop-print#readme) · [实现与研究记录](https://github.com/lomai4n/brother-drop-print/blob/main/docs/architecture-v1.1.md) · [反馈问题](https://github.com/lomai4n/brother-drop-print/issues)

### 🔌 [hik-device-bridge](https://github.com/lomai4n/hik-device-bridge)

**面向设备事件接入的非官方 C++20 库与命令行工具，目标平台为 Linux。**

- 探索设备会话生命周期、报警订阅接口、异步事件队列与元数据处理。
- 使用 CMake 构建，并通过离线合成数据验证通用层、退出流程和错误处理。
- 当前仅提供模拟预发布；真实厂商 SDK 接入被禁用，尚未完成 Linux 与实机验收。

[项目介绍](https://github.com/lomai4n/hik-device-bridge#readme) · [验证记录](https://github.com/lomai4n/hik-device-bridge/blob/main/docs/VALIDATION.md) · [反馈问题](https://github.com/lomai4n/hik-device-bridge/issues)

## 项目中的技术实践

| 方向 | 涉及的技术与内容 |
| --- | --- |
| 视频与自动化 | Python、FFmpeg、语音转写、批量任务与媒体导出 |
| Web 工作台 | Vue 3、TypeScript、Vite、工作流界面 |
| 原生桌面应用 | Swift、CoreGraphics、拖放交互、打印队列 |
| 设备与协议 | C++20、CMake、TCP、PJL / SNMP、事件处理 |

## 开发关注点

- **从需求出发**：围绕可描述、可复现的问题组织功能与交互。
- **让工具容易使用**：完善安装入口、使用说明、错误提示和问题反馈。
- **让结果可以验证**：通过测试、演示和实机记录说明能力，区分已实现内容与后续计划。
- **尊重开源协作**：保留上游来源、许可证和第三方依赖说明。

## 交流与合作

欢迎交流视频工作流、macOS 工具、设备接入和日常自动化，也欢迎相关的 **开发机会、项目合作与开源贡献**。

想了解我的技术实践，可以从上面的项目、源码与实现记录开始；使用反馈和技术讨论，欢迎在对应仓库的 Issues 中交流。

> I build tools around real needs. Open to technical discussions, development opportunities, and open-source collaboration.
