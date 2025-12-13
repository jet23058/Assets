# 喵喵資產 (Meow Meow Assets) 🐾

這是一個現代化、介面精美的個人資產追蹤應用程式。專為個人理財設計，提供直觀的資產增長趨勢、月度收支分析以及詳細的財務儀表板。

![Version](https://img.shields.io/badge/version-2.0.0-teal.svg)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

## ✨ 特色功能

### 📊 視覺化分析
- **年度資產趨勢圖**: 使用互動式 Area Chart 呈現資產變化，支援年份切換。
- **花費分佈分析**: 自動統計月度花費類別，以 Pie Chart 呈現前五大花費項目。
- **綜合損益指標**: 獨家的綜合評分系統，結合收入成長與資產累積表現。

### 💰 財務追蹤
- **多維度紀錄**: 支援資產總額、月備忘錄、月收入、月結餘。
- **CSV 匯入整合**: 完美支援 **MOZE** 記帳軟體 CSV 格式匯入，自動解析花費明細。
- **年度統計卡片**: 
  - 年度資產增長金額與比例
  - 年度最高/最低資產月份
  - 平均月收入與年總收入分析

### ☁️ 雲端同步與安全
- **Google 登入**: 整合 Firebase Authentication，安全快速。
- **雲端備份**: 資料即時同步至 Firestore，換裝置也能無縫接軌。
- **大數據優化**: 針對大量交易紀錄進行資料分塊 (Chunking) 處理，確保讀取效能。

## 🛠️ 技術棧

- **Frontend**: React 18, Vite
- **UI/Styling**: Tailwind CSS (Simulated), Lucide React Icons
- **Charts**: Recharts
- **Backend/Auth**: Firebase (Auth, Firestore, Storage)

## 🚀 快速開始

### 1. 安裝依賴
```bash
npm install
```

### 2. 設定環境變數
請在專案根目錄建立 `.env` 檔案，並填入 Firebase 設定：

```env
VITE_FIREBASE_API_KEY=your_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_storage_bucket
VITE_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
VITE_FIREBASE_APP_ID=your_app_id
```

### 3. 啟動開發伺服器
```bash
npm run dev
```
開啟瀏覽器訪問 `http://localhost:5173`。

## 📝 版本紀錄

- **v2.0.0** (Current)
  - 整合 Firebase 雲端儲存與身份驗證。
  - 新增年度資產統計卡片與詳細 Tooltip 分析。
  - 優化 CSV 匯入流程與錯誤處理。
  - 介面視覺升級。

- **v1.2.0**
  - 使用 React + Vite 重構。
  - 基礎資產記錄功能。

## 📄 License
MIT

---
Developed by Jet & Antigravity