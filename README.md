# Hội Nhập Cùng Scots English — Quiz Trực Tiếp

Game quiz trực tiếp (kiểu Kahoot) dùng để ôn tập kiến thức onboarding cho nhân sự mới tại Scots English.

## Nội dung
18 câu hỏi trắc nghiệm bám sát chương trình "Hội nhập cùng Scots English" (Phòng Đào tạo HO), bao gồm:
- Thông tin chung & cột mốc phát triển
- Sứ mệnh, tầm nhìn, giá trị cốt lõi, triết lý giáo dục
- Tiêu chuẩn người Scots English (quy tắc ứng xử, 5S, nội quy họp)
- Chế độ chính sách & đãi ngộ

## Cách chơi
1. Giáo viên (Host) mở trang này, chọn **"Tạo phòng (Giáo viên/Host)"** để lấy mã phòng 4 số.
2. Học viên mở cùng trang này trên điện thoại/laptop, chọn **"Tham gia"**, nhập mã phòng + tên.
3. Giáo viên bấm **"Bắt đầu"** khi đủ người tham gia.
4. Mỗi câu hỏi có 20 giây, học viên chọn đáp án — điểm tính theo tốc độ trả lời.
5. Sau mỗi câu, giáo viên xem đáp án + bảng xếp hạng, rồi chuyển câu tiếp theo.
6. Kết thúc: bảng vinh danh Top 3 + bảng xếp hạng đầy đủ.

## Công nghệ
File HTML/JS thuần, dùng chung một trang cho cả giáo viên và học viên, đồng bộ trạng thái real-time qua persistent storage của Claude Artifacts (`window.storage`, shared mode).

**Lưu ý:** File này cần được mở qua Claude Artifact (link chia sẻ) để tính năng đồng bộ nhiều người chơi hoạt động — mở trực tiếp file `.html` offline sẽ không đồng bộ được giữa các thiết bị.

---
*Phát triển bởi Phòng L&D — Scots English*
