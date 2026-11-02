# lu791019.github.io

Dex（盧冠宏）的個人作品集網站，以 GitHub Pages 發布。

## 內容

單頁網站，分六個區塊：首頁、關於我、工作經歷、主要專案、技能、聯絡方式。

- 導覽列點擊後平滑捲動到對應區塊
- 區塊進入視窗時淡入
- 頁尾年份由 JavaScript 依當年自動更新
- 版面支援手機寬度（`@media (max-width: 768px)`）

純靜態頁面，沒有建置步驟與套件依賴；圖示來自 CDN 載入的 Font Awesome。

## 本機預覽

```bash
git clone https://github.com/lu791019/lu791019.github.io.git
cd lu791019.github.io
python3 -m http.server 8000
# 開啟 http://localhost:8000
```

## 目錄結構

```
index.html    頁面內容
styles.css    樣式
script.js     導覽捲動、區塊淡入、頁尾年份
```

## 發布

推送到 `main` 分支後由 GitHub Pages 發布。
