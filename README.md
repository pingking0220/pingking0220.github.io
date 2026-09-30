# 力行國小行政服務入口

https://pingking0220.github.io/ — 各行政系統的入口頁（靜態頁，不需登入）。

| 系統 | 網址 | 原始碼 |
|---|---|---|
| 場地預約 | https://pingking0220.github.io/venue-booking/ | pingking0220/venue-booking |
| 頒獎典禮座位預約 | https://pingking0220.github.io/award-seating/ | pingking0220/award-seating |

新增系統時，在 `index.html` 的 `.cards` 裡複製一張卡片，改圖示、名稱、說明與連結即可。
兩個系統共用 Firebase 專案 `award-seat` 與學校 Google 帳號登入。
