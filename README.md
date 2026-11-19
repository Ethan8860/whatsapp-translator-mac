# WhatsApp Translator for Mac

**Read and reply in eight languages — directly alongside WhatsApp.**

[简体中文](README.zh-CN.md) · [Download for Mac](https://github.com/Ethan8860/whatsapp-translator-mac/releases/download/v0.3.7/WhatsApp-Translator-0.3.7-Mac.dmg) · [All releases](https://github.com/Ethan8860/whatsapp-translator-mac/releases)

A companion for the native WhatsApp desktop app, using Apple's on-device translation. No translation API key or per-request fees. **v0.3.7 · build 307**.

## Choose your languages

- **Interface language:** Simplified Chinese, English, Spanish, French or German, independently of translation settings.
- **Reading and input language:** the language you read translations in and write your drafts in.
- **Reply language:** the language your draft should become. Open the reply selector above the conversation. Options use the current interface language. If it matches your input language, drafts stay unchanged.

The eight translation languages are Simplified Chinese, English, Spanish, French, Japanese, Brazilian Portuguese, German and Italian. English↔Spanish drafts, Undo, Pause and Resume were also tested in a real WhatsApp composer. This is not a guarantee of translation accuracy.

## How it works

1. Open a WhatsApp conversation. Loaded text appears in a translation panel beside the window.
2. Write in your selected input language directly in WhatsApp. After **5 seconds without typing**, the assistant replaces the draft with a translation.
3. Review it, then send it yourself. **The assistant never sends messages automatically.**

Pause while thinking or composing. Undo restores the original draft; if translation remains active, it translates again after 5 seconds of inactivity. The panel follows WhatsApp, collapses when needed and hides when you switch apps. Compare originals or import exported chat text for older history.

## Install

Requires an **Apple Silicon Mac, macOS 26 or later**, and the native WhatsApp app. Intel Macs, Windows, mobile devices, WhatsApp Web and other messaging clients are not supported by this release.

1. Download the DMG and drag **WhatsApp Bilingual.app** into **Applications**.
2. Open the app and choose interface, reading/input and reply languages.
3. Grant Accessibility permission in System Settings. Prepare and test the selected Apple language packs; initial downloads require internet access.
4. Optionally enable launch at login, then choose Start Using WhatsApp.


The app is locally signed, without Apple Developer ID signing or notarization. macOS or company policies may block it. Ask your IT administrator to review it or wait for a signed release; do not disable system security protections.

## Updates

Open **More → Check for Updates**. The check anonymously reads public GitHub release information. If a newer version is available, choose **Download and Update**. The assistant verifies the installer and restarts.

To install this release from v0.3.0, quit the assistant and replace the app in Applications. Keep the same installed application name/path to retain settings and launch-at-login behavior. macOS may require refreshing its Accessibility permission after a signature change.

## Privacy and limits

Translation is processed locally; chat text, imported records and translations stay in memory for the running session. The assistant does not upload chat content to a translation server. Apple supplies language packs; GitHub supplies update information and downloads. No Codex, Xcode or paid translation account is needed.

- Machine translation may misread short phrases, names or tone. Review important amounts, dates and commitments.
- Live reading covers currently loaded text, not the entire history at once. Scroll in WhatsApp or import a text export.
- Images, GIF content, audio and attachments are not translated.
- Native acceptance used WhatsApp 2.26.46.15 with its interface in Chinese. English/Spanish WhatsApp message-envelope parsing has automated fixtures but still needs live acceptance; WhatsApp updates may affect recognition.
- More languages, clients and platforms are planned, not currently supported.

[Installation guide / 使用说明](使用说明.txt)

## About this repository

This repository distributes installers and documentation only. It contains no application source code, chat records or user settings; public downloads do not imply an open-source license.

Independent project; not affiliated with or endorsed by WhatsApp or Meta.
