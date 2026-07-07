# BHD Star Seat Booking System 2026

Hệ thống đặt vé và tính tiền trực quan cho các phòng chiếu BHD Star Lê Văn Việt 2026.

## Tính Năng Nổi Bật

- **Sơ đồ ghế tự động:** Hiển thị sơ đồ ghế chính xác theo từng phòng chiếu (Screen 1 - Screen 6).
- **Phân loại ghế thông minh:** Hỗ trợ Ghế Thường, Ghế VIP, Ghế Đôi với mức giá và phụ thu tương ứng.
- **Giá vé linh hoạt theo nhóm:** Cho phép người dùng gán loại đối tượng khách hàng riêng biệt (Người lớn, U22 / HSSV, Trẻ em) cho từng ghế trong nhóm đặt vé để tính giá vé riêng từng người cực kỳ chính xác.
- **Phụ thu dịch vụ:** Hỗ trợ tính thêm phụ thu phim 3D và các dịp Lễ Tết/Bom tấn.
- **Xuất hóa đơn trực quan:** Tạo hóa đơn dạng Ticket Card đẹp mắt với mã vạch (barcode) và hỗ trợ tải xuống dưới dạng hình ảnh JPG.
- **Xuất sơ đồ ghế:** Tải sơ đồ phòng chiếu với trạng thái các ghế đã chọn dưới dạng ảnh PNG.

## Deploy lên GitHub Pages

Dự án này đã được cấu hình tự động triển khai (deployment) lên **GitHub Pages** bằng **GitHub Actions**.

### Cách kích hoạt GitHub Pages trên Repository của bạn:

1. Đẩy code lên repository GitHub của bạn (`main` branch).
2. Truy cập vào trang GitHub của repository đó, chọn tab **Settings** (Cài đặt).
3. Chọn mục **Pages** ở thanh menu bên trái.
4. Tại phần **Build and deployment** (Xây dựng và triển khai):
   - Mục **Source** (Nguồn), đổi từ *Deploy from a branch* sang **GitHub Actions**.
5. Sau khi đổi, quy trình deployment sẽ tự động chạy trong tab **Actions** và trang web sẽ hiển thị trực tuyến tại đường dẫn GitHub Pages của bạn!
