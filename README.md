# Machine Learning Teaching Platform

本專題旨在打造一個整合式的機器學習教學平台，結合課程內容、自然語言互動、程式範例與自動批改功能，幫助初學者有效學習機器學習知識。

## 🎯 專案目標
- 提供學生能以自然語言向系統提問的互動式學習平台
- 結合大語言模型（LLM）與資料檢索（RAG）技術，提升回答品質
- 整合練習題、選擇章節、程式比對與自動批改功能
- 改善學習動機，強化理解效果

## 🔧 使用技術
- 前端：HTML / CSS / JavaScript（Flask template）
- 後端：Python Flask
- 模型接入：LM Studio + RAG（Retrieval-Augmented Generation）
- 向量資料庫：FAISS
- 自動批改與比對機制：選擇題標準答案比對 + 程式碼比對功能

## 🖥️ 功能模組
- 🧑‍🏫 課程章節展示：依章節呈現教材與練習
- 💬 自然語言問答：使用者可輸入問題，系統用 RAG 技術回答
- ✅ 自動批改：支援選擇題的範圍選擇與成績批改
- 🧪 實作練習：附程式碼比對機制與練習題展示
- 📺 使用者影片展示：搭配 Demo 影片加強說明

## 🚀 如何執行
1. 安裝套件：
   ```bash
   pip install -r requirements.txt
   ```

2. 啟動 Flask 應用：
   ```bash
   python app.py
   ```

3. 打開瀏覽器進入：
   ```
   http://127.0.0.1:5000
   ```

## 👨‍💻 開發團隊
- 江慶澤
- 黃亮瑜
- 陳師緯
- 汪亞蕬

## 📁 資料夾結構
```
.
├── app.py
├── requirements.txt
├── templates/
│   └── index.html
├── static/
│   └── style.css
└── README.md
```


