# 🌍 TripSync - Website Hỗ Trợ Quản Lý Và Lập Kế Hoạch Du Lịch Nhóm

## 📌 Giới thiệu

TripSync là hệ thống website hỗ trợ quản lý và lập kế hoạch du lịch nhóm, giúp các thành viên dễ dàng phối hợp trong quá trình chuẩn bị và thực hiện chuyến đi.

Hệ thống cung cấp một nền tảng tập trung cho phép quản lý lịch trình, theo dõi chi tiêu, chia sẻ hình ảnh, quản lý checklist chuẩn bị và cộng tác giữa các thành viên trong nhóm.

---

## ✨ Chức năng chính

### 🔐 Quản lý tài khoản

* Đăng ký tài khoản
* Đăng nhập / Đăng xuất
* Khôi phục mật khẩu
* Quản lý thông tin cá nhân

### 🧳 Quản lý chuyến đi

* Tạo chuyến đi
* Cập nhật thông tin chuyến đi
* Xóa chuyến đi
* Mời thành viên tham gia
* Tham gia chuyến đi bằng mã mời
* Rời khỏi chuyến đi

### 📅 Quản lý lịch trình

* Thêm hoạt động
* Chỉnh sửa hoạt động
* Xóa hoạt động
* Đề xuất hoạt động
* Bình chọn hoạt động
* Góp ý hoạt động
* Chốt hoạt động

### 💰 Quản lý chi tiêu

* Thêm khoản chi
* Chỉnh sửa khoản chi
* Xóa khoản chi
* Thống kê chi tiêu
* Phân chia chi phí giữa các thành viên
* Hỗ trợ tính toán công nợ tự động

### ✅ Checklist chuẩn bị

* Phân công thành viên
* Đề xuất mục checklist
* Duyệt đề xuất checklist
* Cập nhật trạng thái hoàn thành
* Chỉnh sửa checklist
* Xóa mục checklist

### 📸 Thư viện ảnh

* Tải ảnh lên
* Xem ảnh
* Tải ảnh về
* Xóa ảnh không phù hợp

---

## 👥 Vai trò người dùng

### Trưởng nhóm (Trip Owner)

* Toàn quyền quản lý chuyến đi
* Quản lý thành viên
* Điều phối lịch trình
* Chốt hoạt động
* Phân công checklist

### Thành viên (Member)

* Tham gia chuyến đi
* Đề xuất và bình chọn hoạt động
* Quản lý chi tiêu
* Cập nhật checklist
* Chia sẻ hình ảnh

---

## 🛠 Công nghệ sử dụng

### Backend

* PHP 8.x
* Laravel 12
* MySQL

### Frontend

* HTML5
* CSS3
* JavaScript
* Bootstrap 5

### Công cụ hỗ trợ

* Git & GitHub
* Visual Studio Code
* Figma

---

## 🗄️ Cơ sở dữ liệu

Các bảng dữ liệu chính:

* users
* trips
* trip_members
* trip_days
* trip_activities
* activity_votes
* activity_comments
* trip_expenses
* expense_splits
* trip_photos
* checklist_items

---

## 🚀 Cài đặt dự án

### Clone project

```bash
git clone https://github.com/yourusername/tripsync.git
cd tripsync
```

### Cài đặt thư viện

```bash
composer install
```

### Tạo file môi trường

```bash
cp .env.example .env
```

### Sinh Application Key

```bash
php artisan key:generate
```

### Cấu hình Database

```env
DB_DATABASE=tripsync
DB_USERNAME=root
DB_PASSWORD=
```

### Migration Database

```bash
php artisan migrate
```

### Chạy dự án

```bash
php artisan serve
```

Truy cập:

```text
http://127.0.0.1:8000
```

---

## 🎯 Mục tiêu dự án

* Tăng khả năng cộng tác giữa các thành viên trong nhóm.
* Quản lý lịch trình tập trung.
* Minh bạch hóa chi tiêu.
* Hỗ trợ chuẩn bị chuyến đi hiệu quả.
* Lưu trữ và chia sẻ dữ liệu chuyến đi trên cùng một nền tảng.

---

## 👨‍💻 Tác giả

Nguyễn Mạnh Hùng

Sinh viên ngành Kỹ thuật Phần mềm
Trường Đại học Thủy Lợi

Đồ án tốt nghiệp 2026
