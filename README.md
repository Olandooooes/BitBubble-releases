# BitBubble 官方发布

## 项目展示 / Project overview

**BitBubble 是一个从桌面交互延伸到跨设备社交的产品。** 它把“陪伴”落实为可操作的行为：宠物出发、到访朋友桌面、交换纸条、互动后返回，并留下回忆。

### 实现重点

- **桌面客户端**：Electron 透明置顶窗口、鼠标穿透、拖动与原生菜单，兼顾桌宠展示和管理界面。
- **实时交互**：WebSocket 连接与重连，串联两台设备上的出发、到访与返回状态。
- **交付**：Windows 安装包、版本归档、文件校验和公开反馈入口。源码保持私有。
- **工程关注点**：桌宠窗口与管理界面的状态一致性、断线后的串门恢复、安装包与开发环境的行为差异。

### 建议体验路径

1. 从官网或 Release 安装 Windows 版本，创建并调整桌宠。
2. 使用两台电脑添加好友，完成一次出发、到访、纸条回复和返回。
3. 观察两端状态与回忆记录；遇到异常时记录版本和复现步骤。

这是供体验者使用的演示路径，不代表本次文档更新重新完成了双设备测试。公开正式版以 Release 为准；macOS 尚无公开正式版。

**English:** BitBubble is a Windows social desktop pet built with Electron. Its core experience connects desktop interaction with cross-device visits, messages and shared memories. This public repository provides releases and feedback; the application source remains private.


BitBubble（比特泡泡）是一款 Windows 轻社交桌宠。桌宠可以陪你摸鱼、拜访好友、携带纸条、一起玩轻量小游戏，并把真实互动保存成回忆卡。

> 本仓库是 BitBubble 的官方发布与反馈仓库，仅提供安装包、校验文件和版本记录。BitBubble 是闭源商业软件，源代码保存在私有仓库中，不在此公开。

## 下载与版本

截至 2026-09-20，最新正式 Release 为 [v0.16.29](https://github.com/Olandooooes/BitBubble-releases/releases/tag/v0.16.29)。请从 [最新 Release](https://github.com/Olandooooes/BitBubble-releases/releases/latest) 获取当前 Windows 安装包与对应校验文件。下面保留此前 v0.15.2 的下载及校验记录，方便追溯。

### BitBubble v0.15.2

[从官方下载域名下载安装包](https://download.xingo.fun/BitBubble-Setup-0.15.2.exe) · [查看 GitHub Release](https://github.com/Olandooooes/BitBubble-releases/releases/tag/v0.15.2) · [访问产品官网](https://bitbubble.xingo.fun/)

- 系统：Windows 10 / 11（x64）
- 安装包：`BitBubble-Setup-0.15.2.exe`
- 文件大小：97,851,666 bytes
- SHA-256：`59cbd13b799f8b5215158fd6f1117067d9b9519a61818bc4dd16fc88ee07c1b8`

所有历史版本和更新说明均可在 [Releases](https://github.com/Olandooooes/BitBubble-releases/releases) 中查看。

## 当前功能

- 自定义桌宠形象、名称、口头禅、大小和行为
- 邀请码、好友申请与跨电脑好友串门
- 携带纸条、快速回复、回信与双向道别
- 钓鱼、种花、会议涂鸦、纸团投篮和桌面寻宝
- 3–5 人摸鱼小队与好友接力
- 摸鱼日报、PNG 战报卡、四格漫画和关系称号
- 老板键、下班倒计时、免打扰和低资源模式
- 回忆卡与真实双宠互动记录

## 安装与安全

1. 仅从本仓库 Release 或 [BitBubble 官网](https://bitbubble.xingo.fun/) 下载安装包。
2. 下载后可用 SHA-256 校验文件完整性。
3. 当前安装包尚未购买 Windows 商业代码签名证书，首次运行时 Windows 可能显示“未知发布者”。

PowerShell 校验命令：

```powershell
Get-FileHash .\BitBubble-Setup-0.15.2.exe -Algorithm SHA256
```

## 反馈问题

如果遇到 Bug 或有功能建议，请在 [Issues](https://github.com/Olandooooes/BitBubble-releases/issues) 中提交，并尽量附上：

- BitBubble 版本号
- Windows 版本
- 问题复现步骤
- 截图或错误信息（请先移除隐私内容）

## 商业与版权说明

BitBubble 为闭源商业软件。公开 GitHub 地址不代表源代码开源，也不授予复制、修改、反编译、重新打包或冒充官方发行的许可。

安装和使用软件即表示你同意随安装包提供的相关许可与服务条款。
