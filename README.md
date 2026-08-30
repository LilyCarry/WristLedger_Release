# ⚡ 闪电记账 (WristLedger) 公共发布与公告中心

欢迎访问《闪电记账 (WristLedger)》官方发布与公告更新中心。本项目为 Xiaomi Vela 穿戴设备与 Android 伴侣端提供高速免翻墙 CDN 静态分发服务。

---

## 📦 最新版本基准 (v2.0.1)

| 端别 | 适用机型 | 发布渠道 / 下载入口 | 表盘自定义工具状态 |
| :--- | :--- | :--- | :---: |
| **小屏手环版** | 小米手环 9 / 10 等跑道屏 | [米坛社区 (资源ID: 7615)](https://www.bandbbs.cn/resources/7615/) | 🔴 未更新 / 审核中 |
| **大屏手表版 (Pro)** | 小米手表 / 大屏方形表 | [米坛社区 (资源ID: 7616)](https://www.bandbbs.cn/resources/7616/) | 🔴 未更新 / 审核中 |
| **Android 伴侣端** | Android 7.0+ 手机 | [GitHub Releases 下载 APK](https://github.com/LilyCarry/WristLedger_Release/releases) | —— |

---

## 📡 4 级智能容灾 CDN 节点

Android 伴侣端与客户端通过以下 4 级静态节点轮询拉取最新公告与更新信息 (`app_notice.json`)：

1. **Fastly CDN**: `https://fastly.jsdelivr.net/gh/LilyCarry/WristLedger_Release@main/app_notice.json`
2. **Default CDN**: `https://cdn.jsdelivr.net/gh/LilyCarry/WristLedger_Release@main/app_notice.json`
3. **GitHub Raw**: `https://raw.githubusercontent.com/LilyCarry/WristLedger_Release/main/app_notice.json`
4. **ghproxy 镜像**: `https://ghproxy.net/https://raw.githubusercontent.com/LilyCarry/WristLedger_Release/main/app_notice.json`

---

## 📜 关联项目仓库

- **手环端工程 (Vela QuickApp)**: [LilyCarry/wrist-ledger](https://github.com/LilyCarry/wrist-ledger)
- **伴侣端工程 (Android Kotlin/M3)**: [LilyCarry/WristLedger_Android](https://github.com/LilyCarry/WristLedger_Android)
