# 智慧老人村住民版 Demo

公開展示網址：<https://andyludeveloper.github.io/smart-nursing-home-demo/>

這個 repository 只包含 Vite 編譯後的靜態網站與 GitHub Pages 部署設定。

Vue、TypeScript、測試、PRD 與設計規格原始檔不包含在此公開 repository 中。

## Demo 限制

- 所有住民、房間、環境、設備、通知與求助資料都是虛構的本機模擬資料。
- 網站不會連線到真實登入、設備、感測器、後端或照護中心 API。
- 所有聯絡入口都只是介面展示，不會撥打電話或傳送訊息。

## 發布邊界

- Repository 根目錄只允許放置可公開部署的編譯成果、README、provenance 與 Pages workflow。
- 編譯使用 `VITE_BASE_PATH=/smart-nursing-home-demo/ npm run build-only`。
- 每次更新均需重新驗證測試、型別、build、asset 引用及原始碼未外洩。
- 本次 artifact 的來源與 SHA-256 記錄在 [BUILD-PROVENANCE.md](BUILD-PROVENANCE.md)。
