# MeeGame

Source của [meegame.shop](https://meegame.shop) — trang gom link game web, kèm 2 game tự làm.

| Thư mục | Nội dung |
|---|---|
| `web/` | Trang tĩnh: `index.html` (trang chủ), `admin.html`, `games-seed.js`, `categories.js`, `titles-en.js`, `config.js` |
| `web/quanlau/` | Game **Lẩu Ơi!** — [meegame.shop/quanlau](https://meegame.shop/quanlau/) |
| `web/xoailac/` | Game **Xoài Lắc Ơi!** — [meegame.shop/xoailac](https://meegame.shop/xoailac/) |
| `app/` | API Python (`meegame_api.py`, SQLite) — `api.meegame.shop` |
| `covers-sync/` | Job đồng bộ ảnh bìa game (chạy cron 5 phút/lần) |
| `compose.yml`, `web.conf` | Docker Compose + cấu hình nginx |
| `sao-luu.sh` | Sao lưu SQLite hằng đêm |

Khoá bí mật (`JEV_API_KEY`, mật khẩu admin…) không nằm trong repo — chúng ở `/etc/meegame/` trên máy chủ và được đọc qua biến môi trường.
