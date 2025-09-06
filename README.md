# 🛒 Website Bán Linh Kiện Điện Tử (ASP.NET MVC)

## 📖 Giới thiệu
Đây là **đồ án cuối kỳ môn học** với đề tài:  
**“Xây dựng website bán linh kiện điện tử bằng ASP.NET”**.  

Website được xây dựng nhằm hỗ trợ **quản lý bán hàng trực tuyến**, bao gồm:  
- Quản lý sản phẩm, danh mục  
- Giỏ hàng & đặt hàng  
- Quản lý đơn hàng  
- Đăng ký/đăng nhập  
- Phân quyền người dùng  

---

## 🚀 Công nghệ sử dụng
- **ASP.NET ** – Xử lý nghiệp vụ 
- **C#** – Ngôn ngữ lập trình chính  
- **SQL Server** – Hệ quản trị cơ sở dữ liệu  
- **Entity Framework (LINQ)** – Truy vấn dữ liệu  
- **HTML, CSS, Bootstrap, JavaScript, jQuery** – Thiết kế giao diện  
- **IIS Express / Visual Studio** – Môi trường triển khai và phát triển  

---

## ⚙️ Các chức năng chính
👤 **Khách hàng**  
- Đăng ký / Đăng nhập  
- Xem, tìm kiếm sản phẩm  
- Thêm sản phẩm vào giỏ hàng  
- Đặt hàng & theo dõi đơn hàng  

🧑‍💼 **Nhân viên**  
- Kiểm tra đơn hàng  
- Cập nhật trạng thái đơn hàng  
- Hỗ trợ khách hàng  

🛠️ **Quản trị viên (Admin)**  
- Quản lý sản phẩm, danh mục  
- Quản lý tài khoản người dùng  
- Quản lý đơn hàng  
- Xem và xuất báo cáo thống kê  

---

## 🗂️ Cấu trúc thư mục
```plaintext
.
├── Controllers/        # Chứa các Controller
├── Models/             # Chứa các lớp Model (EF, dữ liệu)
├── Views/              # Giao diện người dùng (Razor)
├── Content/            # CSS, ảnh, bootstrap
├── Scripts/            # JavaScript, jQuery
├── App_Data/           # Cơ sở dữ liệu (.mdf)
├── README.md           # File mô tả project
└── Web.config          # Cấu hình ứng dụng
