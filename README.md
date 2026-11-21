# 🎯 RMC301 Exam Practice - 380 Câu Trắc Nghiệm & Bộ Thẻ Quizlet

> **Phiên bản chính thức v1.3:** Tích hợp **Note cá nhân cho từng câu (Sidebar)**, **Chế độ Thi Thử (Mock Exam 30 câu / 50 câu có đếm giờ & chấm điểm)**, **Tìm kiếm câu hỏi nhanh (Search Bar)**, **Báo cáo thống kê năng lực (Analytics)** và **Đồng bộ thời gian thực qua Google Firebase**!

Kho lưu trữ toàn bộ dữ liệu ôn tập môn **RMC301 (Research Methods in Communication)** gồm 380 câu hỏi trắc nghiệm kèm đáp án và giải thích chi tiết, ứng dụng web trắc nghiệm tương tác trực tuyến có đồng bộ Cloud, và các file nạp thẻ Quizlet.

---

## 🌐 1. Link Truy Cập Ứng Dụng Web Trắc Nghiệm Trực Tuyến
👉 **[https://datkr001.github.io/rmc301-quiz/](https://datkr001.github.io/rmc301-quiz/)**

### ✨ Tính Năng Nổi Bật Của Website (v1.3):
- **Làm bài trực quan:** 380 câu trắc nghiệm với các nút chọn `A`, `B`, `C`, `D` độc lập.
- **Phản hồi tức thì:** Bấm chọn biết ngay Đúng (xanh) / Sai (đỏ), kèm đáp án chuẩn và lời giải thích tiếng Việt.
- **📝 Note cá nhân cho từng câu:** Cột Sidebar độc lập bên phải giúp bạn ghi chú mẹo nhớ, từ khóa, tự động lưu thời gian thực lên Firebase Cloud. Có icon 📝 và bộ lọc riêng trong bảng câu hỏi.
- **⏱️ Chế độ Thi Thử (Mock Exam):**
  - Tùy chọn ⚡ **Test Nhanh 30 câu - 40 phút** hoặc 🎯 **Format Thi Thật 50 câu - 60 phút**.
  - Đồng hồ đếm ngược, ẩn đáp án khi làm, chấm điểm thang 10 và xem lại lời giải sau khi nộp bài.
- **🔍 Tìm kiếm câu hỏi (Search Bar):** Gõ từ khóa tiếng Anh/tiếng Việt để lọc và nhảy ngay tới bất kỳ câu nào trong 380 câu.
- **📊 Bảng thống kê năng lực (Analytics):** Xem tỷ lệ hoàn thành, tỷ lệ đúng/sai và danh sách câu hay làm sai để ôn tập lại trọng điểm.
- **☁️ Đồng bộ đám mây tự động (Realtime Cloud Sync):** Tự động đồng bộ tiến độ 2 chiều giữa **Máy tính** và **Điện thoại** qua Google Firebase. Làm trên PC, mở điện thoại là thấy ngay!

---

## 📚 2. Danh Sách File Dữ Liệu Nạp Quizlet (Thành Phẩm)

Trong repo này có đầy đủ các file đã được chuẩn hóa để bạn nạp vào Quizlet:

| Tên File | Mô Tả | Khuyên Dùng |
| :--- | :--- | :--- |
| **`quizlet_toan_bo_380_cau_1_lan_nhap.txt`** | Toàn bộ 380 câu nén dạng 1 dòng/câu (Tab & Newline) | ⭐ Nhập 1 lần toàn bộ |
| **`quizlet_part1_cau_1_den_95.txt`** | 95 câu phần 1 (Định dạng nhiều dòng đẹp mắt) | Chia nhỏ <2000 dòng |
| **`quizlet_part2_cau_96_den_190.txt`** | 95 câu phần 2 | Chia nhỏ <2000 dòng |
| **`quizlet_part3_cau_191_den_285.txt`** | 95 câu phần 3 | Chia nhỏ <2000 dòng |
| **`quizlet_part4_cau_286_den_380.txt`** | 95 câu phần 4 | Chia nhỏ <2000 dòng |
| **`quizlet_cards.csv`** | Dữ liệu dạng bảng tính Excel / CSV | Mở bằng Excel |
| **`quizlet_cards.json`** | Dữ liệu JSON nguyên bản có cấu trúc | Lập trình / Tích hợp |
| **`HUONG_DAN_NHAP_QUIZLET.md`** | Hướng dẫn chi tiết cách cài đặt ký tự phân cách trên Quizlet | Đọc trước khi nhập |

---

## 🛠️ Hướng Dẫn Nạp Thẻ Vào Quizlet
1. Mở Quizlet $ightarrow$ Tạo học phần mới $ightarrow$ Bấm nút **"Nhập" (Import)**.
2. Mở file `quizlet_toan_bo_380_cau_1_lan_nhap.txt` $ightarrow$ Nhấn `Ctrl + A` $ightarrow$ `Ctrl + C` (Copy toàn bộ).
3. Dán vào khung nhập của Quizlet:
   - Ký tự phân cách giữa Thuật ngữ và Định nghĩa: Chọn **Tab**.
   - Ký tự phân cách giữa các thẻ: Chọn **Dòng mới (New line)**.
4. Bấm **"Nhập"** $ightarrow$ Tạo học phần thành công!
