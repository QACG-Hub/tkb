# TKB - Thời khóa biểu sinh viên

Ứng dụng quản lý thời khóa biểu sinh viên.

## Tính năng

- **Theo Ngày / Cả Tuần**: xem lịch học theo ngày hoặc cả tuần.
- **Bảng TKB**: bảng dữ liệu đầy đủ 16 cột (TT, Lớp, Sĩ số, Tên học phần, Số TC, Tổng số tiết, Buổi, Thứ, Tiết, Từ ngày, Đến ngày, Phòng học, Đơn vị, Giảng viên, Hình thức thi, Ghi chú). Gom nhóm theo môn, tự sắp xếp Sáng → Chiều → Tối.
- **Quét Ảnh AI**: đọc ảnh thời khóa biểu (OCR) — mỗi buổi học tách thành một dòng riêng.
- **Quản Lý Môn**: thêm / sửa / xóa môn, một môn gồm nhiều buổi.
- Lưu dữ liệu trong `localStorage` của trình duyệt.

## Cấu trúc

| File | Vai trò |
|------|---------|
| `index.html` | Giao diện |
| `style.css` | Định dạng |
| `script.js` | Toàn bộ xử lý |

Mở trực tiếp `index.html` bằng trình duyệt để dùng.
