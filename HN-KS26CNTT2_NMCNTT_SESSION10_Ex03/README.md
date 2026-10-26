# 5. Yêu cầu đầu ra
1. Phần I. Phân tích
- Giá trị 1: Mã vận đơn
- Giá trị 2: Bảng giá cước
- Giá trị 3: Cột cần lấy
- Giá trị 4: Khớp 100% với dòng trong bảng
2. Phần III. Kiểm thử
- Xử lý lỗi #N/A khi mã vận đơn có ký tự lạ bằng hàm IFERROR: `=IFERROR(VLOOKUP(B2;'Giá cước'!$A$1:$B$8;2;0);"Không tìm thấy")`
