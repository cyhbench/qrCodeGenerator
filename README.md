# 📱 QR Code Generator

即時 QR Code 產生器。輸入任何內容，即時產生 QR Code。

## 功能

- ⚡ **即時產生** — 輸入即刻生成，200ms debounce
- 🌍 **萬物皆可** — 網址、純文字、電話、Email、WiFi 密碼，任何字串
- 📏 **四種尺寸** — S (256) / M (384) / L (512) / XL (768)
- 🎨 **雙色模式** — 黑底白碼 / 淺色底
- ⬇ **一鍵下載** — PNG 格式
- 📋 **一鍵複製** — 直接複製圖片到剪貼簿
- 💾 **自動儲存** — 內容存 localStorage
- 📱 **手機優先** — 觸控友善介面
- 🌙 **暗色 UI** — 護眼深色主題
- 📦 **零後端** — 純前端，單一 HTML 檔

## 技術

- [qrcode.js](https://github.com/soldair/node-qrcode) — QR Code 生成
- 純 HTML/CSS/JS，無需 build

## 使用

直接開啟 `index.html` 即可。

```bash
# 本地開啟
open index.html

# 或用 Python 簡單伺服
python3 -m http.server 8080
```

## 部署到 GitHub Pages

1. 建立 GitHub repo
2. 上傳 `index.html`
3. Settings → Pages → Source 選 main branch
4. 完成

## QR Code 容量

- 純數字：最多 7,089 字元
- 英數混合：最多 4,296 字元
- 二進位：最多 2,953 字元
- 中文（UTF-8）：約 1,800 字元
