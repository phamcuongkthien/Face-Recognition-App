# Phần Mềm Nhận Dạng Khuôn Mặt (Face Recognition System)

## 1. Giới thiệu dự án
Hệ thống ứng dụng xử lý ảnh và Học máy (Machine Learning) để tự động phát hiện và nhận dạng khuôn mặt qua hình ảnh hoặc camera/webcam theo thời gian thực.

## 2. Thành viên nhóm & Phân công công việc

| STT | Họ và tên | Vai trò | Phân công công việc | Branch |
| :---: | :--- | :--- | :--- | :--- |
| 1 | **Phạm Văn Cường** *(Leader)* | Quản lý & Data | Tạo/quản lý repo, thu thập, tiền xử lý và gán nhãn dataset | `feature/data-preparation` |
| 2 | **Trương Văn Tiến** | AI Model | Trích xuất đặc trưng (embeddings), huấn luyện & tối ưu mô hình | `feature/model-training` |
| 3 | **Hoàng Mạnh Hùng** | UI/UX | Thiết kế & lập trình giao diện chọn ảnh, bật webcam, hiển thị kết quả | `feature/ui-development` |
| 4 | **Bùi Minh Đức** | System Integration | Kết nối mô hình AI với UI, xử lý luồng camera/webcam real-time | `feature/system-integration` |
| 5 | **Nguyễn Thị Thu Yên** | QA & Docs | Thiết kế test case, kiểm thử hiệu năng & viết báo cáo dự án | `feature/testing-documentation` |

## 3. Công nghệ sử dụng
* **Ngôn ngữ:** Python
* **Thư viện AI/Xử lý ảnh:** OpenCV, `face_recognition` / Dlib
* **Giao diện (UI):** Tkinter / PyQt
