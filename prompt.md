# 🎬 影展專題網頁《綠空慢泡，綠川漾抹》Vibe Coding & 開發紀錄

本專題為逢甲大學大二影展專題官方介紹網頁，結合都市療癒系視覺與現代化前端排版技術，完整記錄從構想、HTML 語意化架構、CSS 現代化樣式切割、RWD 響應式設計到部署的完整歷程。

---

## 📌 目錄
1. 專題核心理念與專案架構
2. Prompt 1 : HTML5 語意化架構與 SEO 規劃
3. Prompt 2 : CSS 樣式模組化切割與 Grid 雙欄佈局
4. Prompt 3 : RWD 響應式與視覺亮點優化
5. 部署與成果展示連結

---

## 1. 專題核心理念與專案架構
- **專題名稱：** 《綠空慢泡，綠川漾抹》
- **核心 Slogan：** 「讓煩惱化為泡影，在綠川重拾清醒。」
- **專案資料夾結構：**
  - `index.html`：網頁主結構與語意化標籤
  - `prompt.md`：Vibe Coding 開發與 Prompt 紀錄檔
  - `css/project1.css`：獨立切割之現代化 CSS 樣式表
  - `images/`：收錄綠空廊道、綠川水岸等實景劇照

---

## 2. Prompt 1 : HTML5 語意化架構與 SEO 規劃

> **Prompt 內容：**
> 「請幫我設計一個逢甲大學大二影展專題《綠空慢泡，綠川漾抹》的官方介紹網頁。包含完整的 HTML5 語意化標籤、SEO Meta 設定、側邊欄導覽、Hero Banner、三大視覺亮點、分鏡介紹卡片與取景地點巡禮。」

- **實作成果：**
  - 運用 `<nav>`、`<aside>`、`<main>`、`<section>` 等語意化標籤，提升程式碼可讀性。
  - 設置完整的 Meta Description 與 Keywords，優化搜尋引擎最佳化 (SEO)。
  - 建立固定式導覽列與側邊欄快速錨點跳轉。

---

## 3. Prompt 2 : CSS 樣式模組化切割與 Grid 雙欄佈局

> **Prompt 內容：**
> 「請將 CSS 檔案進行切割，獨立放置於 `css/` 資料夾中的 `project1.css`。採用深青色與翡翠綠的都市療癒系調性，包含 CSS Grid 雙欄佈局、卡片懸浮動畫與精美標籤樣式。」

- **實作成果：**
  - 成功將樣式表獨立模組化，於 `index.html` 的 `<head>` 中透過 `<link rel="stylesheet" href="css/project1.css">` 引入。
  - 導入 CSS Grid 系統，打造左側固定導覽、右側主內容的精緻雙欄佈局。

---

## 4. Prompt 3 : RWD 響應式與視覺亮點優化

> **Prompt 內容：**
> 「請為專題網頁加入完整 RWD 響應式功能，確保在手機等行動裝置上能夠完美顯示完整資訊，並將實景照片（綠空廊道與綠川）完美嵌入取景地點巡禮卡片中。」

- **實作成果：**
  - 運用 Media Queries（`@media (max-width: 768px)`）實現行動裝置自動適應，小螢幕下側邊欄與導覽列自動切換為單欄直式排版。
  - 嵌入真實景點攝影作品，透過 `object-fit: cover` 確保圖片在各種尺寸下皆不變形。

---

## 5. 專案相關連結
- **(1) Prompt 說明 (GitHub Markdown)：** [點此查看 GitHub 原始檔](https://github.com/ranpoyo/project1/blob/main/prompt.md)
- **(2) InfinityFree Landing Page：** 部署首頁網址
- **(3) Vercel 部署網址：** Vercel 專案線上預覽網址
```[cite: 6]

