# Harrik Player — Release Assets

本仓只分发 Harrik Player 的已签名 APK；源码仓库为私有。

- 最新版本：https://github.com/harriks/harrik-player/releases/latest
- ABI 专用包：`app-arm64-v8a-release.apk`、`app-armeabi-v7a-release.apk`、`app-x86_64-release.apk`
- 通用包：`HarrikPlayer-v*-universal.apk`（不确定 ABI 时使用）
- 最低 Android 7.0（API 26），面向 Android TV。

## 1.1.12 签名迁移

v1.1.11 及更早版本为 debug 签名，**不能覆盖安装** 1.1.12。请先卸载旧版再安装；账号、设置与登录 token 会丢失。

v1.1.11 的应用内更新仍指向旧私有 API，不会提示升级，需要手动下载安装 1.1.12；从 1.1.12 起自动更新恢复。

## 校验

每个 Release 的 notes 提供 SHA-256；请只从本仓 Releases 下载。
