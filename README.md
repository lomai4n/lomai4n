<div align="center">

# 你好，我是 lomai4n 👋

**从 Web 平台到桌面与设备，把实际需求做成能用的工具。**

Building practical applications across web, desktop, media, and connected devices.

Java · Python · JavaScript / TypeScript · Swift · C++

[查看我的项目](https://github.com/lomai4n?tab=repositories) · [LomVideo](https://github.com/lomai4n/LomVideo) · [Brother Drop Print](https://github.com/lomai4n/brother-drop-print)

</div>

---

## 关于我

我围绕具体的使用场景开发软件：搭建业务管理平台、连接设备与数据、处理视频与视觉信息，也制作让日常操作更简单的桌面工具。

目前的项目实践覆盖 **全栈 Web 应用、物联网与设备集成、计算机视觉、视频自动化和原生应用**。从管理界面、后端服务到设备通信，我关注各个环节如何组成可使用、可维护的工作流。

我希望作品既能解决问题，也能让使用者看懂如何安装、如何使用，以及当前能力的边界。

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

## 技术与项目实践

| 方向 | 项目中用到的技术 | 实践内容 |
| --- | --- | --- |
| 后端与业务平台 | Java 17、Spring Boot、BladeX、MyBatis-Plus、Python / FastAPI | 业务接口、流程与状态管理、服务集成 |
| Web 前端 | Vue 3、JavaScript / TypeScript、Vite、Element Plus、ECharts | 管理后台、工作台、数据展示与交互 |
| 数据与消息 | PostgreSQL、MySQL、Redis、pgvector、MQTT、NATS | 数据持久化、缓存、向量检索与事件通信 |
| 计算机视觉 | Python、OpenCV、MediaPipe、ONNX Runtime | 姿态检测、视觉推理与识别服务 |
| 桌面与移动端 | Swift、CoreGraphics、Android / Java、uni-app、微信小程序 | 原生交互、文件处理与移动端界面 |
| 设备与协议 | C++20、CMake、TCP、PJL / SNMP、BLE、USB | 设备接入、状态查询与通信协议 |
| 视频与三维 | FFmpeg、React、Remotion、Three.js | 媒体处理、程序化视频与 Web 三维场景 |
| 自动化工具 | Python / asyncio、AstrBot、Docker Compose | 消息机器人、定时任务与服务编排 |
| 嵌入式原型 | ESP32、Arduino / C++、BLE、传感采集 | 固件、通信与采集原型，持续联调与验证 |

### 其他项目方向

除上面的公开仓库，我也在推进这些方向的项目：

- **业务平台与物联网**：连接后台管理、移动端、设备事件和数据展示。
- **视觉与多媒体**：姿态检测、识别服务、视频工作流与程序化动画。
- **交互与三维**：用 Three.js 制作可交互的三维场景与空间预览。
- **软硬件联调**：探索 ESP32 采集固件、Android 通信和 BLE / USB 链路；硬件原型仍需校准与实机验证。

## 开发关注点

- **从需求出发**：围绕可描述、可复现的问题组织功能与交互。
- **让工具容易使用**：完善安装入口、使用说明、错误提示和问题反馈。
- **让结果可以验证**：通过测试、演示和实机记录说明能力，区分已实现内容与后续计划。
- **尊重开源协作**：保留上游来源、许可证和第三方依赖说明。

## 交流与合作

欢迎交流 **Java / Python 后端、Web 与原生应用、物联网与设备集成、计算机视觉和视频工具**，也欢迎相关的 **开发机会、项目合作与开源贡献**。

想了解我的技术实践，可以从上面的项目、源码与实现记录开始；使用反馈和技术讨论，欢迎在对应仓库的 Issues 中交流。

> I build applications around real needs, from web services to desktop tools and connected devices. Open to development opportunities and open-source collaboration.
