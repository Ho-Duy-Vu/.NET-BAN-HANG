# 🛒 E-Commerce Website – ASP.NET MVC

**Author:** Hồ Duy Vũ  
📧 **Email:** duyvu11092004@gmail.com  
💻 **Platform:** Web Application  
🧱 **Architecture:** MVC + RESTful API  

---

## 📌 Giới Thiệu Dự Án

**E-Commerce Website** là một ứng dụng web bán hàng được xây dựng bằng **ASP.NET MVC**, hỗ trợ đầy đủ các chức năng cơ bản của một hệ thống thương mại điện tử, bao gồm:

- Quản lý sản phẩm & danh mục
- Giỏ hàng & thanh toán
- Quản lý người dùng & phân quyền
- Theo dõi lịch sử giao dịch
- Cung cấp API RESTful cho hệ thống

Dự án áp dụng **Entity Framework** để làm việc với **SQL Server**, đảm bảo khả năng mở rộng, bảo mật và dễ bảo trì.

---

## 🎯 Mục Tiêu Dự Án

- Xây dựng hệ thống bán hàng theo mô hình MVC chuẩn
- Áp dụng ORM (Entity Framework) vào dự án thực tế
- Thực hành phân quyền người dùng (RBAC)
- Thiết kế API RESTful phục vụ mở rộng hệ thống
- Rèn luyện kỹ năng backend với ASP.NET

---

## ✨ Tính Năng Chính

### 📦 1. Quản Lý Sản Phẩm

- Thêm / sửa / xóa sản phẩm
- Hiển thị danh sách sản phẩm
- Quản lý thông tin chi tiết:
  - Tên
  - Mô tả
  - Giá bán
  - Hình ảnh

---

### 🗂️ 2. Quản Lý Danh Mục

- Thêm / sửa / xóa danh mục
- Phân loại sản phẩm theo danh mục
- Hỗ trợ lọc và tìm kiếm sản phẩm

---

### 🛒 3. Giỏ Hàng

- Thêm sản phẩm vào giỏ hàng
- Cập nhật số lượng
- Tính tổng tiền tự động
- Thanh toán đơn hàng
- Theo dõi trạng thái đơn hàng

---

### 🔐 4. Phân Quyền Người Dùng (RBAC)

- **Admin**
  - Quản lý sản phẩm
  - Quản lý danh mục
  - Quản lý người dùng
  - Quản lý đơn hàng
- **User**
  - Đăng ký / đăng nhập
  - Xem sản phẩm
  - Thêm vào giỏ hàng
  - Thanh toán

> Phân quyền được triển khai theo **Role-Based Access Control**, đảm bảo an toàn hệ thống.

---

### 👤 5. Đăng Ký & Đăng Nhập

- Đăng ký tài khoản mới
- Đăng nhập hệ thống
- Mã hóa mật khẩu
- Bảo mật thông tin người dùng

---

### 🧾 6. Chi Tiết Sản Phẩm

- Trang chi tiết sản phẩm riêng biệt
- Hiển thị đầy đủ:
  - Hình ảnh
  - Mô tả
  - Giá bán
  - Danh mục liên quan

---

### 📜 7. Lịch Sử Giao Dịch

- Người dùng theo dõi lịch sử mua hàng
- Xem thông tin:
  - Đơn hàng
  - Tổng tiền
  - Trạng thái thanh toán

---

### 🔗 8. API RESTful

- Cung cấp API cho:
  - Sản phẩm
  - Danh mục
  - Đơn hàng
- Phục vụ tích hợp hệ thống & frontend khác
- Dễ dàng kiểm thử bằng Postman

---

### 🧪 9. Postman Collection

- Có sẵn bộ request Postman
- Hỗ trợ test nhanh API
- Phục vụ phát triển & debug

---

## 🛠️ Công Nghệ Sử Dụng

| Thành phần | Công nghệ |
|----------|----------|
| Framework | ASP.NET MVC |
| ORM | Entity Framework |
| Database | SQL Server |
| Frontend | Razor View, Bootstrap |
| JS | jQuery |
| API Test | Postman |
| IDE | Visual Studio 2022 |

---

## ⚙️ Cài Đặt & Chạy Ứng Dụng

### 🔧 Yêu Cầu Hệ Thống

- .NET Core SDK **3.1+**
- SQL Server / SQL Server Express
- Visual Studio 2022

---

### 1️⃣ Clone Repository


git clone https://github.com/username/repository.git
2️⃣ Cấu Hình Database
Tạo database mới trong SQL Server

Cập nhật chuỗi kết nối trong appsettings.json

"ConnectionStrings": {
  "DefaultConnection": "Server=.;Database=ECommerceDB;Trusted_Connection=True;"
}
3️⃣ Chạy Ứng Dụng
Mở project bằng Visual Studio

Build & Run (F5)

📂 Cấu Trúc Dự Án

ECommerceMVC/
│── Controllers/
│── Models/
│── Views/
│── API/
│── Data/
│── wwwroot/
│── appsettings.json
│── Program.cs
│── README.md
📡 API Endpoints (Ví Dụ)

GET    /api/products
POST   /api/products
PUT    /api/products/{id}
DELETE /api/products/{id}
🚀 Định Hướng Phát Triển
Thanh toán online (VNPay, MoMo)

Phân quyền chi tiết hơn

Dashboard quản trị

Thống kê & báo cáo doanh thu

Chuyển sang .NET 6/7

Tách Frontend & Backend (API-first)

👤 Thông Tin Tác Giả
Name: Hồ Duy Vũ

Email: duyvu11092004@gmail.com

⭐ Nếu bạn thấy project hữu ích, hãy star repo để ủng hộ nhé!


---

### ✅ README này phù hợp cho:
- Đồ án **ASP.NET MVC**
- Môn **Lập trình Web / Công nghệ .NET**
- Portfolio xin thực tập / fresher
- Repo GitHub cá nhân

Nếu bạn muốn mình:
- 🔹 Viết **README song ngữ**
- 🔹 Rút gọn cho **1 trang báo cáo**
- 🔹 Viết **báo cáo Word 10–20 trang**
- 🔹 Sinh **Use Case / ERD / Database Schema**
- 🔹 Chuẩn hóa theo style **BigTech**

👉 nói mình, mình làm tiếp cho đúng mục tiêu bạn dùng 💪

