# MathGrader AI - Ứng dụng Chấm Thi Tự Luận Môn Toán

Ứng dụng web thông minh hỗ trợ giáo viên môn Toán **chấm bài thi tự luận**, **nhận dạng chữ viết tay (OCR) bằng Gemini AI Multimodal Vision**, **tải đáp án từ file Word (.docx)** và **chấm hàng loạt tự động**.

## 🚀 Tính năng nổi bật

1. **Đáp án & Thang điểm (Rubric)**:
   * Tự động bóc tách các bước giải từ file Word (`.docx`) hoặc file văn bản (`.txt`).
   * Hỗ trợ công thức toán học sắc nét bằng **KaTeX**.
   * Hỗ trợ tải xuống file **Mẫu Word đáp án (.docx)** chuẩn định dạng.

2. **Chụp ảnh bài làm học sinh & OCR AI**:
   * Chụp ảnh trực tiếp từ camera điện thoại (hỗ trợ camera sau trên smartphone).
   * Tự động gọi **Gemini 3 Flash Multimodal API** để đọc chữ viết tay, so sánh với đáp án và gợi ý điểm số, lỗi sai từng bước.

3. **Chấm hàng loạt (Batch Grading)**: Chấm toàn bộ danh sách bài nộp chỉ với 1 cú click.

4. **Thống kê & Xuất Excel**: Xem điểm trung bình, điểm cao nhất và xuất file báo cáo điểm số ra định dạng CSV.

## 🛠️ Hướng dẫn đưa lên GitHub để dùng trên Điện thoại

1. Tạo một Repository mới trên [GitHub](https://github.com/).
2. Tải 2 file `index.html` và `README.md` về máy.
3. Upload (kéo thả) cả 2 file lên kho chứa GitHub của bạn.
4. Vào **Settings** -> **Pages** -> Chọn Branch là `main` và thư mục `/ (root)` -> Bấm **Save**.
5. Truy cập vào đường link GitHub Pages được cung cấp để sử dụng trực tiếp trên điện thoại di động mọi lúc mọi nơi!