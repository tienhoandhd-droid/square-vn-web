# Square VN – Bàn biên tập

Giao diện web điều khiển bot đăng bài Binance Square (`square-vn-bot`, repo private).

- Trang này **chỉ chứa giao diện**: không có dữ liệu, mật khẩu hay token.
- Muốn xem nội dung phải **đăng nhập**. Lần đầu trên mỗi thiết bị, bạn đặt email và mật khẩu rồi dán GitHub token một lần. Token được mã hoá bằng mật khẩu (PBKDF2 + AES-GCM) và chỉ lưu trên thiết bị đó.
- Mọi dữ liệu được đọc trực tiếp từ repo private qua GitHub API, bằng token của bạn.

Bật web: **Settings → Pages → Deploy from a branch → `main` / `(root)`**.
Thêm vào màn hình chính điện thoại: mở web bằng Safari/Chrome → *Chia sẻ* → *Thêm vào MH chính*.
