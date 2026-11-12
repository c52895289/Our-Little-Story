# 緒 ♡ 念 — OUR LITTLE STORY

雙人戀愛日記網站，行動裝置優先設計。

## 開啟

開啟 `index.html` 即可使用；本機版採用瀏覽器 `localStorage` 儲存，**不同裝置不會自動同步**。

## 部署到 GitHub Pages

1. 將本資料夾內的 `index.html`、`couple.jpg` 等檔案上傳至 Repository 根目錄（不要只上傳 ZIP）。
2. 在 GitHub Repository > Settings > Pages 選擇 `Deploy from a branch` > `main` > `/(root)`，儲存後等待 GitHub 顯示部署網址。
3. 注意：**即使 Repository 設為 Private，GitHub Pages 網站及圖片仍可能對公眾開放**。若不願公開合照，請勿啟用 Pages，改用支援登入保護的主機與儲存空間。

## 隱私與資料

- 未配置身分驗證、雲端資料庫與存取規則前，絕對不要將此站當成私密雙人同步日記使用。
- 本機資料儲存於同一台裝置、同一個瀏覽器中，清除瀏覽器網站資料可能造成紀錄遺失。
- 若要跨裝置同步與雙人存取，建議使用 Supabase 或 Firebase Auth + 資料庫權限控管，並測試未授權訪客無法讀取資料。
