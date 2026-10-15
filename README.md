# 曖昧關係模擬器：朋友圈線索版

這是純靜態網站，可直接部署到 GitHub Pages。

## 本地開啟

直接雙擊 `index.html` 即可。遊戲進度會保存在瀏覽器 `localStorage`。

## 部署至 GitHub Pages

1. 在 GitHub 建立新 repository。
2. 把 `index.html`、`styles.css`、`app.js` 上傳到 repository 根目錄。
3. 開啟 **Settings → Pages**。
4. 在 **Build and deployment** 選擇 **Deploy from a branch**。
5. Branch 選擇 `main`，資料夾選擇 `/ (root)`，然後按 **Save**。

## 主要功能

- 隨機開場情境
- 多條劇情分支
- 朋友圈篩選、按讚、留言顯示及線索查看
- 朋友圈線索會解鎖後續專屬選項並影響關係數值
- 10項隱藏關係數值
- 主持人面板
- 自由輸入
- 自動存檔
- 響應式手機與桌面版面
