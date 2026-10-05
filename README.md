# Track 1 — Day 19: Prototype & User Feedback

## Thông tin học viên và nhóm

- **Họ và tên:** Chu Thủy Dương
- **Mã học viên:** 2A202602660
- **Tên nhóm:** `3 in 1`
- **Thành viên nhóm:**
  - Chu Thủy Dương (2A202602660)
  - Lê Thanh Tình (2A202602449)
  - Phạm Hương Giang (2A202602359)
- **AI Feature Case đã chọn:** Case B — AI Notes: Personal Learning Notes

---

## Tóm tắt nội dung các tài liệu

| Tài liệu | Mô tả chi tiết | Liên kết |
| :--- | :--- | :--- |
| **Three-Option Design Sheet** | Bản thiết kế chi tiết 3 phương án giải pháp (Option A, B, C) dựa trên JTBD và Pain hypothesis từ Day 17; kèm link board thiết kế chung của nhóm. | [three-option-design-sheet.md](file:///e:/VIN_AI/Track1_Day19_2A202602660_ChuThuyDuong/three-option-design-sheet.md) |
| **Prototype Links** | Tập hợp các liên kết tương tác (Figma / v0 / Web demo) cho cả 3 phiên bản prototype A/B/C và hướng dẫn kịch bản chạy thử. | [prototype-link.md](file:///e:/VIN_AI/Track1_Day19_2A202602660_ChuThuyDuong/prototype-link.md) |
| **Prototype Feedback Note** | Biên bản ghi chép chi tiết phiên Usability Testing do chính học viên Chu Thùy Dương trực tiếp facilitate với người dùng (nhiệm vụ, quan sát hành vi, trích dẫn thực tế, rào cản). | [prototype-feedback-note.md](file:///e:/VIN_AI/Track1_Day19_2A202602660_ChuThuyDuong/prototype-feedback-note.md) |
| **Group Feedback Synthesis** | Báo cáo hội tụ kết quả từ tất cả các phiên thử nghiệm của nhóm 3 in 1; phân tích mẫu số chung, rủi ro AI UX và quyết định lựa chọn phương án phát triển tiếp theo. | [group-feedback-synthesis.md](file:///e:/VIN_AI/Track1_Day19_2A202602660_ChuThuyDuong/group-feedback-synthesis.md) |
| **AI Support Log** | Khai báo minh bạch phạm vi, mục đích và nội dung các lần tương tác với AI theo nguyên tắc liêm chính học thuật. | [ai-support-log.md](file:///e:/VIN_AI/Track1_Day19_2A202602660_ChuThuyDuong/ai-support-log.md) |

---

## Snapshot kết quả thử nghiệm và quyết định của nhóm

### 1. Vấn đề cốt lõi được kế thừa từ Day 17
- **Bối cảnh & JTBD:** Khi hoàn thành một bài học trực tuyến mới/phức tạp, học viên muốn nhanh chóng khôi phục ngữ cảnh và biến các dấu vết rời rạc thành tài liệu ôn tập hiệu quả để không phải đọc lại bài từ đầu.
- **Insight từ fieldwork:** Người học không chỉ cần một bản tóm tắt thụ động mà có nhu cầu cao về **Active Recall** (tự kiểm tra kiến thức) và giảm thiểu gián đoạn mạch học khi ghi chép.

### 2. Tóm tắt 3 phương án thiết kế (Three Options)
1. **Option A (Low AI / High User Control — Contextual Pinning & Tagging):** Người dùng tự đánh dấu và phân loại thủ công, AI chỉ gợi ý từ khóa và timeline ngữ cảnh.
2. **Option B (Balanced AI Co-pilot — Dual-Pane Interactive Canvas):** AI tự động tổ chức thông tin thành cấu trúc 2 cột song song; người dùng xem, chỉnh sửa trực tiếp và xác nhận trước khi lưu.
3. **Option C (High AI / Active Recall & Smart Quiz Engine):** AI phân tích highlights và điểm "Chưa hiểu" để tự động sinh flashcards và bộ câu hỏi trắc nghiệm ôn tập nhanh theo chu kỳ lặp lại ngắt quãng.

### 3. Quyết định lựa chọn của nhóm
- **Phương án được chọn:** **Phương án lai ghép (Hybrid: Option B + Option C)**.
- **Lý do:** Người dùng đánh giá cao tính minh bạch và khả năng kiểm soát bản nháp của Option B (Dual-Pane Canvas), đồng thời rất hào hứng với cơ chế chuyển hóa ghi chú thành bài tập trắc nghiệm tự kiểm tra của Option C (Active Recall). Nhóm quyết định giữ khung chỉnh sửa của Option B làm giao diện chính và tích hợp tính năng sinh bài tập tự luyện của Option C làm module củng cố kiến thức cuối bài.
