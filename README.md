# 🎓 EngiLingo AI - Trợ Lý Học Tiếng Anh Thông Minh

> Nền tảng web hỗ trợ học tiếng Anh chuyên ngành kỹ thuật và giao tiếp thông minh, tích hợp AI, Web Speech API và phương pháp lặp lại ngắt quãng (Spaced Repetition System - SRS).

---

## 🚀 Tính Năng Nổi Bật

### 1. 💬 Hội Thoại Tương Tác AI (Interactive Speaking & Chat Room)
- **Roleplay linh hoạt**: Chọn vai trò AI phù hợp với mục tiêu học tập:
  - 🎓 *Cố vấn học thuật UTC2* (Chuyên ngành & Thuật ngữ kỹ thuật)
  - 🗣️ *Giám khảo IELTS Speaking* (Luyện phản xạ & chấm điểm Band 7.5+)
  - 💼 *Phỏng vấn tuyển dụng kỹ sư* (Tech Job Interview)
  - ☕ *Bạn trò chuyện tiếng Anh hàng ngày* (Casual English)
- **4 lớp phản hồi toàn diện trong mỗi tin nhắn**:
  1. **Câu trả lời đàm thoại** bằng tiếng Anh kèm nút nghe phát âm chuẩn bản xứ.
  2. **Bản dịch tiếng Việt** chuẩn xác giúp hiểu sâu ngữ cảnh.
  3. **Soi & sửa lỗi ngữ pháp**: Tự động phát hiện lỗi chia thì, hòa hợp chủ ngữ - vị ngữ, lặp liên từ, giới từ, dấu câu... kèm câu sửa chuẩn.
  4. **Đề xuất cách nói hay hơn**: Gợi ý 2 phiên bản câu nói (Chuẩn tự nhiên & Học thuật/Chuyên nghiệp) kèm nút nghe đọc riêng từng câu.
- **Voice Input & TTS**: Nhận diện giọng nói qua microphone và tự động đọc phản hồi bằng Web Speech API.

### 2. 🎙️ Phòng Luyện Phát Âm Chuẩn (Pronunciation Lab)
- Nghe câu mẫu từ người bản xứ.
- Nhấn Microphone thu âm và đối chiếu ngữ âm từng từ theo thời gian thực.
- Bôi màu trực quan: từ phát âm chuẩn (xanh lá) và từ cần cải thiện (đỏ).
- Tính toán điểm chính xác (%) và ghi nhận lịch sử vào bảng thống kê.

### 3. ✍️ Tối Ưu Văn Phong Học Thuật (Grammar & Academic Rewriter)
- Chuyển đổi văn phong nói đơn giản sang văn phong học thuật (Academic Writing / IELTS Band 7.5+).
- Cung cấp bảng đối chiếu sửa lỗi chi tiết: từ gốc, từ thay thế và quy tắc ngữ pháp.

### 4. 🗂️ Kho Từ Vựng & Thẻ Ghi Nhớ (SRS Flashcards)
- Phương pháp lặp lại ngắt quãng (Spaced Repetition) với thuật toán tính khoảng cách ôn tập tối ưu.
- Các bộ thẻ chuyên sâu:
  - 🚗 *Kỹ Thuật Giao Thông & Vận Tải (UTC2)*
  - 💻 *Công Nghệ Thông Tin & AI*
  - 📈 *TOEIC 650+ Trọng Tâm*
  - ⭐ *Bộ thẻ do người dùng tự tạo* (thêm từ mới tùy biến).

### 5. 📊 Bảng Thống Kê Tiến Độ Học Tập
- Theo dõi streak học liên tục, số lượng từ đã học, số lần luyện âm, điểm trung bình và biểu đồ hoạt động.
- Hỗ trợ xuất dữ liệu học tập ra file JSON.

---

## 🛠️ Công Nghệ Sử Dụng

- **Frontend**: HTML5, Tailwind CSS, JavaScript (ES6+).
- **Icons & Charts**: Font Awesome 6.5, Chart.js.
- **APIs**:
  - Web Speech API (`SpeechRecognition`, `SpeechSynthesis`).
  - Google Gemini API (`gemini-1.5-flash`) cho phản hồi thời gian thực thông minh.
  - Tích hợp sẵn bộ máy Rule-based NLP Engine xử lý mượt mà khi chạy offline.
- **Lưu trữ**: `localStorage` (lưu trữ tiến độ, điểm số, streak và từ vựng tự tạo).

---

## 📖 Hướng Dẫn Sử Dụng

1. Clone repository về máy:
   ```bash
   git clone https://github.com/TranNinhThuan171007/website_ho_tro_hoc_tieng_anh.git
   ```
2. Mở file `index.html` trực tiếp trên trình duyệt (khuyến nghị **Google Chrome** hoặc **Microsoft Edge** để trải nghiệm đầy đủ Web Speech API).
3. (Tùy chọn) Nhấn nút **"Cài Đặt AI"** ở góc phải màn hình để nhập Google Gemini API Key nếu muốn trải nghiệm sức mạnh phân tích chuyên sâu của LLM.

---

*Dự án phát triển phục vụ học tập và nghiên cứu ứng dụng AI trong giáo dục đại học.*
