# HƯỚNG DẪN CÀI ĐẶT JOOMLA

## 1. Mục đích

Tài liệu này hướng dẫn quá trình chuẩn bị môi trường và cài đặt Joomla phục vụ đề tài:

**TÌM HIỂU JOOMLA VÀ THIẾT KẾ WEBSITE GIỚI THIỆU THÔNG TIN TRUNG TÂM GIỚI THIỆU VIỆC LÀM**

Joomla được sử dụng làm hệ quản trị nội dung (CMS) để xây dựng và quản lý Website giới thiệu thông tin Trung tâm Giới thiệu việc làm.

Website được triển khai trước tiên trên môi trường máy chủ Web cục bộ để phục vụ quá trình nghiên cứu, thiết kế, kiểm thử và hoàn thiện.

---

## 2. Mục tiêu cài đặt

Quá trình cài đặt nhằm:

- Chuẩn bị môi trường máy chủ Web cục bộ.
- Cài đặt và cấu hình Apache.
- Cài đặt và cấu hình PHP.
- Cài đặt và cấu hình MySQL/MariaDB.
- Chuẩn bị cơ sở dữ liệu cho Joomla.
- Cài đặt Joomla.
- Thiết lập tài khoản quản trị.
- Kiểm tra Website sau khi cài đặt.
- Chuẩn bị môi trường để thiết kế và quản trị Website.

---

## 3. Môi trường sử dụng

Môi trường triển khai dự kiến gồm:

- Hệ điều hành: Windows.
- XAMPP.
- Apache.
- PHP.
- MySQL hoặc MariaDB.
- phpMyAdmin.
- Joomla CMS.
- Trình duyệt Web.

Phiên bản cụ thể của Joomla, PHP, MySQL/MariaDB và XAMPP sẽ được cập nhật sau khi quá trình cài đặt thực tế hoàn thành.

---

## 4. Chuẩn bị XAMPP

### 4.1. Cài đặt XAMPP

XAMPP được sử dụng để tạo môi trường máy chủ Web cục bộ.

Sau khi cài đặt XAMPP, mở **XAMPP Control Panel**.

Kiểm tra các thành phần:

- Apache.
- MySQL.

### 4.2. Khởi động Apache

Trong XAMPP Control Panel:

1. Mở XAMPP.
2. Tìm dòng **Apache**.
3. Chọn **Start**.
4. Kiểm tra Apache đã chạy.

Apache có nhiệm vụ cung cấp Web Server để Website Joomla có thể hoạt động trên máy tính cục bộ.

### 4.3. Khởi động MySQL/MariaDB

Trong XAMPP Control Panel:

1. Tìm dòng **MySQL**.
2. Chọn **Start**.
3. Kiểm tra MySQL đã chạy.

MySQL/MariaDB được sử dụng để lưu trữ dữ liệu của Website Joomla.

---

## 5. Kiểm tra Web Server

Sau khi Apache được khởi động, mở trình duyệt Web.

Truy cập:

