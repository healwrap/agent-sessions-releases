# Agent Sessions

会话与账号，一处管理。 / Your agent sessions and accounts, in one workspace.

本仓库提供 Agent Sessions 桌面安装包、版本说明和签名更新清单。项目源代码在独立的私有仓库中维护。

This repository hosts desktop installers, release notes and signed update metadata. Source code is maintained in a separate private repository.

## 下载安装 / Downloads

[下载最新版本 / Download the latest release](https://github.com/healwrap/agent-sessions-releases/releases/latest)

| 系统 / Platform | 安装包 / Installer |
| --- | --- |
| macOS Apple Silicon | `Agent-Sessions_<version>_macOS-arm64.dmg` |
| Windows x64 | `Agent-Sessions_<version>_windows-x86_64-setup.exe` |

下载不需要登录 GitHub。macOS 镜像附有 SHA-256 校验文件。

Downloads do not require a GitHub account. macOS images include SHA-256 checksums.

## 应用更新 / In-app updates

支持此分发渠道的版本可在“设置 → 应用更新”中检查更新。更新包沿用应用内置公钥校验签名。

Versions configured for this channel can check for updates in **Settings → App updates**. Update signatures are verified with the public key embedded in the app.

更新清单 / Update feed: [latest.json](https://github.com/healwrap/agent-sessions-releases/releases/latest/download/latest.json)

原先使用私有源码仓库下载地址的旧版本，需要安装一次接入新渠道的版本，之后即可使用公开更新。

Older versions using the source repository's download address require one installation of a build configured for this channel before public in-app updates work.

## 反馈 / Feedback

[提交问题或建议 / Report a problem or suggestion](https://github.com/healwrap/agent-sessions-releases/issues)

请勿上传账号登录数据、访问 Key、代理凭据或个人会话正文。

Do not attach account login data, access keys, proxy credentials or private conversation contents.
