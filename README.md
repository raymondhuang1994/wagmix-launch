# WAGMIx Launch V35

WAGMIx Launch 是繁體中文及英文的單檔網站，包含品牌介紹、產品預告和聯絡頁。預設語言為繁體中文，可在頁首切換至英文。

## 部署

1. 從此倉庫下載 `index.html`。
2. 將檔案上傳至靜態網站的根目錄或獨立子目錄。以 `text/html; charset=utf-8` 提供檔案。
3. 在瀏覽器開啟該目錄，確認語言切換、產品預告及聯絡連結正常。

HTML 已內嵌圖片、字型、CSS 和 JavaScript，可直接部署至靜態主機，無需額外的構建步驟或後端。瀏覽器需啟用 JavaScript。

| 頁面 | 繁體中文 | English |
|---|---|---|
| 關於 WAGMIx | `/` | `/?lang=en` |
| 產品預告 | `/#/products` | `/?lang=en#/products` |
| 聯絡我們 | `/#/contact` | `/?lang=en#/contact` |

如部署至子目錄，請將上述路徑的根目錄替換為實際部署目錄。
