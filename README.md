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

- **App 内**：`PaywallView.swift`（付费页两链接）+ `AboutView.swift`（关于页两链接）
- **App Store Connect**：App 隐私区「隐私政策 URL」= privacy.html；商店页「支持 URL」= support.html
- 发布历史：2026-10-13 首版上线（方案 C：独立公开仓库 + Pages 默认域，零 DNS / 零备案）
