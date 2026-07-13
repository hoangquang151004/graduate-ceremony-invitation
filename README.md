# 🎓 Academic Elegance - Trang Web Mời Tốt Nghiệp Cá Nhân

Trang web mời tham dự lễ tốt nghiệp trực tuyến được thiết kế theo phong cách **"Commencement Couture"** (Nét đẹp học thuật sang trọng). Dự án kết hợp hài hòa giữa sự trang nghiêm của lễ tốt nghiệp và cảm giác tinh tế, ấm áp của một tấm thiệp mời vật lý cao cấp.

Trang web được thiết kế riêng cho buổi lễ tốt nghiệp của **Nguyễn Thị Hương** vào ngày **18.07.2026** tại **Trường Đại học Công nghệ Đông Á**.

---

## ✨ Tính Năng Nổi Bật

- 🌸 **Thiết Kế Đậm Chất Nghệ Thuật (Tactile Luxury & Minimalist Editorial):** Sử dụng các khung ảnh Polaroid nghiêng tự nhiên, chất liệu giả lập giấy cotton thô (`paper-texture`), các họa tiết hoa peony màu nước mềm mại và hiệu ứng ép kim vàng nhạt.
- 📸 **Scrapbook & Masonry Grid:** Bố cục trưng bày ảnh linh hoạt, hiển thị trọn vẹn những khoảnh khắc đời thường, ảnh chân dung học thuật và ảnh chụp cùng gia đình, bạn bè.
- 🔍 **Bộ Sưu Tập Ảnh Lightbox Thông Minh:** Người xem có thể nhấp vào các "Snapshot ngày thường" để phóng to ảnh, chuyển slide bằng phím mũi tên hoặc nhấp chuột, xem mô tả chi tiết cho từng tấm ảnh.
- 🎵 **Đĩa Nhạc Vinyl Tương Tác:** Trình phát nhạc nền (`music.mp3`) với nút bấm thiết kế giống như một đĩa than đang quay. Có cơ chế tự động phát thông minh (Autoplay Fallback) ngay khi người dùng tương tác lần đầu tiên với trang web để vượt qua chính sách chặn âm thanh của trình duyệt.
- 🗺️ **Bản Đồ Chỉ Đường Thực Tế:** Tích hợp Google Maps Iframe chỉ đường trực tiếp tới địa điểm tổ chức (Đại học Công nghệ Đông Á - Trịnh Văn Bô, Hà Nội).
- 🎬 **Hiệu Ứng Cuộn Trang Mượt Mà (Scroll Reveal):** Các thành phần giao diện sẽ trượt nhẹ và hiện dần lên khi cuộn trang nhờ công nghệ tối ưu `IntersectionObserver`.
- 📱 **Tương Thích Mọi Thiết Bị (Responsive Design):** Giao diện hiển thị hoàn hảo trên máy tính (lưới 12 cột) cũng như điện thoại di động (lưới 1 cột với khoảng cách thoáng đãng).

---

## 🎨 Hệ Thống Thiết Kế (Design System)

Chi tiết thiết kế được xây dựng dựa trên đặc tả trong [DESIGN.md](DESIGN.md):

- **Màu Sắc Chủ Đạo:**
  - `Primary` (Hồng phấn/Blush - `#7b5455`): Tạo nền tảng nữ tính, ấm áp.
  - `Secondary` (Vàng Champagne/Gold - `#735c00`): Điểm xuyết cho các chi tiết đặc biệt như khung viền, nhãn, nút bấm.
  - `Background` (Kem Giấy/Paper - `#fbf9f8`): Màu nền ấm mô phỏng bìa giấy mỹ thuật.
  - `Neutral` (Than chì/Charcoal - `#1b1c1c`): Đảm bảo độ tương phản cao cho chữ viết.
- **Phông Chữ (Typography):**
  - **Tiêu đề:** `Playfair Display` (Font serif cổ điển, trang trọng).
  - **Nội dung chính:** `Source Sans 3` (Font sans-serif hiện đại, dễ đọc).
  - **Nhãn/Nút:** `Montserrat` (Chữ in hoa, khoảng cách ký tự rộng tạo nét sang trọng).
- **Trang Trí:** Khung ảnh Polaroid đổ bóng nhẹ (`polaroid-frame`), nhãn dán giả băng keo Washi (`washi-tape`), hoa văn nghệ thuật (`material-symbols-outlined`).

---

## 📁 Cấu Trúc Dự Án

```text
├── code.html          # Trang HTML chính chứa cấu trúc, kiểu dáng Tailwind & JS logic
├── DESIGN.md          # Đặc tả hệ thống thiết kế (Design System specification)
├── music.mp3          # Nhạc nền định dạng MP3 cho trang web
├── screen.png         # Ảnh chụp màn hình giao diện
└── README.md          # Hướng dẫn dự án (File này)
```

---

## 🛠️ Công Nghệ Sử Dụng

- **HTML5 & Vanilla Javascript (ES6+)**
- **Tailwind CSS (CDN version)** cho việc xây dựng bố cục và responsive nhanh chóng
- **Google Fonts** (`Playfair Display`, `Source Sans 3`, `Montserrat`)
- **Material Symbols Outlined** cho hệ thống icon thanh lịch
- **IntersectionObserver API** cho hiệu ứng cuộn trang hiệu năng cao

---

## 🚀 Hướng Dẫn Chạy Dự Án

Trang web được thiết kế dạng Single Page Application thuần nên không cần cấu hình build phức tạp. Bạn có thể khởi chạy bằng các cách sau:

### Cách 1: Mở Trực Tiếp (Đơn Giản)
Nhấp đúp chuột vào file `code.html` để mở trực tiếp trên bất kỳ trình duyệt nào (Chrome, Safari, Edge, Firefox).

> [!NOTE]  
> Do chính sách bảo mật CORS của trình duyệt đối với tệp tin cục bộ (`file://`), tính năng nhúng Google Maps có thể hiển thị cảnh báo trên một số trình duyệt nếu chạy offline trực tiếp. Để trải nghiệm tốt nhất, bạn nên sử dụng **Cách 2**.

### Cách 2: Sử Dụng Live Server (Khuyên Dùng)
1. Nếu sử dụng VS Code, cài đặt extension **Live Server**.
2. Nhấp chuột phải vào `code.html` và chọn **Open with Live Server**.
3. Trang web sẽ chạy trên máy chủ nội bộ (ví dụ: `http://127.0.0.1:5500/code.html`). Âm nhạc và bản đồ sẽ hoạt động trơn tru.

---

## 📄 Bản Quyền & Giấy Phép

Dự án này được tạo ra để lưu giữ kỷ niệm tốt nghiệp lớp 2026. Vui lòng tôn trọng quyền sở hữu hình ảnh của nhân vật chính trong trang web.
