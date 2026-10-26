# Harrik Player — Release Assets

Harrik Player 是面向 Android TV 的沉浸式媒体播放器，兼容 Emby / Jellyfin 服务端。

本仓只分发已签名 APK；最新版本见 [Releases](https://github.com/harriks/harrik-player/releases/latest)。

## 技术栈

- Kotlin / Jetpack Compose for TV
- Media3 / ExoPlayer + FFmpeg 扩展（AC3 / EAC3 / DTS / MLP / TrueHD）
- Room / DataStore / Coil / Koin
- OkHttp + Cronet

## 安装

- Android 7.0+（API 26），面向 Android TV。
- 1.1.12 使用新签名；安装过旧版本的用户需先卸载旧版再安装，账号与设置需重新登录。
- 按设备 ABI 选择 `app-arm64-v8a-release.apk`、`app-armeabi-v7a-release.apk` 或 `app-x86_64-release.apk`；不确定时使用 `HarrikPlayer-v*-universal.apk`。

## 校验

每个 Release 的说明中提供 SHA-256；请只从本仓 Releases 下载。
