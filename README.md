# 🎓 Academic Elegance - Trang Web Mời Tốt Nghiệp Cá Nhân

Trang web mời tham dự lễ tốt nghiệp trực tuyến được thiết kế theo phong cách **"Commencement Couture"** (Nét đẹp học thuật sang trọng & Tactile Luxury). Dự án kết hợp hài hòa giữa sự trang nghiêm của buổi lễ tốt nghiệp và cảm giác tinh tế, ấm áp của một tấm thiệp mời vật lý cao cấp.

Trang web được thiết kế riêng cho buổi lễ tốt nghiệp của **Nguyễn Thị Hương** vào ngày **18.07.2026** tại **Trường Đại học Công nghệ Đông Á**.

---

## ✨ Tính Năng & Trải Nghiệm Nổi Bật

- 💌 **Hiệu Ứng Mở Phong Bì Thiệp Mời (Interactive Envelope Reveal):** Màn hình mở đầu trực quan mô phỏng một chiếc phong bì thiệp mời thực tế. Người xem nhấp vào dấu sáp đóng dấu (`Wax Seal`) để mở phong bì, kích hoạt âm nhạc và hiệu ứng trượt mở 3D sống động trước khi bước vào không gian trang chính.
- 🌸 **Thiết Kế Đậm Chất Nghệ Thuật (Tactile Luxury & Minimalist Editorial):** Sự kết hợp giữa chất liệu giả lập giấy cotton thô (`paper-texture`), khung ảnh Polaroid đặt nghiêng tự nhiên, họa tiết hoa peony mềm mại và các chi tiết điểm xuyết ánh kim sang trọng.
- ✨ **Hệ Thống Hạt Cánh Hoa & Đốm Sáng Lấp Lánh (Atmospheric Petals & Sparkles):** Hiệu ứng cánh hoa bay lãng mạn và ánh sao lấp lánh phát sáng tự nhiên, được tối ưu hoàn toàn bằng Vanilla JavaScript, mang lại cảm giác sống động và cuốn hút cho trang web.
- 📸 **Scrapbook & Masonry Grid + Lightbox Thông Minh:** Bố cục trưng bày hình ảnh linh hoạt. Người xem có thể nhấp trực tiếp vào bất kỳ "Snapshot ngày thường" nào để mở **Lightbox**, xem chi tiết ảnh ở độ phân giải cao, đọc chú thích và chuyển tiếp dễ dàng bằng phím mũi tên hoặc chuột.
- 💬 **Gửi Lời Chúc & Xác Nhận Tham Gia (RSVP & Wish Modals):** Tích hợp hai biểu mẫu tương tác với giao diện kính mờ (`backdrop-blur`) giúp khách mời dễ dàng gửi lời chúc mừng tốt đẹp hoặc xác nhận sự hiện diện (RSVP) chỉ với vài thao tác.
- 📊 **Đồng Bộ Google Sheets & LocalStorage Theo Thời Gian Thực:** Kết nối sẵn sàng với **SheetDB API** để tự động lưu thông tin lời chúc và xác nhận tham gia trực tiếp lên Google Sheets. Đồng thời có cơ chế lưu trữ cục bộ (`localStorage`) dự phòng kèm thông báo Toast & Modal cảm ơn sang trọng.
- 🎵 **Đĩa Nhạc Vinyl Tương Tác:** Trình phát nhạc nền (`music.mp3`) với nút xoay mô phỏng đĩa than cổ điển. Tích hợp cơ chế tự động phát thông minh (`Autoplay Fallback`) xử lý mượt mà việc trình duyệt chặn tự động phát âm thanh khi người dùng tương tác lần đầu với trang web.
- 🗺️ **Bản Đồ & Thông Tin Địa Điểm Trực Quan:** Nhúng trực tiếp Google Maps Iframe đến địa điểm tổ chức (**Trường Đại học Công nghệ Đông Á - Trịnh Văn Bô, Hà Nội**) cùng các thông tin về ngày, giờ, hướng dẫn di chuyển tiện lợi.
- 🎬 **Hiệu Ứng Cuộn Trang Mượt Mà (Scroll Reveal & Lazy Loading):** Tối ưu hóa tải ảnh và hiệu ứng hiện dần trơn tru nhờ sử dụng công nghệ `IntersectionObserver`.
- 📱 **Responsive Hoàn Hảo Mọi Thiết Bị:** Hiển thị sắc nét, hài hòa từ màn hình máy tính rộng lớn đến điện thoại di động cầm tay.

---

## 🎨 Hệ Thống Thiết Kế (Design System)

Chi tiết thiết kế được xây dựng và tuân thủ theo đặc tả trong [DESIGN.md](DESIGN.md):

- **Màu Sắc Chủ Đạo:**
  - `Primary` (Hồng phấn/Blush - `#7b5455`): Tạo nên sự ấm áp, tinh tế và trang nhã.
  - `Secondary` (Vàng Champagne/Gold - `#735c00`): Điểm xuyết cho các chi tiết đặc biệt như khung viền, nhãn nhấn, nút bấm.
  - `Background` (Kem Giấy/Paper - `#fbf9f8`): Màu nền ấm áp mô phỏng bề mặt giấy mỹ thuật cao cấp.
  - `Neutral` (Than chì/Charcoal - `#1b1c1c`): Đảm bảo độ tương phản cao và rõ nét cho văn bản.
