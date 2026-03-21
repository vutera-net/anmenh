# Implementation Plan - Phase 4: Bát Tự & Khả Năng Mở Rộng

Phase 3 đã hoàn thành xuất sắc việc xây dựng nền tảng vững chắc cho logic tử vi (áp dụng lịch Hồ Ngọc Đức chuẩn Việt Nam), cũng như hoàn thiện trải nghiệm UX/UI (Dark Mode, Framer Motion, Dashboard Hàng Ngày). 

Bước tiếp theo (Phase 4) sẽ tập trung vào các tính năng học thuật sâu hơn.

## Proposed Changes

### 1. Module Bát Tự Tứ Trụ
- [ ] Xây dựng thuật toán an lá số Bát Tự (Can Chi của Năm, Tháng, Ngày, Giờ).
- [ ] Biểu đồ Radar đánh giá trạng thái Ngũ Hành (Kim, Mộc, Thủy, Hỏa, Thổ) - Khuyết / Vượng.
- [ ] Phân tích tổng quan vòng trường sinh và Thập Thần.

### 2. Xem Tuổi Tương Hợp Đôi Lứa
- [ ] Form nhập liệu kép cho 2 người (Nam/Nữ).
- [ ] Logic đối chiếu Thiên Can, Địa Chi (Tam hợp, Lục hợp, Tứ hành xung) và Cung Phi bát trạch.
- [ ] Tính toán điểm tương hợp (%) và đưa ra lời khuyên.

### 3. Tối ưu Hệ Thống & Performance
- [ ] Tách nhỏ `lunar-logic.ts` thành cấu trúc folder modular (nếu tệp trở nên quá lớn).
- [ ] Đóng gói Web App dưới dạng PWA (Progressive Web App) để cài đặt offline trên thiết bị di động.
