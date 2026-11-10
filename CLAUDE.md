# CLAUDE.md – Square VN Web

Giao diện web (GitHub Pages) của bot `square-vn-bot`. Trả lời bằng tiếng Việt.

- Chỉ có `index.html` (HTML/CSS/JS thuần, không build) + `manifest.webmanifest` + `icon.svg`.
- Bản gốc nằm ở `square-vn-bot/docs/index.html`. Sửa ở đó rồi chép sang đây (hoặc ngược lại), để 2 bản luôn giống nhau.
- Repo này PUBLIC: **tuyệt đối không** ghi mật khẩu, token hay dữ liệu vào đây. Đăng nhập dùng token GitHub được mã hoá trên thiết bị (PBKDF2 + AES-GCM, localStorage `sqvn_vault`).
- `DEFAULT_REPO` trong `index.html` phải trỏ tới repo bot: `<tài-khoản>/square-vn-bot`.
- Phong cách: nền than chì `#17161c`, nhấn vàng champagne `#cdae6e`, tiêu đề Cormorant Garamond, nội dung Be Vietnam Pro. Máy tính có thanh bên, điện thoại có thanh điều hướng dưới đáy.