- **Phông Chữ (Typography):**
  - **Tiêu đề:** `Playfair Display` (Font serif cổ điển, trang trọng, mang đậm phong cách học thuật).
  - **Nội dung chính:** `Source Sans 3` (Font sans-serif hiện đại, thanh thoát, dễ đọc).
  - **Nhãn/Nút bấm:** `Montserrat` (Chữ in hoa với khoảng cách ký tự rộng, hiện đại và sang trọng).

---

## 📁 Cấu Trúc Dự Án

```text
├── index.html         # Trang HTML chính chứa toàn bộ giao diện Tailwind CSS, hiệu ứng & logic JavaScript
├── DESIGN.md          # Đặc tả hệ thống thiết kế (Design System specification)
├── README.md          # Tài liệu hướng dẫn dự án (File này)
├── music.mp3          # Nhạc nền định dạng MP3 cho thiệp mời
├── screen.png         # Ảnh preview giao diện trang web
└── media/             # Thư mục lưu trữ hình ảnh (ảnh chân dung, snapshot polaroid, ảnh sự kiện...)
```

---

## 🛠️ Công Nghệ Sử Dụng

- **HTML5 & Vanilla JavaScript (ES6+):** Xây dựng cấu trúc và logic tương tác mượt mà, không phụ thuộc vào framework nặng nề.
- **Tailwind CSS (CDN version):** Kết hợp các plugin `forms`, `container-queries` và custom theme trực tiếp trong HTML để tạo giao diện nhanh chóng, linh hoạt.
- **Google Fonts:** Tải động bộ phông chữ (`Playfair Display`, `Source Sans 3`, `Montserrat`).
- **Material Symbols Outlined:** Hệ thống biểu tượng sắc nét, tinh tế từ Google.
- **IntersectionObserver API & Web Audio API:** Quản lý hiệu ứng cuộn trang và âm thanh tối ưu hiệu năng.
- **SheetDB REST API:** Cầu nối API trực tiếp để lưu trữ dữ liệu biểu mẫu lên Google Sheets.

---

## 🚀 Hướng Dẫn Khởi Chạy & Cấu Hình

### 1. Khởi Chạy Trang Web

Trang web được xây dựng dưới dạng Single Page Application gọn nhẹ. Bạn có thể khởi chạy theo các cách sau:

- **Cách khuyên dùng (Với VS Code Live Server):**
  1. Cài đặt tiện ích mở rộng **Live Server** trên Visual Studio Code.
  2. Nhấp chuột phải vào file `index.html` và chọn **Open with Live Server**.
  3. Trình duyệt sẽ mở trang web tại địa chỉ nội bộ (ví dụ: `http://127.0.0.1:5500/index.html`). Toàn bộ tính năng mở phong bì, phát âm thanh và bản đồ sẽ hoạt động trơn tru nhất.
- **Mở trực tiếp:**
  - Nhấp đúp chuột vào file `index.html` để mở bằng trình duyệt (Chrome, Safari, Edge, Firefox). *(Lưu ý: Một số chính sách bảo mật CORS của trình duyệt đối với tệp `file://` có thể hạn chế nhúng Google Maps hoặc Autoplay âm thanh).*

### 2. Cấu Hình Lưu Lời Chúc & RSVP Lên Google Sheets (SheetDB)

Để thông tin khách mời gửi từ biểu mẫu **Gửi Lời Chúc** và **Xác Nhận Tham Gia** tự động được lưu vào bảng tính Google Sheets của bạn:

1. Tạo một trang tính **Google Sheets** mới và đặt tên cho các cột ở hàng đầu tiên (Header row) gồm:
   - `type` (Loại: wish / rsvp)
   - `name` (Tên người gửi)
   - `message` (Lời chúc)
   - `timestamp` (Thời gian gửi)
2. Truy cập [SheetDB.io](https://sheetdb.io/), đăng nhập và kết nối với file Google Sheets vừa tạo để lấy **API URL**.
3. Mở file `index.html`, tìm đến dòng **1277** và dán URL API của bạn vào biến `SHEETDB_API_URL`:
   ```javascript
   const SHEETDB_API_URL = "https://sheetdb.io/api/v1/mã_api_của_bạn_tại_đây";
   ```
   *(Nếu để trống `""`, hệ thống sẽ mặc định lưu trữ cục bộ vào `localStorage` của trình duyệt).*

---

## 📄 Bản Quyền & Lời Cảm Ơn

Dự án được tạo ra với trọn vẹn sự chăm chút và tâm huyết nhằm lưu giữ những kỷ niệm quý giá trong buổi lễ tốt nghiệp của lớp 2026. Xin chân thành cảm ơn và chúc mừng tân cử nhân!
