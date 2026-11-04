# My Portfolio — 周凡茗 Fan-Ming Chou

個人作品集網站，採 Y2K Chrome / 液態金屬風格，內建**深色 / 淺色模式切換**。

## 內容

| 檔案 | 說明 |
| --- | --- |
| `index.html` | 網站主頁（單一 HTML 檔，樣式與腳本皆內嵌，無需建置工具） |
| `我的資料.md` | 個人履歷資料（求職目標、專題、證照、經歷、聯絡方式） |

## 功能

- **深色 / 淺色模式切換**：右上角切換鈕，選擇會記錄在 `localStorage`（`fm-portfolio-theme`），重新整理不會跳色。
- **Y2K Chrome 視覺**：全息雷射漸層邊框、鉻金標題漸層、打字機跑馬燈、玻璃卡片。
- **響應式版面**：桌面 12 欄 Bento 網格，平板與手機自動降為單欄。
- **無障礙**：切換鈕具 `aria-pressed` / `aria-label`，焦點樣式清晰，文字對比符合 WCAG AA。

## 本地預覽

直接用瀏覽器開啟 `index.html` 即可；或啟動任一靜態伺服器：

```bash
npx serve .
python -m http.server 8000
```

## GitHub Pages

本 repo 啟用 Pages 後，網址為：
<https://baixuan2222.github.io/my-portfolio/>

## 授權

原始碼可自由使用與修改，內容屬於周凡茗 Fan-Ming Chou。
