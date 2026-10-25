# 10 亿 Token、1000+ 小时？小薅薅 0.2.49 六端桌面版来了

![小薅薅 0.2.49 宇宙涡流主视觉](assets/xiaohaoh-hero-0.2.49.png)

> **标题里的“10 亿 Token”和“1000+ 小时”是夸张宣传修辞，不是实际账单或工时统计。** 真实发行信息：macOS ARM64、macOS Intel x64、Windows 11 x64，各有完整版和简洁版，共六个构建。

## 把 Agent 放进自己的桌面

小薅薅是一款独立运行的桌面 AI Agent。它把对话、记忆、认知节点图、心跳和行动日志放进一个工作台；完整版和简洁版界面各自独立，技能、插件与核心能力按同一版本同步。

![小薅薅 0.2.49 功能亮点图](assets/xiaohaoh-highlights-0.2.49.svg)

### 这一版的亮点

- **完整与简洁两种界面**：独立窗口和本地数据空间，使用同一版本的功能与扩展。
- **桌面认知工作台**：对话、长期记忆、认知节点关系、Agent 心跳和行动日志集中查看。
- **独立扩展运行**：预置技能和可选 MCP 插件由小薅薅管理，不要求另装 Hermes、Harness 或 Python 主机。外部模型或服务仍需按需配置。
- **连接自己的模型服务**：设置兼容的模型服务和 API Key；对话请求会发送给所选服务商。聊天和记忆保存在本机。
- **macOS 本地语音识别**：macOS 包预置 SenseVoice 模型；该模型附带独立协议，限参考与学习用途，并随包提供来源及许可说明。
- **Windows 11 便携运行**：下载 EXE 后直接启动，无需安装向导。Windows 包不包含 macOS 专用 SenseVoice 模型。

## 六个版本

| 平台 | 版本 | 下载 | 文件大小 |
|---|---|---|---:|
| macOS ARM64 | 完整版 | [完整版](https://github.com/tomlen045/xiaohaoh-agent/releases/download/v0.2.49/XiaoHaoHao-full-0.2.49-macOS-arm64.zip) | 307 MB |
| macOS ARM64 | 简洁版 | [简洁版](https://github.com/tomlen045/xiaohaoh-agent/releases/download/v0.2.49/XiaoHaoHao-simple-0.2.49-macOS-arm64.zip) | 307 MB |
| macOS Intel x64 | 完整版 | [完整版](https://github.com/tomlen045/xiaohaoh-agent/releases/download/v0.2.49/XiaoHaoHao-full-0.2.49-macOS-x64.zip) | 311 MB |
| macOS Intel x64 | 简洁版 | [简洁版](https://github.com/tomlen045/xiaohaoh-agent/releases/download/v0.2.49/XiaoHaoHao-simple-0.2.49-macOS-x64.zip) | 311 MB |
| Windows 11 x64 | 完整版 | [完整版](https://github.com/tomlen045/xiaohaoh-agent/releases/download/v0.2.49/XiaoHaoHao-full-0.2.49-Windows-x64-portable.exe) | 121 MB |
| Windows 11 x64 | 简洁版 | [简洁版](https://github.com/tomlen045/xiaohaoh-agent/releases/download/v0.2.49/XiaoHaoHao-simple-0.2.49-Windows-x64-portable.exe) | 121 MB |

[下载全部构建的 SHA-256 校验清单](assets/SHA256SUMS-0.2.49.txt)。

macOS 下载为 ZIP；Windows 下载为 x64 便携 EXE。每个构建版本为 0.2.49。完整版和简洁版各自保存应用数据。

## 验收记录

- macOS ARM64：发行包及校验清单已核对。
- macOS Intel x64：两个 ZIP 的完整性、主程序架构和版本元数据已核对。
- Windows 11 x64：两个便携程序在 Windows 11 环境启动，主窗口响应正常；构建前运行时检查为 8 项通过、0 项失败。
- 六个发行文件均重新计算 SHA-256；每个文件均低于 GitHub Release 单文件 2 GiB 限制。
- macOS 应用未签名或公证，Windows 程序未做 Authenticode 签名。首次打开时，Gatekeeper 或 SmartScreen 可能显示安全提示。
- Windows 版本需配置模型服务/API Key 后进行自然语言对话。请勿把密钥放入公开截图或文件。

## English

[Read the English launch article](en.md).

## 作品主视觉与功能图

- [主视觉 PNG](assets/xiaohaoh-hero-0.2.49.png)
- [功能亮点 SVG](assets/xiaohaoh-highlights-0.2.49.svg)
