# 🛒 Pet Store



**Github**: https://github.com/tranzankhien/php_web_advance.git

## 🌐 Giới thiệu
Đây là một website bán thú cưng và sản phẩm liên quan trực tuyến được xây dựng bằng framework PHP Laravel. Website cho phép người dùng duyệt sản phẩm, tìm kiếm, phân loại và đặt hàng. Quản trị viên có thể quản lý người dùng, sản phẩm và các danh mục liên quan.

## ⚙️ Công nghệ sử dụng
- **Backend:** PHP Laravel
- **Database:** Local xampp (MySQL)
- **Frontend:** HTML, CSS, JavaScript (Bootstrap)
  
## 🚀 Chức năng chính
### 🛍️ Người dùng
- Xem danh sách sản phẩm
- Tìm kiếm sản phẩm theo tên
- Lọc sản phẩm theo danh mục
- Đăng ký, đăng nhập, đặt hàng
- Quản lý giỏ hàng

### 🔑 Quản trị viên
- Quản lý sản phẩm: Thêm, sửa, xóa
- Quản lý đơn hàng: Cập nhật trạng thái, xoá
  
## 📦 Cài đặt

### 1️⃣ Clone repository
```bash
git clone https://github.com/tranzankhien/php_web_advance.git
cd SHOPTHUCUNG_LARAVEL
```

### 2️⃣ Cấu hình môi trường
Tạo file `.env` và cấu hình các thông số sau:
```plaintext
DB_CONNECTION=mysql
DB_HOST=web_laravel
DB_PORT=3306
DB_USERNAME=root
DB_PASSWORD=""
```

### 3️⃣ Cài đặt các package
```bash
composer install
npm install
```

### 4️⃣ Tạo key và migrate database
```bash
php artisan key:generate
php artisan migrate --seed
```


## 🔍 Hướng dẫn sử dụng
- **Trang chủ:** Hiển thị danh sách sản phẩm
- **Tìm kiếm:** Nhập từ khóa vào thanh tìm kiếm
- **Phân loại:** Chọn danh mục trong menu
- **Trang quản trị:** `/admin`

## 🔑 Tài khoản demo
- **Admin:** `admin@admin.com` / `123`

## 📖 Cấu trúc thư mục
```plaintext
├── app
│   ├── Http\Controllers
│   ├── Models
│   └── Services
├── database
│   └── migrations
├── resources
│   ├── views
│   └── js
├── routes
│   └── web.php
└── public
```

## ⚠️ Lưu ý
- Đảm bảo mở kết nối đến cơ sở dữ liệu trên Aiven.
- Bảo mật các biến môi trường khi deploy lên server.
