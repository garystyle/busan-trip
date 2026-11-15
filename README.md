# 釜山自由行行程網站

一份可直接部署到 GitHub Pages 的單頁釜山五日行程網站。

## 功能與技術

- 總覽頁與五日行程切換，支援桌面與手機版排版。
- 網站所需圖片、插畫、CSS 與 JavaScript 均已內嵌在 `index.html`；部署網站不需額外附件、外部套件或建置步驟。
- 原始行程筆記及 8 張參考圖片另保存在 `source/`，供後續維護與 AI 接手使用。
- 可離線開啟；上傳到 GitHub Pages 後可透過網址瀏覽。

## 本機預覽

直接用瀏覽器開啟 `index.html` 即可。

## 原始行程與 AI 接手

- `source/2026-12-22_釜山自由行.md` 是原始行程文件的未修改副本；8 張原始圖片與筆記放在同一資料夾。
- 原始筆記使用 Obsidian 的 `![[檔名]]` 圖片語法，GitHub 預覽可能不會顯示圖片；請 AI 依檔名直接檢視 `source/` 內的圖片。
- 雲端 AI 接手時，先閱讀 [`AI_HANDOFF.md`](AI_HANDOFF.md)，再閱讀原始行程與相關圖片。

## 部署到 GitHub Pages

1. 在 GitHub 建立新的 repository，將本資料夾中的檔案放在 repository 根目錄。
2. 開啟 repository 的 **Settings → Pages**。
3. 在 **Build and deployment** 選擇 **Deploy from a branch**，分支選 `main`、資料夾選 `/ (root)`，再按 **Save**。
4. 等待 GitHub Pages 部署完成後，從 Pages 設定頁開啟網站網址。

本專案不需要編譯或 GitHub Actions workflow。

## 發布前隱私檢查

目前行程頁與原始資料包含具體旅遊日期、航班資訊、住宿名稱、地址及住宿分享連結。若 repository 設為公開，任何人都可能看到這些內容；公開前請確認是否要保留、遮蔽或移除。

## 授權

目前未附授權條款。若希望他人可以複製或改作，發布前請選擇並加入適合的 `LICENSE` 檔案。
