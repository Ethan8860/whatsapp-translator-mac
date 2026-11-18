# WhatsApp 双语助手 · Mac

非官方的 macOS WhatsApp 翻译助手：英语／西语消息译成中文；在 WhatsApp 原输入框写中文，停笔 5 秒后译成所选英文或西语，由你检查后手动发送。

本仓库仅发布安装包、校验文件和使用说明，不包含应用源码、聊天记录或用户配置。

## 下载

进入本仓库的 [Releases](https://github.com/Ethan8860/whatsapp-translator-releases/releases) 下载最新预览版：
- `WhatsApp-Bilingual-版本号-Mac-arm64-beta.dmg`：标准拖拽安装包。
- `WhatsApp-Bilingual-版本号-Colleague-Package.zip`：安装包、使用说明和校验文件，适合转发同事。
- `SHA256SUMS.txt`：下载文件的 SHA-256 校验值。

## 要求与安装

Apple Silicon（M 系列）Mac，macOS 26 或更新版本。暂不支持 Intel Mac、Windows 或 WhatsApp 网页版。

1. 打开 DMG，将应用拖到 Applications，再从“应用程序”启动。
2. 按首次设置提示授予辅助功能权限。
3. 准备 Apple 中文、英文／西语翻译语言包。
4. 可开启登录自动启动，然后打开 WhatsApp 聊天。

详见 [安装与使用说明](使用说明.txt)。

## 功能

- Apple 本地翻译，无翻译 API 调用费用。
- 译文面板随 WhatsApp 贴边，支持收起、原文对照及导入聊天文本。
- 中文草稿停笔 5 秒后转换；支持暂停及撤销翻译，不自动发送。
- 英／西语目标切换；本地内存缓存减少重复翻译。

## 当前发布状态

v0.2.12（构建 212）为未公证的内测版，使用临时签名。其他 Mac 可能被系统或公司策略拦截；请由 IT 核验，或等待正式签名版。不要关闭系统安全保护。

目前更新仍需手动下载安装；应用内“检查更新”和一键更新尚未提供。

## 隐私及限制

翻译在本机完成；语言包由 Apple 下载。聊天及译文仅在本次运行内存中处理。下载本仓库文件会访问 GitHub。

实时阅读范围是 WhatsApp 已加载的文字。图片、GIF、语音及附件内容不做识别翻译。机器翻译可能误判语气，重要内容请核对原文。

本项目与 WhatsApp／Meta 无隶属关系。公开安装包不表示源码开源或授予开源许可证。
