# ESP+HOMEKIT 生成面板

> 图形化点选生成 ESP8266 / ESP32 的 **ESPHome + HomeKit 双协议** YAML，基于 Flutter，可打包成 Android APK，也能直接跑 Web 版。

## 功能

- WiFi 配置（SSID / 密码）
- HomeKit 设备类型生成
- ESPHome YAML 配置输出
- 同一套代码可出 Android APK 和 Web 页面

## 运行

```bash
flutter pub get

# Web 版
flutter run -d chrome

# Android APK
flutter build apk --release
# 产物：build/app/outputs/flutter-apk/app-release.apk
```

也可以直接用浏览器打开仓库里的 `index.html`（Web 构建产物）。

## 目录

```
lib/            # Flutter 源码
android/        # Android 工程
assets/         # 资源
index.html      # Web 入口
pubspec.yaml
```

## 许可证

本项目采用 MIT 许可证，详见 [LICENSE](LICENSE)。