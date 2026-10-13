# Framelet Legal Pages

框影（Framelet，iOS App）App Store 上架用**法务页静态站**，GitHub Pages 托管。

| 页面 | URL |
|---|---|
| 隐私政策 | https://turbobo.github.io/framelet-legal/privacy.html |
| 服务条款 | https://turbobo.github.io/framelet-legal/terms.html |
| 支持 | https://turbobo.github.io/framelet-legal/support.html |

> 本仓库**仅含公开发布副本，不含任何 App 源码**（主仓库 `photo-frame-SwiftUI` 保持私有）。
> 源文件同步自主仓库 `docs/legal/`。修改流程：改主仓库 `docs/legal/` → 同步本仓库 → push（Pages 自动重建）。

## 消费位置

- **App 内**：`PaywallView.swift`（付费页底部两链接——订阅披露必需位，App 内唯一入口；关于页入口已按产品决定于 v1.3.136 移除）
- **App Store Connect**：App 隐私区「隐私政策 URL」= privacy.html；商店页「支持 URL」= support.html
- 发布历史：2026-10-13 首版上线（方案 C：独立公开仓库 + Pages 默认域，零 DNS / 零备案）
