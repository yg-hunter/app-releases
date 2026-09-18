# 开源软件发布仓库

本仓库用于发布个人开发的开源应用安装包，**不含源码**。所有应用均免费使用。

## 应用列表

| 应用 | 版本 | 平台 | 下载 | 更新日志 |
|------|------|------|------|----------|
| my-notes | v0.5.0 | Windows x64 | [下载](https://github.com/yg-hunter/app-releases/releases/download/v0.5.0/my-notes-v0.5.0-windows-x64.zip) | [更新日志](CHANGELOG.md) |
| my-notes | v0.5.0 | Android arm64 | [下载](https://github.com/yg-hunter/app-releases/releases/download/v0.5.0/my-notes-v0.5.0-android.apk) | [更新日志](CHANGELOG.md) |
| my-notes | v0.3.0 | Windows x64 | [下载](https://github.com/yg-hunter/app-releases/releases/download/v0.3.0/my-notes-v0.3.0-windows-x64.zip) | [更新日志](CHANGELOG.md) |
| my-notes | v0.3.0 | Android arm64 | [下载](https://github.com/yg-hunter/app-releases/releases/download/v0.3.0/my-notes-v0.3.0-android.apk) | [更新日志](CHANGELOG.md) |
| my-notes | v0.3.1 | Windows x64 | [下载](https://github.com/yg-hunter/app-releases/releases/download/v0.3.1/my-notes-v0.3.1-windows-x64.zip) | [更新日志](CHANGELOG.md) |
| my-notes | v0.3.1 | Android arm64 | [下载](https://github.com/yg-hunter/app-releases/releases/download/v0.3.1/my-notes-v0.3.1-android.apk) | [更新日志](CHANGELOG.md) |

## 使用说明

- **Windows**：下载 zip 解压后直接运行 exe，无需安装
- **Android**：下载 APK 安装，需开启"允许未知来源应用"

## 发布规范

- 每个版本一个 Release，tag 格式 `v版本号`（如 `v0.3.0`）
- 安装包命名：`应用名-版本号-平台.扩展名`（如 `my-notes-v0.3.0-android.apk`）
- 每个版本更新后，在 `CHANGELOG.md` 追加更新记录
