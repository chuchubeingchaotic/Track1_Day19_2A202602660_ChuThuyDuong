# Nhật Ký Sử Dụng AI Hỗ Trợ (AI Support Log)

**Học viên:** Chu Thủy Dương (2A202602660)  
**Tên nhóm:** `3 in 1`  
**AI Feature Case:** Case B — AI Notes: Personal Learning Notes  

---

## 1. Nguyên tắc sử dụng AI & Cam kết liêm chính học thuật

1. **AI đóng vai trò trợ lý tư duy (Thinking Partner & Sparring Partner):** Hỗ trợ gợi ý các góc nhìn thiết kế, chuẩn hóa cấu trúc văn bản và rà soát lỗi logic trong kịch bản kiểm thử.
2. **Không làm giả dữ liệu thực nghiệm:** Toàn bộ dữ liệu trong phiên thử nghiệm cá nhân (`prototype-feedback-note.md`) và các nhận xét từ người dùng đều là quan sát thực tế và trích dẫn trực tiếp từ người tham gia (P01), không dùng AI để sinh dữ liệu giả hoặc suy đoán thay cho trải nghiệm của người dùng thật.
3. **Người học chịu trách nhiệm kiểm duyệt cuối cùng:** Mọi đề xuất của AI đều được đối chiếu với nguyên tắc của môn học, thảo luận kỹ lưỡng trong nhóm `3 in 1` trước khi đưa vào tài liệu chính thức.

---

## 2. Nhật ký chi tiết các phiên tương tác với AI

### Phiên 1: Lên ý tưởng 3 phương án thiết kế (Three-Option Exploration)
- **Mục đích:** Xây dựng 3 hướng tiếp cận có độ phân kỳ rõ rệt về mức độ can thiệp của AI (Low AI, Balanced AI, High AI) dựa trên kết quả phỏng vấn từ Day 17.
- **Công cụ:** Gemini / Claude
- **Prompt chính:**
  > *"Dựa trên bài toán Case B (AI Notes) và insight từ Day 17: người học lười đọc lại ghi chú thụ động, hay có thói quen copy note nạp AI làm trắc nghiệm, hãy gợi ý 3 hướng thiết kế prototype có sự khác biệt rõ về mức độ tự động hóa của AI và quyền kiểm soát của người dùng."*
- **Output của AI:** AI đề xuất 3 nhánh: (1) Trợ lý neo ngữ cảnh thủ công, (2) Không gian làm việc đồng sáng tạo Canvas 2 cột, (3) Bộ sinh trắc nghiệm tự động Active Recall.
- **Đánh giá & Điều chỉnh của học viên:** Nhóm chấp nhận 3 hướng tiếp cận này vì phân tách rất rõ mức độ can thiệp của AI; bổ sung thêm chi tiết cơ chế *Hover-linking* đối chiếu nguồn cho Option B để tăng tính minh bạch.

---

### Phiên 2: Chuẩn bị kịch bản thử nghiệm Usability Testing (Task & Observation Design)
- **Mục đích:** Xây dựng kịch bản giao nhiệm vụ cho người dùng thử nghiệm mà không mớm cung hoặc làm lộ giải pháp.
- **Công cụ:** Gemini / Claude
- **Prompt chính:**
  > *"Hãy giúp tôi thiết kế 3 nhiệm vụ kiểm thử (User Tasks) và các câu hỏi đào sâu trung tính để người dùng tự do khám phá 3 bản prototype trên mà không có cảm giác bị dẫn dắt hoặc ép khen giải pháp."*
- **Output của AI:** Bộ khung 3 tasks tương ứng với 3 options và danh sách quan sát hành vi (thời gian ngập ngừng, biểu cảm, thao tác di chuột).
- **Đánh giá & Điều chỉnh của học viên:** Loại bỏ các câu hỏi có xu hướng hỏi ý kiến tương lai (*"Bạn có nghĩ tính năng này sẽ giúp bạn học tốt hơn không?"*), thay bằng câu hỏi đào sâu vào cảm nhận tức thì (*"Vừa rồi bạn vừa bấm nút đó, điều gì xảy ra tiếp theo có đúng như bạn kỳ vọng không?"*).

---

### Phiên 3: Cấu trúc hóa ghi chép sau phiên phỏng vấn thực tế
- **Mục đích:** Chuyển đổi các ghi chú thô trong quá trình quan sát người dùng P01 thành biên bản Usability Testing có cấu trúc chặt chẽ.
- **Công cụ:** Gemini
- **Prompt chính:**
  > *"Dưới đây là các gạch đầu dòng ghi chép thô và trích dẫn lời nói của bạn Nam trong buổi thử nghiệm prototype 30 phút. Hãy giúp tôi gom nhóm lại theo các mục: Hành vi quan sát được, Trích dẫn trực tiếp, Điểm bối rối/Friction và Đánh giá về AI UX."*
- **Output của AI:** Bản dàn ý phân loại rõ ràng theo từng option, giữ nguyên văn các câu quote của người dùng.
- **Đánh giá & Điều chỉnh của học viên:** Rà soát lại từng quote, điều chỉnh lại đúng giọng điệu tiếng Việt thực tế của bạn Nam, bổ sung phần đúc kết cá nhân của Facilitator.

---

### Phiên 4: Hỗ trợ đối chiếu phản hồi và tổng hợp báo cáo nhóm
- **Mục đích:** Tìm điểm giao nhau giữa 3 phiên thử nghiệm của 3 thành viên trong nhóm `3 in 1` để đưa ra quyết định giải pháp chung.
- **Công cụ:** Gemini / Claude
- **Prompt chính:**
  > *"So sánh phản hồi từ 3 người dùng: User 1 từ chối Option A vì lười dọn dẹp, thích giao diện 2 cột của Option B và cực thích trắc nghiệm của Option C; User 2 & 3 cũng có nhận xét tương tự về giao diện 2 cột và nỗi sợ đọc tài liệu dài. Hãy gợi ý phương án kiến trúc kết hợp tối ưu."*
- **Output của AI:** Gợi ý mô hình kiến trúc lai ghép (Hybrid Architecture) kết hợp giao diện Canvas 2 cột làm nền tảng chính và gắn thêm Module Active Recall ở bước hoàn tất ghi chú.
- **Đánh giá & Điều chỉnh của học viên:** Nhóm thống nhất đây là hướng đi khả thi nhất, vẽ lại sơ đồ luồng người dùng và đưa vào `group-feedback-synthesis.md`.

---

### Phiên 5: Thiết lập cấu trúc thư mục và rà soát checklist nộp bài Day 19
- **Mục đích:** Tự động hóa việc tạo khung 6 tệp tin chuẩn theo yêu cầu bài học Day 19 và rà soát tính nhất quán giữa các tài liệu.
- **Công cụ:** Antigravity AI Assistant
- **Đánh giá của học viên:** Tiết kiệm thời gian định dạng, đảm bảo cấu trúc thư mục repo chuẩn xác, mạch lạc và sẵn sàng nộp bài.

---

## 3. Tổng kết bài học về việc ứng dụng AI
- AI phát huy tối đa hiệu quả khi được sử dụng làm công cụ đối thoại phản biện (Sparring Partner) để tìm ra các góc nhìn thiết kế khác nhau trước khi ra quyết định.
- Khi làm việc với người dùng thật, sự thấu cảm, việc quan sát ngôn ngữ cơ thể, sự ngập ngừng di chuột và những câu nói bột phát của user là những dữ liệu đắt giá nhất mà không một mô hình AI nào có thể thay thế được.
