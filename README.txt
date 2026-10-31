台股掌帳｜手機／平板行動版
檔案：index.html、manifest.webmanifest、service-worker.js、icon-192.svg、icon-512.svg

使用方式：
1. 解壓縮 ZIP。
2. 可直接用瀏覽器開啟 index.html 使用帳務功能；行情跨網域請求在 file:// 模式可能被瀏覽器阻擋。
3. 要安裝成手機／平板 PWA，請把所有檔案放到 HTTPS 網站（例如 GitHub Pages）。網站部署後用 Safari／Chrome 開啟並加入主畫面。
4. 資料存在各裝置的瀏覽器 localStorage，不會自動跨裝置同步。請定期匯出 JSON 備份。
5. 行情功能嘗試讀取 TWSE MIS 公開行情端點，服務可能延遲、限流或因跨網域限制失敗；失敗時請以券商報價為準。
6. 進出場評分是透明的技術條件規則，不是保證準確的 AI 預測，也不會下單。若要真正 AI 模型或穩定即時行情，需另接合法資料/API 服務並保護 API 金鑰。
7. 手續費率、折扣、證交稅可在設定頁調整，請核對國泰證券實際費率。
