FIREPASS PROTOTYPE V4 — ROUND 2 USER TESTING
===========================================

Mục đích: Bản nâng cấp trực tiếp từ project FIREPASS V3. Giữ giao diện, logo, bộ màu và tài liệu mẫu V3; điều chỉnh UX theo feedback vòng 1.

CÁCH MỞ
1. Giải nén FIREPASS_Prototype_V4_Round2.zip.
2. Double-click index.html, mở bằng Chrome, Edge hoặc Safari.
3. Toàn bộ prototype chạy OFFLINE — không cần server hoặc tài khoản.
4. Có thể gửi ZIP cho nhóm hoặc người test, họ giải nén và mở index.html.

CHÚ Ý VỀ DỮ LIỆU
- Dữ liệu, chữ ký và trạng thái checklist thử nghiệm chỉ lưu trong localStorage của trình duyệt ĐANG SỬ DỤNG; không đồng bộ giữa các thiết bị.
- Mở trên máy khác không thấy dữ liệu của máy ban đầu.
- File/ảnh upload: demo chỉ lưu TÊN TỆP và trạng thái, không upload dữ liệu thực lên máy chủ.
- QR, thanh toán, thông báo, hỗ trợ, đăng nhập: chỉ giả lập.
- Nên dùng dữ liệu giả; không nhập thông tin cá nhân nhạy cảm hoặc giấy tờ PCCC thật trong buổi test.

FLOW BAN QUẢN LÝ
Trang chủ → Ban quản lý tòa nhà → Hồ sơ PCCC áp dụng → Checklist 6 phần (theo thứ tự)
→ Tổng hợp (Đạt / Chưa đạt / Chưa xác định) → Tóm tắt dịch vụ
→ Hợp đồng đầy đủ (chỉ 1 checkbox đồng ý) → Thanh toán Demo → Ký hợp đồng
→ Kích hoạt (chỉ mở nếu không còn mục chưa đạt/chưa xác định) → Thiết lập 7 hạng mục → Dashboard.

Lưu ý:
- Có thể chọn “Chưa đạt” / “Chưa xác định”, lưu nháp, tiếp tục checklist và xem tóm tắt dịch vụ.
- Checklist chưa hoàn thiện thì KHÔNG kích hoạt phần hướng dẫn cư dân.
- “Xem Dashboard Demo” nằm trong màn hình thiết lập tòa nhà và “Tổng quan” trong menu của khu vực Ban quản lý, không bắt buộc đi hết checklist.
- Phí dịch vụ chỉ hiển thị XXX, không phải báo giá thật.
- Bản hợp đồng được trình bày thành HTML dễ đọc trên mobile, nội dung dựa trên DOCX gốc trong ZIP.

FLOW CƯ DÂN
Trang chủ → Cư dân tòa nhà → Chọn phòng 608 (hoặc phòng khác)
→ Module 1 (Sơ đồ & lối thoát) → Micro-quiz 1
→ Module 2 (Thiết bị PCCC) → Micro-quiz 2
→ Module 3 (Tình huống khẩn cấp) → Micro-quiz 3
→ Hoàn thành 3/3 → Xác nhận 1 checkbox + chữ ký
→ Xem trước bản xác nhận → Xác nhận → Hoàn thành
→ Thông tin an toàn của tôi (truy cập nhanh không học lại).

HỖ TRỢ
Trang Hỗ trợ: yêu cầu hỗ trợ, mô phỏng hotline, báo lỗi hệ thống bằng modal, hướng dẫn (demo).

QUAN TRỌNG VỀ AN TOÀN / PHÁP LÝ
- FIREPASS không tự chứng nhận tòa nhà đạt chuẩn PCCC, không phải dịch vụ kiểm định.
- Sơ đồ, lối thoát, vị trí thiết bị và bài học là thông tin MINH HỌA, chưa xác minh tại công trình thực tế.
- Module 3 và phần kỹ thuật sử dụng thiết bị có placeholder chờ rà soát nội dung bởi nguồn/cơ quan chuyên môn có thẩm quyền.
- Không dùng hướng dẫn placeholder trong tình huống cháy thật.
- Chữ ký demo không có xác thực danh tính hoặc giá trị pháp lý mặc định.
- Hợp đồng mẫu chưa được luật sư rà soát để dùng thương mại.

TRONG ZIP
- index.html: ứng dụng V4 hoàn chỉnh, chạy độc lập với các asset được nhúng.
- firepass-favicon.png: biểu tượng tab.
- FIREPASS_Hop_dong_dich_vu_Mau.docx: mẫu hợp đồng gốc.
- FIREPASS_Bien_ban_xac_nhan_Mau.docx: biên bản gốc.
- source/v4_revision.js: phần JavaScript nâng cấp V4, đã được nhúng trong index.html; KHÔNG cần tải riêng khi chạy.
- CHANGELOG_V4.md: mô tả những gì đã sửa và còn giả lập.
- TEST_ROUND2.txt: checklist kiểm thử vòng 2.
