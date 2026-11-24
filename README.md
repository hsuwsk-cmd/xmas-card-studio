# 聖誕 AI 創卡魔法屋

可直接部署到 GitHub Pages 的靜態網頁應用程式。

## 上傳步驟

1. 在 GitHub 建立一個新的 Public Repository，例如 `xmas-ai-card`。
2. 將本資料夾內的 `index.html` 上傳至 repository 根目錄。
3. 進入 **Settings → Pages**。
4. 在 **Build and deployment → Source** 選擇 **Deploy from a branch**。
5. Branch 選 `main`，資料夾選 `/ (root)`，按 **Save**。
6. 等待約 1–2 分鐘，網站會發布於：

   `https://你的GitHub帳號.github.io/倉庫名稱/`

## 使用 AI 生成功能

1. 開啟網站後，按右上角「🔑 設定課堂魔法金鑰」。
2. 貼上你自己的 Google AI Studio API Key。
3. 金鑰只會儲存在該瀏覽器的 localStorage，不會寫入此 GitHub repository。
4. 請不要將 API Key 寫入 `index.html` 或上傳到公開 repository。

## 檔案

- `index.html`：完整網頁應用程式
- `.nojekyll`：防止 GitHub Pages 執行 Jekyll 處理，確保以底線開頭的檔案可正常存取
