# 拾形支援網站

[English](README.md) | **繁體中文**

拾形是一款在 iPhone 本機重建高斯模型的應用程式。本儲存庫僅包含公開支援與隱私政策網站，不包含應用程式原始碼、掃描資料或私人審查聯絡資訊。

- [網站](https://xdxsb.top/shixing-app-site/)
- [使用說明](https://xdxsb.top/shixing-app-site/support.html)
- [隱私政策](https://xdxsb.top/shixing-app-site/privacy.html)
- [設計](docs/plans/2026-10-17-site-design.zh-TW.md)

## 預覽與部署

在此目錄執行 `python3 -m http.server 8765`，開啟 `http://localhost:8765`。網站不需要建置步驟或套件，不包含 JavaScript、追蹤或表單後端。GitHub Pages 透過 HTTPS 提供 `main` 根目錄內容。修改使用任務分支及 PR；合併前檢查連結、內容準確性、隱私、鍵盤操作及窄螢幕排版。

部署後確認首頁、支援及隱私政策均回傳 HTTP 200。若需修正已發布內容，透過新的 PR 撤回相關提交，並確認 Pages 重新部署。維持公開客服信箱有效，不加入私人掃描、電話或帳戶資料。裝飾插畫清楚標示為示意圖，並非掃描結果。應用程式目前仍在準備上架。

此帳戶既有的 Pages 自訂網域為 `xdxsb.top`，透過 Cloudflare 提供服務。請使用上方直接 HTTPS 網址；`github.io` 專案網址會重新導向帳戶網域。不要為此網站更改既有的帳戶網域或 DNS。
