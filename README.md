# WhatsApp Translator for Mac

**Read English and Spanish messages in Chinese. Write replies in Chinese and translate them into English or Spanish.**

[简体中文](README.zh-CN.md) · [Download for Mac](https://github.com/Ethan8860/whatsapp-translator-mac/releases/download/v0.2.12/WhatsApp-Translator-0.2.12-Mac.dmg) · [All releases](https://github.com/Ethan8860/whatsapp-translator-mac/releases)

A companion app for the **WhatsApp desktop app on macOS**, powered by Apple's on-device translation. No translation API key or per-request translation fees.

The app's interface is currently in **Simplified Chinese**. It is designed for Chinese-speaking users chatting with English- and Spanish-speaking contacts; it is not a general-purpose translator for every language pair.

## What it does

- **Read incoming messages:** English and Spanish text appears as Chinese translations in a panel beside WhatsApp.
- **Reply in Chinese:** type directly in WhatsApp, choose English or Spanish in the companion panel, and pause typing for **5 seconds** to translate the draft.
- **Stay in control:** review and send the message yourself. The assistant never sends messages automatically.
- **Pause or undo:** pause translation while composing, or restore the Chinese draft with Undo. If the assistant is still active, the restored draft translates again after 5 seconds of inactivity.
- **Keep the conversation visible:** the panel follows the WhatsApp window, can collapse, and hides when you switch to another app.
- **Compare with the original:** show source text, retry individual translations, or import exported chat text to read older messages.

## Requirements

| Requirement | Supported |
|---|---|
| Computer | Apple Silicon Mac — M-series chips |
| Operating system | macOS 26 or later |
| WhatsApp | Native macOS desktop app |
| Translation languages | English/Spanish → Simplified Chinese; Chinese → English/Spanish |
| App interface | Simplified Chinese |

Intel Macs, Windows, mobile devices and WhatsApp Web are not supported by this build.

## Download and install

Current version: **v0.2.12 — build 212**.

1. [Download the DMG](https://github.com/Ethan8860/whatsapp-translator-mac/releases/download/v0.2.12/WhatsApp-Translator-0.2.12-Mac.dmg).
2. Open it and drag **WhatsApp Bilingual.app** into **Applications**. This is the installed application's name.
3. Launch it from Applications. Follow setup to grant **Accessibility** permission in macOS System Settings.
4. Prepare the Apple translation language packs for Chinese, English and Spanish. The initial download requires an internet connection.
5. Optionally enable launch at login, then open a WhatsApp conversation.

Prefer a package you can share? [Download the ZIP with the installer and Chinese instructions](https://github.com/Ethan8860/whatsapp-translator-mac/releases/download/v0.2.12/WhatsApp-Translator-0.2.12-Mac-Package.zip).

**macOS installation notice:** the app does not yet have Apple Developer ID signing or notarization. macOS or your organization's security policy may block it. Ask your IT administrator to review it, or wait for a signed release. Do not disable system security protections to install it.

## Quick reference for the Chinese interface

| Label | Meaning |
|---|---|
| 英文 / 西语 | English / Spanish reply target |
| 原文对照 | Show original text alongside translations |
| 暂停助手 / 继续助手 | Pause / Resume translation |
| 撤销翻译 | Restore the current Chinese draft |
| 导入记录 | Import exported chat text |
| 设置与语言包 | Settings and language packs |

## Privacy and cost

Translation runs locally using Apple's Translation framework. No paid translation account, API key, Codex or Xcode installation is required.

Chat text, imported text and translations are processed in memory during the current app session. This project does not upload them to a translation server. Language-pack downloads connect to Apple; release downloads connect to GitHub.

Accessibility permission lets the assistant read WhatsApp messages and replace the current draft. Sending remains your action.

## Limitations and updates

- Machine translation can misinterpret tone, short phrases and names. Verify amounts, dates and important commitments against the original.
- Live reading covers text currently loaded by WhatsApp, not the entire chat history at once. Scroll to load older messages or import a text export.
- Text inside images, GIFs, voice messages and attachments is not translated.
- WhatsApp updates may affect message recognition.
- Updates are currently manual: download a new version, quit the assistant, and replace the app in Applications. In-app update checking and one-click updates are not available yet.

[Full Chinese installation guide](使用说明.txt)

## About this repository

This repository distributes installers and documentation. It does not contain the application's source code, chat records or user settings. Public downloads do not imply an open-source license.

This is an independent project and is not affiliated with or endorsed by WhatsApp or Meta.
