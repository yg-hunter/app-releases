# 开源软件发布仓库

本仓库用于发布个人开发的开源应用安装包，**不含源码**。所有应用均免费使用。

## 应用列表

| 应用 | 版本 | 平台 | 下载 | 更新日志 |
|------|------|------|------|----------|
| my-notes | v0.7.0 | Windows x64 | [下载](https://github.com/yg-hunter/app-releases/releases/download/v0.7.0/my-notes-v0.7.0-windows-x64.zip) | [更新日志](CHANGELOG.md) |
| my-notes | v0.7.0 | Android arm64 | [下载](https://github.com/yg-hunter/app-releases/releases/download/v0.7.0/my-notes-v0.7.0-android.apk) | [更新日志](CHANGELOG.md) |
| my-notes | v0.5.0 | Windows x64 | [下载](https://github.com/yg-hunter/app-releases/releases/download/v0.5.0/my-notes-v0.5.0-windows-x64.zip) | [更新日志](CHANGELOG.md) |
| my-notes | v0.5.0 | Android arm64 | [下载](https://github.com/yg-hunter/app-releases/releases/download/v0.5.0/my-notes-v0.5.0-android.apk) | [更新日志](CHANGELOG.md) |
| my-notes | v0.3.0 | Windows x64 | [下载](https://github.com/yg-hunter/app-releases/releases/download/v0.3.0/my-notes-v0.3.0-windows-x64.zip) | [更新日志](CHANGELOG.md) |
| my-notes | v0.3.0 | Android arm64 | [下载](https://github.com/yg-hunter/app-releases/releases/download/v0.3.0/my-notes-v0.3.0-android.apk) | [更新日志](CHANGELOG.md) |
| my-notes | v0.3.1 | Windows x64 | [下载](https://github.com/yg-hunter/app-releases/releases/download/v0.3.1/my-notes-v0.3.1-windows-x64.zip) | [更新日志](CHANGELOG.md) |
| my-notes | v0.3.1 | Android arm64 | [下载](https://github.com/yg-hunter/app-releases/releases/download/v0.3.1/my-notes-v0.3.1-android.apk) | [更新日志](CHANGELOG.md) |
| weight manager | v2.5.0 | Android 8.0+（通用） | [下载](https://github.com/yg-hunter/app-releases/releases/download/weight-manager-v2.5.0/weight%20manager-v2.5.0.apk) | [更新日志](CHANGELOG.md) |
| weight manager | v2.5.0 | Android arm64 | [下载](https://github.com/yg-hunter/app-releases/releases/download/weight-manager-v2.5.0/weight%20manager-v2.5.0-arm64.apk) | [更新日志](CHANGELOG.md) |

## 使用说明

- **Windows**：下载 zip 解压后直接运行 exe，无需安装
- **Android**：下载 APK 安装，需开启"允许未知来源应用"

## 发布规范

- 每个应用一个 Release 标签前缀，标签格式 `应用名-版本号`（如 `my-notes-v0.7.0`、`weight-manager-v2.5.0`）
- 安装包命名：`应用名-版本号-平台.扩展名`（如 `my-notes-v0.3.0-android.apk`）
- 每个版本更新后，在 `CHANGELOG.md` 按应用分节追加更新记录
