# 🛒 E-Commerce Website – ASP.NET MVC

- **Author**: Hồ Duy Vũ – Software Engineer | AI & Backend Developer
- **GitHub**: https://github.com/Ho-Duy-Vu
- **Email**: duyvu11092004@gmail.com 
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

# 📦 ECommerce MVC Project

Dự án E-Commerce xây dựng bằng **ASP.NET MVC**, phục vụ mục tiêu học tập và phát triển hệ thống bán hàng cơ bản, có API mở rộng, dễ nâng cấp và tách frontend/backend trong tương lai.

---

## ⚙️ Hướng Dẫn Cài Đặt & Chạy Dự Án

### 1️⃣ Clone Repository


git clone https://github.com/username/repository.git
2️⃣ Cấu Hình Database
Tạo database mới trong SQL Server

Cập nhật chuỗi kết nối trong file appsettings.json

json
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=.;Database=ECommerceDB;Trusted_Connection=True;"
  }
}
💡 Có thể thay Server=. bằng localhost hoặc tên SQL Server phù hợp với máy bạn.

3️⃣ Chạy Ứng Dụng
Mở project bằng Visual Studio

Build & Run bằng phím F5

📂 Cấu Trúc Dự Án
bash
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
📡 API Endpoints (Ví dụ)
http
GET     /api/products
POST    /api/products
PUT     /api/products/{id}
DELETE  /api/products/{id}
🚀 Định Hướng Phát Triển
💳 Tích hợp thanh toán online (VNPay, MoMo)

🔐 Phân quyền chi tiết hơn (Role-based Authorization)

📊 Dashboard quản trị

📈 Thống kê & báo cáo doanh thu

⬆️ Nâng cấp lên .NET 6 / .NET 7

🧩 Tách Frontend & Backend theo hướng API-first

👤 Thông Tin Tác Giả
Name: Hồ Duy Vũ

Email: duyvu11092004@gmail.com

⭐ Nếu bạn thấy project hữu ích, hãy star repo để ủng hộ nhé!

markdown

---

### ✅ Cách dùng
1. Mở file `README.md`
2. **Xóa toàn bộ nội dung cũ**
3. **Paste nguyên khối trên**
4. Commit → push 👉 **KHÔNG lỗi**

Nếu bạn muốn:
- Gộp **README Portfolio + ECommerce** chung 1 style
- Viết README theo phong cách **BigTech / Tech Lead / Senior**
- Thêm badge, screenshot, demo GIF

👉 nói mình làm tiếp cho 🔥

