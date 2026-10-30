## Nhật ký xử lý

- Vấn đề: Network hiển thị trạng thái HTTP `304` khi tải tài nguyên.
- Kết quả: Đã xác định `304 Not Modified` là phản hồi cache bình thường, không phải lỗi ứng dụng; không cần sửa mã nguồn.
- Nếu trang vẫn hiển thị nội dung cũ: tải lại bằng `Ctrl + F5` hoặc bật `Disable cache` trong DevTools > Network rồi tải lại.
- Trạng thái: Đã kiểm tra và làm rõ nguyên nhân.

## Cập nhật sau sửa lỗi

- Đã chuẩn hóa liên kết CSS trong `ket-qua.html` thành đường dẫn tương đối `css/style.css` để hoạt động ổn định khi triển khai trên web/GitHub Pages.
- Kiểm tra: `ket-qua.html` không có lỗi phân tích.
- Trạng thái: Đã sửa và kiểm tra.
