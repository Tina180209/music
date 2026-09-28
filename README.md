# 淯婷琵琶教室

淯婷老師的琵琶家教網站：老師介紹、演出影片、課程與價格、免費線上試聽預約。

## 檔案說明

| 檔案 | 內容 |
|---|---|
| `index.html` | 整個網站（首頁、課程、經歷、預約四個分頁），照片已內建在裡面 |
| `hero.jpg` | 首頁主視覺照片 |
| `avatar.jpg` | 經歷頁大頭貼 |
| `poster.jpg` | 「知音逢汕」音樂會海報 |

## 用 GitHub Pages 上線

1. 登入 GitHub，按右上角 **+ → New repository**，名稱例如 `yuting-pipa`，選 **Public**，按 **Create repository**。
2. 在新的 repository 頁面按 **uploading an existing file**，把全部檔案拖進去（檔名要剛好是 index.html），按 **Commit changes**。
3. 到 **Settings → Pages**，Source 選 **Deploy from a branch**，Branch 選 **main**、資料夾選 **/(root)**，按 **Save**。
4. 等 1～2 分鐘，網址會是：`https://tina180209.github.io/music/`

## 常改的地方（在 `index.html` 裡搜尋）

- **開放預約的日期**：搜尋 `const OPEN=`。
  - 整天可以：`"2026-11-02":null`
  - 只有晚上：`"2026-11-04":[["19:00","20:00"]]`
- **整天的時段範圍**：搜尋 `const FULLDAY=`。
- **課程與價格**：搜尋 `const COURSES=`。
- **老師的 LINE ID**：搜尋 `id="lineId"`，把「（待補）」換成你的 ID。
- **演出影片**：搜尋 `class="vid"`。
