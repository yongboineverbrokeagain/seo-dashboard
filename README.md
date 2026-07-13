# SEO Performance Monitor Dashboard

Tự động đọc dữ liệu từ Google Sheets, hiển thị dashboard SEO với scorecards, charts, keyword ranking, backlinks overview và watchlist alerts.

## Cách dùng

1. Publish Google Sheets ra web (File → Share → Publish to web → CSV)
2. Mở dashboard → Click ⚙ Config → Paste 3 URL vào
3. Apply & Refresh

## Cập nhật dữ liệu định kỳ

| Tần suất | Sheet | Nội dung |
|----------|-------|----------|
| Hàng tháng | `Monthly_Summary` | Sessions, Clicks, CTR, Position từ GSC/GA4 |
| Hàng tuần | `Backlinks` | Paste Ahrefs CSV export |
| Khi cần | `Watchlist` | Cập nhật vị trí keyword hiện tại |
