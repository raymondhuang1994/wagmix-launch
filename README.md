# WAGMIx Launch V38

WAGMIx Launch 提供繁體中文和英文的品牌介紹、產品預告及聯絡頁。預設語言為繁體中文，可在頁首切換至英文。

## 部署

1. 從此倉庫下載 `index.html` 和 `og-image.png`，一起部署至 `https://wagmix.com/` 的靜態網站根目錄。
2. 確認首頁和 `https://wagmix.com/og-image.png` 可公開存取。首頁使用 `text/html; charset=utf-8`，圖片使用 `image/png`。
3. 將 `favicon.png` 上傳至 `index.html` 所在目錄，並確認瀏覽器標籤頁顯示藍色 X。
4. 用正式網址檢查分享預覽，並在瀏覽器驗證語言切換、產品預告及聯絡連結。

`index.html` 已內嵌網頁使用的圖片、字型、CSS 和 JavaScript，無需構建或後端。分享服務會另行讀取 `og-image.png`。瀏覽器需啟用 JavaScript。

如改用其他網域或子目錄，請更新 `index.html` 內的 `og:url`、`og:image` 和 `twitter:image`，使其指向實際公開網址。

| 頁面 | 繁體中文 | English |
|---|---|---|
| 關於 WAGMIx | `/` | `/?lang=en` |
| 產品預告 | `/#/products` | `/?lang=en#/products` |
| 聯絡我們 | `/#/contact` | `/?lang=en#/contact` |
