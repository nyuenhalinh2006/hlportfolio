# 🍍 HƯỚNG DẪN TÙY CHỈNH & XUẤT BẢN PORTFOLIO BIKINI BOTTOM

Chào bạn! Dưới đây là hướng dẫn chi tiết cách quản lý hình ảnh, âm thanh và đưa trang web lên Internet.

---

## 1. 📸 CÁCH THAY ẢNH ĐẠI DIỆN (AVATAR)

Ảnh đại diện hiện tại đã được liên kết trực tiếp với ảnh chân dung của bạn và lưu tại:
📁 `assets/images/avatar.jpg`

Khi bạn muốn thay bằng một bức ảnh mới:
1. Chuẩn bị file ảnh chân dung mới (định dạng JPG hoặc PNG).
2. Đổi tên file ảnh đó thành `avatar.jpg`.
3. Chép đè (ghi đè) vào thư mục `assets/images/avatar.jpg`.
4. Mở lại trình duyệt và tải lại trang (`Ctrl + F5` hoặc `Shift + F5`) để xem ảnh mới.
*Giao diện đã được thiết kế sẵn thuộc tính `object-fit: cover` và tỷ lệ khung hình tự nhiên, đảm bảo ảnh luôn sắc nét, không bị méo mặt hay kéo dãn.*

---

## 2. 🎵 CÁCH THAY NHẠC NỀN BIKINI BOTTOM

Hệ thống âm thanh của portfolio hỗ trợ **cả file MP3 riêng và bộ giả lập Ukulele nhiệt đới tự động**:
1. Chuẩn bị file nhạc yêu thích (ví dụ bài nhạc nền SpongeBob Hawaii Ukulele tải về dưới dạng `.mp3`).
2. Đổi tên file thành `spongebob_theme.mp3`.
3. Đặt file vào thư mục:
   📁 `assets/audio/spongebob_theme.mp3`
4. Khi mở trang web và bấm nút **"▶️ Phát Nhạc"**, trình duyệt sẽ tự động phát file nhạc này của bạn. Nếu chưa có file mp3, website sẽ tự động kích hoạt bộ giả lập Ukulele Hawaii êm dịu có sẵn.

---

## 3. 🚀 CÁCH XUẤT BẢN PORTFOLIO LÊN INTERNET (MIỄN PHÍ)

### Cách 1: Xuất bản miễn phí với Vercel (Khuyên dùng - Nhanh nhất)
1. Truy cập [vercel.com](https://vercel.com) và đăng nhập (bằng tài khoản GitHub hoặc Google).
2. Kéo thả toàn bộ thư mục `halinh-spongebob-portfolio` vào màn hình Vercel.
3. Bấm **Deploy**. Sau 10 giây, bạn sẽ nhận được một đường link trực tuyến (ví dụ: `halinh-portfolio.vercel.app`) để gửi cho bạn bè hoặc nhà tuyển dụng!

### Cách 2: Xuất bản bằng GitHub Pages
1. Tạo một repository mới trên [github.com](https://github.com) (ví dụ: `halinh-portfolio`).
2. Tải toàn bộ các file trong thư mục `halinh-spongebob-portfolio` lên repository đó (bao gồm `index.html`, thư mục `assets/`...).
3. Vào mục **Settings** của repository ➔ Chọn tab **Pages** (bên trái).
4. Tại mục **Branch**, chọn `main` (hoặc `master`) và bấm **Save**.
5. Sau 1 - 2 phút, GitHub sẽ cấp cho bạn một đường link miễn phí dạng: `https://<ten-github-cua-ban>.github.io/halinh-portfolio`.

### Cách 3: Chạy cục bộ bằng Live Server trong VS Code
1. Mở thư mục `halinh-spongebob-portfolio` bằng VS Code.
2. Cài đặt tiện ích mở rộng **Live Server** (của Ritwick Dey).
3. Nhấp chuột phải vào file `index.html` và chọn **"Open with Live Server"**.

---

## 🏠 CẤU TRÚC THƯ MỤC DỰ ÁN

```text
halinh-spongebob-portfolio/
│
├── index.html                   # Mã nguồn giao diện chính khu phố Bikini Bottom
├── server.js                    # Máy chủ Node.js cục bộ
├── README.md                    # Tài liệu tổng quan
├── HUONG_DAN_SU_DUNG.md         # Hướng dẫn chi tiết này
│
└── assets/
    ├── images/
    │   └── avatar.jpg           # Ảnh đại diện cá nhân của bạn
    └── audio/
        └── spongebob_theme.mp3  # File nhạc nền (tùy chọn đặt thêm)
```
