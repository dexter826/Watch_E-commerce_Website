# WEBSITE BÁN ĐỒNG HỒ - ASP.NET MVC

## THÔNG TIN SINH VIÊN

- **Họ và tên:** Trần Công Minh
- **MSSV:** 2001222641
- **Trường:** Đại học Công Thương TP.HCM (HUIT)
- **Ngành:** Công nghệ thông tin

## GIỚI THIỆU DỰ ÁN

Dự án "Website Bán Đồng Hồ" được xây dựng bằng ASP.NET MVC, là một ứng dụng web thương mại điện tử chuyên về việc bán các loại đồng hồ. Website cung cấp đầy đủ các chức năng cần thiết cho một trang thương mại điện tử, từ việc hiển thị sản phẩm, quản lý giỏ hàng, đặt hàng, đến quản lý thông tin khách hàng và hệ thống quản trị cho admin.

## CÔNG NGHỆ SỬ DỤNG

- **Framework:** ASP.NET MVC 5
- **Ngôn ngữ lập trình:** C#
- **Cơ sở dữ liệu:** SQL Server
- **ORM:** Entity Framework
- **Front-end:** HTML, CSS, JavaScript, Bootstrap
- **Thư viện bổ sung:** jQuery, AutoMapper, Entity Framework

## TÍNH NĂNG CHÍNH

### Phía người dùng (Khách hàng)

1. **Quản lý tài khoản**

   - Đăng ký tài khoản mới
   - Đăng nhập/Đăng xuất
   - Quản lý thông tin cá nhân
   - Đổi mật khẩu

2. **Tìm kiếm và xem sản phẩm**

   - Xem danh sách sản phẩm theo danh mục
   - Xem danh sách sản phẩm theo thương hiệu
   - Xem chi tiết sản phẩm
   - Tìm kiếm sản phẩm

3. **Giỏ hàng và đặt hàng**

   - Thêm sản phẩm vào giỏ hàng
   - Cập nhật số lượng sản phẩm trong giỏ hàng
   - Xóa sản phẩm khỏi giỏ hàng
   - Đặt hàng và thanh toán
   - Xem lịch sử mua hàng

4. **Khuyến mãi**
   - Xem các sản phẩm đang được khuyến mãi
   - Áp dụng mã khuyến mãi khi thanh toán

### Phía quản trị (Admin)

1. **Quản lý sản phẩm**

   - Thêm, sửa, xóa sản phẩm
   - Quản lý danh mục sản phẩm
   - Quản lý thương hiệu

2. **Quản lý đơn hàng**

   - Xem danh sách đơn hàng
   - Cập nhật trạng thái đơn hàng
   - Xem chi tiết đơn hàng

3. **Quản lý khuyến mãi**

   - Tạo, sửa, xóa chương trình khuyến mãi
   - Quản lý chi tiết khuyến mãi cho từng sản phẩm

4. **Quản lý cơ sở dữ liệu**
   - Sao lưu dữ liệu
   - Khôi phục dữ liệu

## CẤU TRÚC DỰ ÁN

- **BanDongHosln:** Thư mục chính của dự án
  - **BanDongHo:** Thư mục chứa mã nguồn của ứng dụng
    - **App_Start:** Cấu hình khởi động ứng dụng
    - **Areas:** Phân vùng Admin
    - **Content:** CSS và các tài nguyên tĩnh
    - **Controllers:** Các controller xử lý logic
    - **Models:** Các model và dịch vụ
    - **Views:** Giao diện người dùng
  - **packages:** Thư viện và package
- **Database:** Chứa script SQL và hình ảnh sản phẩm

## HƯỚNG DẪN CÀI ĐẶT

1. **Yêu cầu hệ thống:**

   - Visual Studio (2019 trở lên)
   - SQL Server (2014 trở lên)
   - .NET Framework 4.5 trở lên

2. **Các bước cài đặt:**
   - Clone hoặc tải dự án về máy
   - Mở file `BanDongHosln.sln` bằng Visual Studio
   - Chạy script SQL trong thư mục Database để tạo cơ sở dữ liệu
   - Tạo file `ConnectionStrings.config` từ file mẫu `ConnectionStrings.Template.config` và cập nhật chuỗi kết nối
   - Tạo file `AppSettings.config` từ file mẫu `AppSettings.Template.config` và cập nhật cấu hình email
   - Build và chạy dự án

## Source Code + Báo cáo [Link]([https://github.com/dexter826/dexter826/blob/main/MyCV.pdf](https://drive.google.com/drive/u/1/folders/1UheNadd-5-4I8xfTkU2KgG2oGCnErFpW))

## LIÊN HỆ

Nếu có bất kỳ thắc mắc hoặc góp ý nào, vui lòng liên hệ:

- Email: tcongminh1604@gmail.com
- SĐT: +84 777999496
