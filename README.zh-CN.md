# WhatsApp 翻译助手（Mac）

用中文、英文或西语阅读和回复 WhatsApp 消息。**v0.3.2 · 构建 302**。

[English](README.md) · [下载安装包](https://github.com/Ethan8860/whatsapp-translator-mac/releases/download/v0.3.2/WhatsApp-Translator-0.3.2-Mac.dmg) · [同事分享 ZIP](https://github.com/Ethan8860/whatsapp-translator-mac/releases/download/v0.3.2/WhatsApp-Translator-0.3.2-Mac-Package.zip)

## 三种语言设置

- 界面语言：中文、English、Español，仅影响菜单和提示。
- 阅读与输入语言：收到的消息译成此语言，你也用此语言写回复。
- 回复目标语言：顶部 中文 / EN / ES 切换；与输入语言相同时不转换草稿。

在 WhatsApp 原输入框写完，停笔 5 秒自动翻译，检查后由你手动发送。助手不会自动发送。撤销恢复原稿，未暂停时停笔 5 秒再次翻译；措辞时可暂停。

## 安装与更新

仅支持 Apple Silicon Mac、macOS 26 或更新系统，以及原生 WhatsApp 客户端。拖拽安装到 Applications 后，按引导开启辅助功能、准备所选语言包，可选择登录启动。无需 API 密钥、Codex 或 Xcode。

菜单“检查更新”连接公开 GitHub 发行信息；发现新版后可选择“下载并更新”，助手会校验安装包并重启。从 v0.3.0 升级时，请先退出助手，将新版替换到原应用路径，保留设置和自动启动。签名变化可能要求刷新系统授权。

本软件尚无 Apple Developer ID 签名及公证，公司策略或 macOS 可能阻止运行，请联系 IT 核验，不要关闭系统安全保护。

## 范围与限制

中、英、西语六个方向已在应用环境测试，英文↔西语输入框转换、撤销、暂停和恢复已实测；机器翻译仍可能有误。原生实测采用 WhatsApp 2.26.46.15 中文界面，英／西语 WhatsApp 界面的消息解析仍待实际验收。

翻译在本机完成，聊天、导入记录和译文只保存在运行内存；语言包下载连接 Apple，检查更新及下载安装包连接 GitHub。实时阅读仅覆盖已加载文本，可滚动或导入历史文本；不翻译图片、GIF、音频及附件内容。

其他语言、Windows、Intel Mac、网页端、手机及其他聊天客户端尚不支持。

[完整安装与使用说明](使用说明.txt)。此仓库仅分发安装包和文档，不包含源码、聊天或用户设置。独立项目，非 WhatsApp／Meta 官方产品。
