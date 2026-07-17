# 白境空間清潔 — 網站資產(CDN)

由 `baijing-site` 的 `build-cdn.js` 產生的編譯資產,供 1shop 官網透過 jsDelivr 載入。

- `site.css` — 全站 CSS(設計系統 + 導覽/動效/聊天樣式)
- `site.js` — 全站 JS(導覽列、動效、小淨、假頁面路由)

**請勿手改**:改內容改 `baijing-site` 來源檔 → 跑 `build-cdn.js` → 複製 `dist/` 覆蓋這裡 → push。

jsDelivr 網址:
- https://cdn.jsdelivr.net/gh/Raffertyxu/baijing-assets@main/site.css
- https://cdn.jsdelivr.net/gh/Raffertyxu/baijing-assets@main/site.js
