# HƯỚNG DẪN CÀI ĐẶT JOOMLA

## 1. Mục đích

Thư mục `setup` lưu trữ các tài liệu và hướng dẫn liên quan đến quá trình cài đặt, cấu hình và thiết lập Website Joomla của đề tài.

Website được xây dựng nhằm giới thiệu thông tin Trung tâm Giới thiệu việc làm.

---

## 2. Môi trường cài đặt

Website được triển khai trên môi trường máy chủ Web cục bộ.

Các thành phần sử dụng:

- XAMPP
- Apache
- PHP
- MySQL hoặc MariaDB
- phpMyAdmin
- Joomla CMS
- Trình duyệt Web

Phiên bản cụ thể của các phần mềm sẽ được cập nhật sau khi hoàn thành quá trình cài đặt thực tế.

---

## 3. Cài đặt môi trường XAMPP

### Bước 1: Cài đặt XAMPP

Cài đặt XAMPP trên máy tính.

Sau khi cài đặt, mở XAMPP Control Panel.

### Bước 2: Khởi động Apache

Trong XAMPP Control Panel, khởi động dịch vụ:

- Apache

Apache được sử dụng để chạy Website Joomla trên máy chủ Web cục bộ.

### Bước 3: Khởi động MySQL

Khởi động dịch vụ:

- MySQL

MySQL được sử dụng để lưu trữ cơ sở dữ liệu của Website Joomla.

---

## 4. Chuẩn bị cơ sở dữ liệu

Mở trình duyệt Web và truy cập:

`http://localhost/phpmyadmin`

Tạo một cơ sở dữ liệu mới dành cho Website Joomla.

Tên cơ sở dữ liệu sẽ được cập nhật theo cấu hình thực tế của Website.

---

## 5. Chuẩn bị Joomla

Tải bộ mã nguồn Joomla và giải nén vào thư mục Web của XAMPP.

Thông thường thư mục Website được đặt trong:

`C:\xampp\htdocs\`

Ví dụ:

`C:\xampp\htdocs\trungtamvieclam\`

Tên thư mục thực tế sẽ được cập nhật theo quá trình triển khai Website.

---

## 6. Cài đặt Joomla

Sau khi đặt mã nguồn Joomla vào thư mục Web, mở trình duyệt và truy cập Website thông qua:

`http://localhost/trungtamvieclam/`

Thực hiện các bước cài đặt Joomla theo trình hướng dẫn.

Các thông tin cần cấu hình gồm:

- Tên Website.
- Thông tin quản trị viên.
- Tên cơ sở dữ liệu.
- Tài khoản cơ sở dữ liệu.
- Mật khẩu cơ sở dữ liệu.
- Máy chủ cơ sở dữ liệu.

---

## 7. Cấu hình Website

Sau khi cài đặt Joomla thành công, tiến hành cấu hình:

- Thông tin Website.
- Giao diện.
- Menu.
- Category.
- Article.
- Module.
- Plugin.
- Media.
- User và phân quyền.

---

## 8. Xây dựng nội dung Website

Website dự kiến gồm các nhóm nội dung:

- Trang chủ.
- Giới thiệu Trung tâm.
- Việc làm.
- Nhà tuyển dụng.
- Tin tuyển dụng.
- Tin tức.
- Thông tin dành cho người tìm việc.
- Liên hệ.

Nội dung thực tế sẽ được cập nhật trong quá trình xây dựng Website.

---

## 9. Kiểm thử Website
Sau khi hoàn thành việc cấu hình và xây dựng nội dung, tiến hành kiểm thử:

- Kiểm tra giao diện Website.
- Kiểm tra menu.
- Kiểm tra liên kết.
- Kiểm tra nội dung.
- Kiểm tra hiển thị trên trình duyệt.
- Kiểm tra chức năng quản trị.
- Kiểm tra cơ sở dữ liệu.

---

## 10. Sao lưu và phục hồi

Thực hiện sao lưu:

- Mã nguồn Website Joomla.
- Cơ sở dữ liệu.
- Các nội dung và cấu hình quan trọng.

Sau khi sao lưu, thực hiện kiểm tra khả năng phục hồi để đảm bảo Website có thể được khôi phục khi cần thiết.

---

## 11. Cấu trúc thư mục setup

```text
setup/
├── .gitkeep
└── README.md