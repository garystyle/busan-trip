# 釜山自由行行程網站

一份可直接部署到 GitHub Pages 的單頁釜山五日行程網站。

## 功能與技術

- 總覽頁與五日行程切換，支援桌面與手機版排版。
- 圖片、插畫、CSS 與 JavaScript 均已放在 `index.html`，沒有外部套件、建置步驟或額外圖片附件。
- 可離線開啟；上傳到 GitHub Pages 後可透過網址瀏覽。

## 本機預覽

直接用瀏覽器開啟 `index.html` 即可。

## 部署到 GitHub Pages

1. 在 GitHub 建立新的 repository，將本資料夾中的檔案放在 repository 根目錄。
2. 開啟 repository 的 **Settings → Pages**。
3. 在 **Build and deployment** 選擇 **Deploy from a branch**，分支選 `main`、資料夾選 `/ (root)`，再按 **Save**。
4. 等待 GitHub Pages 部署完成後，從 Pages 設定頁開啟網站網址。

本專案不需要編譯或 GitHub Actions workflow。

## 發布前隱私檢查

目前行程頁包含具體旅遊日期、航班資訊、住宿名稱與地址。若 repository 設為公開，任何人都可能看到這些內容；公開前請確認是否要保留、遮蔽或移除。

## 授權

目前未附授權條款。若希望他人可以複製或改作，發布前請選擇並加入適合的 `LICENSE` 檔案。
