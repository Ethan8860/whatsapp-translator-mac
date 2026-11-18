# WhatsApp 中英西语翻译助手（Mac）

**看懂英语和西班牙语消息，用中文回复。**

配合 Mac 版 WhatsApp 使用：对方的英语／西语消息会显示中文译文；你直接在 WhatsApp 输入中文，停笔 5 秒后自动转成英文或西语，检查后自己发送。

使用 Apple 本地翻译，无需 API 密钥，没有按次翻译费用。

## 下载与安装

**[下载 Mac 安装包](https://github.com/Ethan8860/whatsapp-translator-mac/releases/download/v0.2.12/WhatsApp-Translator-0.2.12-Mac.dmg)** · [完整安装包与使用说明 ZIP](https://github.com/Ethan8860/whatsapp-translator-mac/releases/download/v0.2.12/WhatsApp-Translator-0.2.12-Mac-Package.zip) · [所有版本](https://github.com/Ethan8860/whatsapp-translator-mac/releases)

当前版本：**v0.2.12（构建 212）**。

适用于 **M 系列芯片的 Mac、macOS 26 或更新版本、WhatsApp 桌面客户端**。暂不支持 Intel Mac、Windows、手机或 WhatsApp 网页版。

1. 打开下载的 DMG，将 **WhatsApp Bilingual.app** 拖到 **Applications（应用程序）**。这是应用在 Mac 上的名称。
2. 从“应用程序”启动助手，按提示在系统设置中开启它的**辅助功能权限**。
3. 按提示准备 Apple 中文、英文和西语翻译语言包；已安装的语言包无需重复下载。
4. 打开 WhatsApp 聊天，助手会在旁边显示译文。建议开启“登录 Mac 时自动启动”。

**首次打开被 macOS 拦截？** 当前应用尚未获得 Apple Developer ID 签名与公证，部分 Mac 或公司策略可能阻止运行。请由 IT 核验，或等待完成签名的版本；无需关闭系统安全保护。

[阅读完整使用说明与常见问题](使用说明.txt)

## 怎么使用

| 你想做什么 | 操作 |
|---|---|
| 看懂对方消息 | 打开聊天，旁边查看中文译文；可开启“原文对照” |
| 用中文回复 | 顶部选择“英文”或“西语”，在 WhatsApp 输入中文，停笔 5 秒后转换 |
| 还在措辞，不想转换 | 点“暂停助手”；准备好后再继续 |
| 改回刚才的中文 | 点“撤销翻译”；未暂停时，停笔 5 秒后会重新转换 |
| 发出回复 | 检查 WhatsApp 输入框中的译文，然后手动发送；助手不会自动发送 |
| 查看更早记录 | 在 WhatsApp 中滚动加载消息，或将导出的聊天文本导入助手 |
| 暂时收起译文 | 点收起按钮；助手随 WhatsApp 贴边，切换到其他应用时隐藏 |

## 免费、本地处理

- 翻译由 Apple 本机语言模型完成；首次下载语言包需要网络。
- 聊天内容和译文只在本次运行的内存中处理，不上传到本项目服务器。
- 无需 Codex、Xcode 或付费翻译账号。
- GitHub 下载与语言包下载仍会连接各自服务。

## 使用前了解

- 机器翻译可能误判语气、专有名词或短句；金额、日期和重要约定请核对原文。
- 实时阅读处理 WhatsApp 当前已加载的文字，不会一次读取全部聊天历史。
- 图片、GIF、语音及附件中的内容暂不翻译。
- 当前更新方式为从本页下载新版、退出助手后替换应用。应用内一键更新尚未提供。

本项目为独立开发工具，与 WhatsApp／Meta 无隶属关系。本仓库提供安装包和说明，不包含源码；公开下载不等于源码开源。
