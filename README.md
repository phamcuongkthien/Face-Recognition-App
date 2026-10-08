# Phần Mềm Nhận Dạng Khuôn Mặt (Face Recognition System)

## 1. Giới thiệu dự án
Hệ thống ứng dụng xử lý ảnh và Học máy (Machine Learning) để tự động phát hiện và nhận dạng khuôn mặt qua hình ảnh hoặc camera/webcam theo thời gian thực.

## 2. Nhóm thành viên & Phân công công việc

| STT | Họ và tên | Vai trò | Phân công công việc | Nhánh Git |
| :---: | :--- | :--- | :--- | :--- |
| 1 | **Phạm Văn Cường** | Quản lý & Dữ liệu | Tạo và quản lý repo; thiết kế cơ sở dữ liệu SQLite (`db.py`), chuyển dữ liệu từ bản cũ, sao lưu. | `feature/data-preparation` |
| 2 | **Hoàng Mạnh Hùng** | Nhận diện (AI) | Mã hóa khuôn mặt, so khớp và xác nhận nhiều khung (`recognizer.py`), chống giả mạo bằng chớp mắt (`liveness.py`), hiệu chỉnh ngưỡng. | `feature/model-training` |
| 3 | **Bùi Minh Đức** | UI/UX | Thiết kế và lập trình giao diện (`app.py`, `theme.py`): đăng nhập, màn hình chính, hộp thoại, cửa sổ thống kê. | `feature/ui-development` |
| 4 | **Nguyễn Thị Thu Yên** | Tích hợp hệ thống | Luồng camera và nhận diện đa luồng (`vision.py`), điều phối điểm danh/đăng ký (`engine.py`), cấu hình và bảo mật. | `feature/system-integration` |
| 5 | **Trương Văn Tiến** | QA & Tài liệu | Thiết kế test case, viết bộ kiểm thử tự động, kiểm thử với camera và viết báo cáo dự án. | `feature/testing-documentation` |

## 3. Công nghệ sử dụng
* **Ngôn ngữ:** Python
* **Thư viện AI/Xử lý ảnh:** OpenCV, `face_recognition` / Dlib
* **Giao diện (UI):** Tkinter / PyQt
