# CSE392-Nhom01-TLU
QLDACNTT - Hệ thống Quản lý Công việc
# 📋 Hệ thống Quản lý Công việc (Mini Task Manager / Trello Clone)
**Mã lớp/Nhóm:** CSE392-Nhom01-TLU

## 🎯 Mục tiêu dự án
Xây dựng một ứng dụng web cho phép người dùng cá nhân và nhóm quản lý dự án, theo dõi luồng công việc qua các bảng (Boards) và thẻ (Tasks). Dự án tập trung vào việc áp dụng thiết kế cơ sở dữ liệu chuẩn hóa (3NF), xây dựng RESTful API và xử lý DOM linh hoạt ở phía client.

## 🛠 Công nghệ sử dụng
*   **Frontend:** HTML5, CSS3, JavaScript (Vanilla JS / DOM Manipulation).
*   **Backend:** Java Spring Boot.
*   **Cơ sở dữ liệu:** MySQL (Thiết kế ERD từ 1NF đến 3NF).
*   **Kiểm thử:** JUnit, Mockito.
*   **Quản lý mã nguồn:** Git & GitHub.

## 👥 Phân công công việc (Team Roles)

Dự án được chia module độc lập để hạn chế tối đa việc conflict code khi gộp nhánh (merge branch).

| Họ và tên | Vai trò chính | Nhiệm vụ chi tiết |
| :--- | :--- | :--- |
| **Lê Quang Duy** | **Team Leader / Database & Auth** | Thiết kế ERD; Khởi tạo project Spring Boot; Làm tính năng Đăng ký/Đăng nhập (Security/JWT); Quản lý việc merge code trên GitHub. |
| **Nguyễn Hữu Luân** | **Backend Developer (Core API)** | Viết các RESTful API cho CRUD (Thêm/Sửa/Xóa/Đọc) Project, Task, Comment; Cập nhật trạng thái Task (To-do, Doing, Done). |
| **Vũ Hải Đường** | **Frontend Developer (Board UI)** | Code giao diện chính của bảng công việc (Board layout); Xử lý sự kiện kéo thả (Drag & Drop) hoặc nút chuyển trạng thái Task bằng JavaScript DOM. |
| **Vũ Thị Lê Vy** | **Frontend Developer (Dashboard & API)**| Code giao diện Đăng nhập/Đăng ký, Trang chủ (Dashboard) quản lý các dự án; Gọi Fetch API để kết nối dữ liệu Frontend với Backend. |
| **Phan Hoàng Lê VY** | **QA Tester & Backend (Extra)** | Viết Unit Test (JUnit/Mockito) cho các logic Backend phức tạp; Phát triển API tìm kiếm Task/Filter; Cập nhật tài liệu README & báo cáo. |
