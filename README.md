# framelet-legal

多 App 共享的法务托管仓库（GitHub Pages 公开站点）。

## 结构

```
index.html          多 App 法务目录页
framelet/           框影（隐私政策 / 服务条款 / 支持）
privacy.html        历史根路径重定向 → framelet/privacy.html
terms.html          历史根路径重定向 → framelet/terms.html
support.html        历史根路径重定向 → framelet/support.html
```

## 约定

- 每个 App 一个目录（如 `framelet/`），目录内放该 App 的隐私政策、服务条款、支持页。
- 新 App 上架时：复制 `framelet/` 三页为新目录并改写内容，在根 `index.html` 增加入口卡片。
- 页面 URL 形如 `https://turbobo.github.io/framelet-legal/<app>/privacy.html`，App Store Connect 中登记该地址即可。
- 历史根路径保留 meta-refresh 重定向占位，避免旧链接 404。
