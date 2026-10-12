# BabyPlan 2030 🌷

Website MVP tiếng Việt dựa trên PRD BabyPlan 2030. Không cần cài đặt, không cần backend.

## Đăng website miễn phí lên GitHub Pages

1. Đăng nhập https://github.com và nhấn **New repository**.
2. Đặt tên repository là `babyplan2030`, chọn **Public**, nhấn **Create repository**.
3. Chọn **Add file → Upload files**, kéo thả file `index.html` và `README.md` trong thư mục này, rồi chọn **Commit changes**.
4. Mở **Settings → Pages**.
5. Trong **Build and deployment**, chọn **Deploy from a branch**, nhánh **main**, thư mục **/(root)**, nhấn **Save**.
6. Chờ GitHub triển khai; đường dẫn thường là `https://TEN-TAI-KHOAN.github.io/babyplan2030/` (thay TEN-TAI-KHOAN bằng tên tài khoản GitHub).

## Tính năng
- Dashboard tiến độ quỹ, tiêm chủng và bàn giao.
- Tạo/sửa mục tiêu tiết kiệm, thêm/sửa/xóa khoản tiết kiệm, dự toán chi phí.
- Ghi ngày tiêm và số tháng chờ **do bác sĩ xác nhận**, tính mốc tham khảo; không tự xác nhận đủ điều kiện thụ thai.
- Thêm/sửa/xóa và lọc công việc bàn giao bằng mã giả định.
- Checklist giấy tờ thai sản, vi chất và sao lưu/khôi phục JSON.

## Lưu ý quan trọng
- Đây là **bản demo một người dùng**, lưu dữ liệu bằng `localStorage` trên trình duyệt, **không có database server** hoặc đăng nhập. Dữ liệu không đồng bộ giữa các thiết bị, có thể mất khi xóa dữ liệu trình duyệt.
- GitHub Pages là website công khai: không nhập thông tin y tế cá nhân, thông tin khách hàng hoặc dữ liệu nội bộ thật.
- Không kết nối ngân hàng, bệnh viện, BHXH hay CRM. Nội dung sức khỏe và BHXH chỉ mang tính nhắc việc, cần xác minh với chuyên gia/cơ quan có thẩm quyền.
- Nếu cần tài khoản, cơ sở dữ liệu thực, phân quyền và đồng bộ nhiều thiết bị thì phải phát triển thêm backend và bảo mật.
