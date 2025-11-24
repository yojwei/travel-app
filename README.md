# Travel App - 旅遊行程規劃 Web App

這是一個使用 Vibe Coding 方式開發的旅遊行程展示網頁應用程式，透過將行程資料整理後交給 Gemini AI 生成完整的互動式介面。

## 專案特色

- 🎨 使用 **Vue.js** 建構互動式用戶介面
- 💅 採用 **Tailwind CSS** 進行快速樣式設計
- 🤖 透過 **Gemini AI** 輔助生成程式碼
- 📱 響應式設計，支援各種裝置瀏覽
- ⚡ 輕量化單頁應用，快速載入

## 技術棧

- **前端框架**: Vue.js
- **CSS 框架**: Tailwind CSS
- **開發方式**: Vibe Coding with Gemini AI
- **專案結構**: 單頁應用 (Single Page Application)

## 開發流程

1. **行程規劃**: 整理旅遊行程資料和需求
2. **AI 生成**: 將整理好的內容提供給 Gemini AI
3. **程式碼生成**: Gemini 根據需求生成 Vue + Tailwind CSS 程式碼
4. **調整優化**: 根據實際需求進行微調

## 專案結構

```plaintext
travel-app/
├── README.md                    # 專案說明文件
├── trip-name-1/                 # 第一個行程資料夾
│   ├── index.html              # 該行程的主頁面
│   └── assets/                 # 該行程的靜態資源
│       ├── images/             # 圖片資源
│       └── data/               # 資料檔案
├── trip-name-2/                 # 第二個行程資料夾
│   ├── index.html              # 該行程的主頁面
│   └── assets/                 # 該行程的靜態資源
└── trip-name-3/                 # 第三個行程資料夾
    ├── index.html              # 該行程的主頁面
    └── assets/                 # 該行程的靜態資源
```

每個行程都有獨立的資料夾，包含：

- `index.html` - 該行程的完整網頁
- `assets/` - 該行程專屬的圖片、資料等資源

## 功能特點

- 📅 行程時間軸展示
- 📍 景點資訊卡片
- 🗺️ 互動式地圖（如適用）
- 💰 預算規劃顯示
- 📝 行程備註與提醒
- 🎯 客製化行程篩選

## Vibe Coding 工作流程

1. **收集靈感**: 整理旅遊想法和行程概念
2. **結構化資料**: 將行程資訊組織成清晰的格式
3. **提示工程**: 撰寫清晰的 prompt 給 Gemini
4. **快速迭代**: 根據生成結果快速調整和優化
5. **整合完善**: 將生成的程式碼整合並完善細節

## CDN 資源

專案使用以下 CDN 資源：

- **Vue.js 3**: `https://cdn.jsdelivr.net/npm/vue@3/dist/vue.global.js`
- **Tailwind CSS**: `https://cdn.tailwindcss.com`

## 瀏覽器支援

- Chrome (推薦)
- Firefox
- Safari
- Edge

## 授權

MIT License

## 貢獻

歡迎提交 Issue 和 Pull Request！

## 致謝

- 感謝 **Google Gemini** 提供 AI 輔助開發
- 感謝 **Vue.js** 和 **Tailwind CSS** 社群

---

**享受你的旅程！** ✈️🌏🎉
