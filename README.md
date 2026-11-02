# 智慧記帳與理財小幫手 (Smart Bookkeeping & Financial Tracker)

![License](https://img.shields.io/badge/license-MIT-green.svg)
![Build](https://img.shields.io/badge/build-passing-brightgreen)
![Platform](https://img.shields.io/badge/platform-Mobile%20%7C%20Desktop-blue)

一個輕量、乾淨、直覺且完全保護隱私的 Web 記帳與理財工具。無需註冊帳號，所有資料皆安全儲存在您的個人裝置中，完全零伺服器成本。

---

## ✨ 產品特色

- 💰 **收支快速紀錄**：輕鬆紀錄每一筆收入與支出，支援自訂金額、類別、項目與發票號碼。
- 📊 **視覺化圖表分析**：自動生成每月收支類別圓餅圖，消費結構一目了然。
- 🎯 **互動式理財目標**：設定儲蓄目標，動態計算累積進度與專屬勵志小語，讓記帳充滿動力。
- 🏷️ **靈活分類管理**：隨時新增、刪除或修改收入與支出的類別。
- 📁 **資料安全與備份**：
  - **100% 隱私安全**：資料僅儲存於本地裝置（IndexedDB & LocalStorage），不連外伺服器。
  - **匯出 / 匯入 JSON**：可隨時備份或轉移歷史紀錄至其他裝置。
- 📱 **響應式行動優先設計**：專為手機體驗優化，提供貼心的 Mobile 底部導覽列，支援 PWA 模式「加入主畫面」。

---

## 🛠️ 使用技術

本專案採用 **極簡化輕量無編譯架構**，完全透過 CDN 載入：

- **前端框架**：[Alpine.js](https://alpinejs.dev/) - 輕量極速的單頁反應式 UI 框架
- **樣式庫**：[Tailwind CSS](https://tailwindcss.com/) - 響應式 Utility-First CSS 框架
- **圖表繪製**：[Chart.js](https://www.chartjs.org/) - 動態視覺化統計圖表
- **圖示庫**：[FontAwesome 6](https://fontawesome.com/) - 豐富的向量圖示
- **資料儲存**：IndexedDB & LocalStorage API

---

## 🚀 快速開始 / 部署指南

### 方法一：GitHub Pages 免費部署 (推薦)

1. **Fork 或 Clone** 本儲存庫至您的 GitHub 帳號。
2. 開啟儲存庫的 **Settings (設定)** $\rightarrow$ **Pages**。
3. 在 **Build and deployment** $\rightarrow$ **Branch** 選擇 `main` (或 `master`) 並儲存。
4. 約 1~2 分鐘後即可取得您的專屬線上記帳網址！

### 方法二：本地端直接開啟

1. 將本專案下載至您的電腦。
2. 直接雙擊 `index.html` 檔即可開開啟瀏覽器開始記帳，無需安裝 Node.js 或架設 Web 伺服器。

---

## 📱 手機端最佳使用方式 (加入主畫面)

1. 用手機瀏覽器（iOS Safari 或 Android Chrome）開啟部署好的網址。
2. 點擊瀏覽器的 **「分享 / 選單」** 按鈕。
3. 選擇 **「加入主畫面 (Add to Home Screen)」**。
4. 即可在手機桌面上像原生 APP 一樣隨點隨記！

---

## 📄 授權條款

本專案採用 [MIT License](LICENSE) 授權，歡迎自由修改與分享。