# Giỏ hàng trực tiếp — landing page prototype

Prototype giao diện (UX/UI) cho sản phẩm **Giỏ hàng trực tiếp** của iHouzz: màn LED sân khấu, kiosk và mã QR tại lễ mở bán, đồng bộ trạng thái căn từ PropSales.

## Xem thử

Mở `index.html` bằng trình duyệt, hoặc bật GitHub Pages cho nhánh `main` (Settings → Pages → Deploy from branch → `main` / root).

Trang là một file HTML tĩnh, không cần build. Font Manrope và Cormorant Garamond tải từ Google Fonts.

## Trạng thái

- Đây là **prototype**: form đăng ký chỉ chạy giao diện, chưa gửi dữ liệu đi đâu.
- Mã căn, diện tích và các con số trên trang là **minh hoạ**.
- Ảnh sự kiện trong `assets/` là ảnh thật của lễ mở bán The Privé; phần màn hình trong ảnh là mô phỏng ghép. **Cần xin phép chủ đầu tư và đơn vị tổ chức trước khi dùng công khai.**
- Giá các gói đang để chỗ trống `[GIÁ …]`.

## Cấu trúc

```
index.html                 trang landing (HTML + CSS + JS trong một file)
assets/ihouzz-logo.png     wordmark iHouzz
assets/ihouzz-icon.png     icon ứng dụng iHouzz
assets/su-kien-*.jpg       ảnh sự kiện dùng ở phần "Tại sự kiện"
assets/the-prive-phoi-canh.jpg   phối cảnh dự án (chưa dùng trong trang này)
```

## Các phần của trang

Hero (bảng giỏ hàng diễn quy trình chọn căn → giữ chỗ → sale xác nhận → đã cọc) · Vấn đề tại lễ mở bán · Cách hoạt động · Tại sự kiện (chọn góc, chạm điểm, bật/tắt lớp mockup) · Trải nghiệm khách 5 bước · Bốn mức tương tác · Đã xử lý sẵn · Hệ sinh thái iHouzz · Gói dịch vụ · Quy trình triển khai · Hỏi đáp · Form đăng ký trải nghiệm.
