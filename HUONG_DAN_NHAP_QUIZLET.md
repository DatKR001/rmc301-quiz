# Hướng Dẫn Nhập 380 Flashcard Vào Quizlet

Toàn bộ **380 câu hỏi trắc nghiệm** từ file Google Slide `Sever_1_SEMESTER_3_MC_RMC301(m)` đã được trích xuất thành công:
- **Mặt trước (Thuật ngữ / Câu hỏi):** Giữ nguyên vẹn 100% nội dung câu hỏi và các phương án A, B, C, D từ hình ảnh slide gốc (đã khử hoàn toàn watermark).
- **Mặt sau (Định nghĩa / Đáp án):** Chứa đáp án chuẩn xác cùng phần dịch nghĩa và giải thích chi tiết từ Speaker Notes.

---

## Cách 1: Nhập bằng tính năng "Nhập" của Quizlet (Khuyên dùng - Nhanh nhất)

1. Mở file [quizlet_custom_import.txt](file:///D:/Tools/Antigravity/Project/Quizlet%20Convert/quizlet_custom_import.txt), nhấn **Ctrl + A** rồi **Ctrl + C** để sao chép toàn bộ nội dung.
2. Truy cập [Quizlet.com](https://quizlet.com), đăng nhập và bấm nút **Tạo** $\rightarrow$ chọn **Học phần** (Create $\rightarrow$ Study set).
3. Ngay phía trên danh sách thẻ, bấm vào nút **+ Nhập** (+ Import).
4. Dán (**Ctrl + V**) toàn bộ nội dung vừa copy vào ô văn bản lớn.
5. Ở phần cài đặt ký tự phân tách bên dưới ô nhập:
   - **Giữa thuật ngữ và định nghĩa (Between term and definition):** Chọn ô **Tùy chỉnh (Custom)** và nhập: `###`
   - **Giữa các thẻ (Between cards):** Chọn ô **Tùy chỉnh (Custom)** và nhập: `$$$`
6. Bấm nút **Nhập** (Import).
7. Quizlet sẽ lập tức tải lên đầy đủ **380 thẻ** với định dạng chuẩn, nhiều dòng rõ ràng. Bấm **Tạo** để lưu học phần!

---

## Cách 2: Nhập từ file bảng tính Excel / CSV
- Bạn có thể mở file [quizlet_cards.csv](file:///D:/Tools/Antigravity/Project/Quizlet%20Convert/quizlet_cards.csv) bằng Microsoft Excel hoặc Google Sheets để chỉnh sửa, thêm bớt hoặc quản lý theo dạng bảng 3 cột (`Slide`, `Term`, `Definition`).

---

## Danh mục các file đã tạo trong thư mục làm việc:
- [quizlet_custom_import.txt](file:///D:/Tools/Antigravity/Project/Quizlet%20Convert/quizlet_custom_import.txt) *(File chính dùng để copy dán vào Quizlet)*
- [quizlet_tab_separated.txt](file:///D:/Tools/Antigravity/Project/Quizlet%20Convert/quizlet_tab_separated.txt) *(File định dạng phân tách bằng Tab)*
- [quizlet_cards.csv](file:///D:/Tools/Antigravity/Project/Quizlet%20Convert/quizlet_cards.csv) *(File CSV dạng bảng tính)*
- [quizlet_cards.json](file:///D:/Tools/Antigravity/Project/Quizlet%20Convert/quizlet_cards.json) *(Dữ liệu cấu trúc JSON)*
- [process_presentation.py](file:///D:/Tools/Antigravity/Project/Quizlet%20Convert/process_presentation.py) *(Kịch bản xử lý tự động)*
