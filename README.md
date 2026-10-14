# framelet-legal

多 App 共享的法务托管仓库（GitHub Pages 公开站点）。

## 结构

```
index.html          多 App 法务目录页（仅入口，不放页面文件）
framelet/           框影（privacy / terms / support）
<app>/              新 App 各自目录
```

## 约定

- 每个 App 一个目录（如 `framelet/`），目录内放该 App 的隐私政策、服务条款、支持页。
- **App 内链接一律直取对应目录**（如 `https://turbobo.github.io/framelet-legal/framelet/privacy.html`），不依赖根目录任何页面文件。
- 新 App 上架时：复制 `framelet/` 三页为新目录并改写内容，在根 `index.html` 增加入口卡片。
- 根目录只保留 `index.html`（目录页）与 `README.md`。
