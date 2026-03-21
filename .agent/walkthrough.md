# Walkthrough - Harmony TuVi (Hoàn tất Phase 3)

Ứng dụng Harmony TuVi đã bước qua giai đoạn hoàn thiện giao diện cơ bản và chính thức sở hữu bộ máy tính toán tử vi tiên tiến, mang lại trải nghiệm cá nhân hóa sâu sắc theo đúng triết lý "Zen".

## Các tính năng nổi bật đã hoàn thành

### 1. Dashboard "Tử Vi Hôm Nay" cá nhân hóa
- Ngay khi người dùng khởi tạo hồ sơ (Họ tên, Năm sinh, Giới tính), hệ thống lưu trữ an toàn bằng `LocalStorage`.
- Trang chủ chuyển đổi thành một Dashboard cung cấp "Lời khuyên trong ngày", đánh giá thang điểm "Năng lượng", chỉ định "Hướng xuất hành", "Màu sắc", "Con số", và "Giờ hoàng đạo" phụ thuộc hoàn toàn vào tuổi thực của người dùng.

### 2. Nâng cấp Engine Lịch Âm & Lịch Vạn Niên
- Ứng dụng tích hợp thuật toán lịch âm chuẩn nhất (dựa trên nghiên cứu của Hồ Ngọc Đức), tự động xử lý các tháng nhuận, can chi một cách chuẩn xác cho múi giờ Việt Nam.
- Giao diện `Calendar` cho phép lọc nhanh các ngày Hoàng Đạo (tốt lành) và Hắc Đạo (xấu). Bấm vào từng ngày sẽ có popup modal hiển thị chi tiết Giờ Hoàng Đạo trong ngày và tư vấn việc nên làm.

### 3. Cân Xương Đoán Số Toàn Diện
- Form nhập đầy đủ tương tác nhanh theo Năm/Tháng/Ngày/Giờ Dương Lịch, tự động quy chiếu Can Chi tương ứng.
- Bảng luận giải được chia ra làm 4 cấp độ mệnh (Đại Phú Quý, Thượng Thượng, Bình Hòa, Thử Thách) với các panel Badge mang theme màu độc lập (Vàng, Xanh, Xám...), phân tích cực kỳ chi tiết từ văn phong cổ học.

### 4. La Bàn Bát Trạch Tương Tác
- Sử dụng thuật toán chuẩn xác để tính "Cung Phi", "Bản Mệnh" (Đông/Tây Tứ Mệnh).
- La bàn ảo được dựng bằng `framer-motion` mượt mà - Trục la bàn xoay chính xác tới vĩ độ của Cung phi, đi kèm các Highlight UI rõ ràng giúp người xem nhận biết hướng đại cát (Sinh Khí) hay hướng kỵ (Tuyệt Mệnh). Kèm lời khuyên thực tế về kê giường/kê trạch.

### 5. Tối ưu Giao diện Theme Bóng Tối (Dark Mode)
- Dark Mode được tinh chỉnh đến mức cao cấp (Mystical Modern). Các background màu nền và glassmorphism ứng dụng sâu rộng kết hợp cùng các thẻ tương tác tạo nên hệ thống Design System chuyên nghiệp, huyền bí phù hợp với triết học phương Đông.