```text
http://localhost/
Nếu trang XAMPP xuất hiện, môi trường Web Server đã hoạt động.
## 6. Kiểm tra phpMyAdmin

Mở trình duyệt và truy cập:

http://localhost/phpmyadmin/

phpMyAdmin được sử dụng để:

- Quản lý cơ sở dữ liệu.
- Tạo cơ sở dữ liệu.
- Kiểm tra bảng dữ liệu.
- Sao lưu cơ sở dữ liệu.
- Phục hồi cơ sở dữ liệu.

Nếu phpMyAdmin mở được, hệ quản trị cơ sở dữ liệu đã sẵn sàng.

---

## 7. Chuẩn bị Joomla

Tải bộ cài Joomla phù hợp với môi trường triển khai.

Sau khi tải bộ cài Joomla, giải nén vào thư mục Web của XAMPP.

Thông thường thư mục Website được đặt trong:

C:\xampp\htdocs\

Ví dụ:

C:\xampp\htdocs\trungtamvieclam\

Trong đó có thể gồm các thư mục:

trungtamvieclam/
├── administrator/
├── api/
├── cache/
├── components/
├── images/
├── language/
├── libraries/
├── media/
├── modules/
├── plugins/
├── templates/
└── ...

Cấu trúc thực tế có thể thay đổi tùy theo phiên bản Joomla được sử dụng.

---

## 8. Tạo cơ sở dữ liệu Joomla

Mở:

http://localhost/phpmyadmin/

Thực hiện tạo một cơ sở dữ liệu dành cho Website.

Tên cơ sở dữ liệu đề xuất:

trungtamvieclam

Thông tin cơ sở dữ liệu sẽ được sử dụng trong quá trình cài đặt Joomla.

### Thông tin cần ghi nhận

Database name: trungtamvieclam
Database type: MySQL/MariaDB
Database host: localhost
Database user: root
Database password:

Mật khẩu cơ sở dữ liệu sẽ được cập nhật theo cấu hình thực tế của môi trường XAMPP.

---

## 9. Cài đặt Joomla

Sau khi Apache và MySQL/MariaDB đã hoạt động, mở trình duyệt.

Truy cập Website Joomla thông qua:

http://localhost/trungtamvieclam/

Nếu bộ cài Joomla hoạt động, tiến hành các bước cài đặt.

### 9.1. Chọn ngôn ngữ

Chọn ngôn ngữ sử dụng trong quá trình cài đặt.

Dự kiến sử dụng:

Tiếng Việt

hoặc ngôn ngữ phù hợp với quá trình triển khai.

### 9.2. Nhập thông tin Website

Nhập thông tin Website:

Tên Website:
Trung tâm Giới thiệu việc làm

Mô tả:
Website giới thiệu thông tin Trung tâm Giới thiệu việc làm,
việc làm, nhà tuyển dụng, tin tuyển dụng và thông tin dành
cho người tìm việc.

Thông tin có thể được điều chỉnh trong quá trình thiết kế Website.

### 9.3. Tạo tài khoản quản trị

Thiết lập tài khoản quản trị Joomla.

Thông tin tài khoản:

Tên quản trị viên:
Lê Thị Như

Tên đăng nhập:
[Thiết lập trong quá trình cài đặt]

Mật khẩu:
[Thiết lập trong quá trình cài đặt]

Email:
[Thiết lập trong quá trình cài đặt]

Không lưu mật khẩu thật vào Repository GitHub.

---

## 10. Cấu hình cơ sở dữ liệu
Trong bước cấu hình cơ sở dữ liệu của Joomla, nhập thông tin tương ứng với cơ sở dữ liệu đã tạo.

Thông tin dự kiến:

Database Type:
MySQLi

Host Name:
localhost

Username:
root

Password:
[Theo cấu hình XAMPP]

Database Name:
trungtamvieclam

Table Prefix:
[Để Joomla tự tạo hoặc sử dụng giá trị mặc định]

Sau đó tiếp tục quá trình cài đặt.

---

## 11. Hoàn tất cài đặt

Sau khi Joomla hoàn tất quá trình cài đặt:

1. Kiểm tra Website phía người dùng.
2. Kiểm tra trang quản trị.
3. Kiểm tra kết nối cơ sở dữ liệu.
4. Kiểm tra giao diện mặc định.
5. Kiểm tra khả năng đăng nhập quản trị.

Trang Website:

http://localhost/trungtamvieclam/

Trang quản trị:

http://localhost/trungtamvieclam/administrator/

Đường dẫn thực tế có thể thay đổi tùy theo tên thư mục Website.

---

## 12. Kiểm tra sau khi cài đặt

Sau khi cài đặt Joomla thành công, tiến hành kiểm tra:

### 12.1. Kiểm tra Website

- Website có truy cập được hay không.
- Trang chủ có hiển thị hay không.
- Hình ảnh và tài nguyên có tải được hay không.
- Giao diện có hoạt động hay không.

### 12.2. Kiểm tra trang quản trị

- Có đăng nhập được hay không.
- Trang quản trị có hiển thị đầy đủ hay không.
- Có tạo được Article hay không.
- Có tạo được Category hay không.
- Có tạo được Menu hay không.
- Có quản lý được Media hay không.

### 12.3. Kiểm tra cơ sở dữ liệu

Mở:

http://localhost/phpmyadmin/

Kiểm tra cơ sở dữ liệu Joomla đã được tạo và có các bảng dữ liệu.

---

## 13. Cấu trúc thư mục setup

Thư mục setup trong Repository được sử dụng để lưu các tài liệu phục vụ quá trình cài đặt và cấu hình Joomla.

Cấu trúc:

setup/
├── .gitkeep
└── README.md

Trong đó:

- .gitkeep: Giữ thư mục trong Git khi thư mục chưa có nhiều tài liệu.
- README.md: Giới thiệu và mô tả quá trình chuẩn bị môi trường và cài đặt Joomla.

Các tài liệu hoặc hình ảnh hướng dẫn bổ sung có thể được thêm vào thư mục setup trong quá trình thực hiện đồ án.

---

## 14. Ghi nhận phiên bản sử dụng

Sau khi cài đặt thực tế hoàn thành, cập nhật thông tin phiên bản tại đây.

XAMPP:
[Chưa cập nhật]

Apache:
[Chưa cập nhật]

PHP:
[Chưa cập nhật]

MySQL/MariaDB:
[Chưa cập nhật]

Joomla:
[Chưa cập nhật]

Không tự điền phiên bản khi chưa kiểm tra trên máy thực tế.

---

## 15. Sao lưu

Trong quá trình thực hiện đồ án, cần thực hiện sao lưu Website và cơ sở dữ liệu.

Các nội dung cần sao lưu:

- Mã nguồn Website Joomla.
- Hình ảnh.
- Media.
- Template.
- Extensions.
- Cơ sở dữ liệu.

Thông tin sao lưu sẽ được cập nhật sau khi Website được triển khai hoàn chỉnh.

---

## 16. Phục hồi

Khi cần phục hồi Website, thực hiện:

1. Khôi phục mã nguồn Website.
2. Khôi phục cơ sở dữ liệu.
3. Kiểm tra cấu hình kết nối cơ sở dữ liệu.
4. Khởi động Apache.
5. Khởi động MySQL/MariaDB.
6. Truy cập Website.
7. Kiểm tra các chức năng.

Quy trình phục hồi thực tế sẽ được ghi nhận trong quá trình thực hiện đồ án.

---

## 17. Lưu ý bảo mật

Không đưa các thông tin nhạy cảm lên GitHub.

Không lưu:

- Mật khẩu tài khoản quản trị Joomla.
- Mật khẩu cơ sở dữ liệu.
- Thông tin tài khoản cá nhân.
- File cấu hình chứa thông tin nhạy cảm.
- Dữ liệu cá nhân của người dùng.

Các thông tin nhạy cảm cần được cấu hình trực tiếp trên môi trường triển khai.

---

## 18. Trạng thái thực hiện

| Nội dung | Trạng thái |
|---|---|
| Chuẩn bị XAMPP | Đang thực hiện |
| Cài đặt Apache | Đang thực hiện |
| Cài đặt MySQL/MariaDB | Đang thực hiện |
| Chuẩn bị Joomla | Đang thực hiện |
| Tạo cơ sở dữ liệu | Chưa thực hiện |
| Cài đặt Joomla | Chưa thực hiện |
| Cấu hình Website | Chưa thực hiện |
| Kiểm thử Website | Chưa thực hiện |
| Sao lưu Website | Chưa thực hiện |
| Phục hồi Website | Chưa thực hiện |

Trạng thái sẽ được cập nhật theo tiến độ thực tế của đồ án.

---

## 19. Ghi chú

Các thông tin về phiên bản Joomla, XAMPP, PHP, MySQL/MariaDB, cấu hình Website và quá trình cài đặt sẽ được cập nhật sau khi thực hiện thực tế.

Tài liệu này là một phần của Repository phục vụ đề tài:

TÌM HIỂU JOOMLA VÀ THIẾT KẾ WEBSITE GIỚI THIỆU THÔNG TIN TRUNG TÂM GIỚI THIỆU VIỆC LÀM

Sinh viên thực hiện:

Lê Thị Như

Lớp:

DX24TT8

Trường:

Đại học Trà Vinh

Năm thực hiện:

2026