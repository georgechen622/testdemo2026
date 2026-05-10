# 陳雋中 George Chen 個人網站

這是一個簡單的靜態個人網站，內容來自 LinkedIn 資料（陳雋中 George Chen / 台微微軟）。

## 內容
- `index.html`：網站主頁
- `styles.css`：樣式設定
- `.github/workflows/pages.yml`：GitHub Pages 自動部署設定

## 部署到 GitHub Pages
1. 初始化 git
   ```bash
   git init
   git add .
   git commit -m "Add personal website"
   ```
2. 新增遠端儲存庫並推送（替換為你的 repo URL）
   ```bash
   git remote add origin https://github.com/<username>/<repo>.git
   git branch -M main
   git push -u origin main
   ```
3. GitHub Pages 會自動從 `main` 分支部署網站。

## 備註
如果你想使用 GitHub Pages 頁面網址，請到 GitHub repo 設定頁面，確認 Pages 已啟用並指向 `main` 分支的根目錄。