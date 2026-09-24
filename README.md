Thành viên và phân công

Thành viên 1	@Chgtsuki2	Authentication, Account, Movie, Category, Cinema, Room, Seat

Thành viên 2	@APONIA	Showtime, Booking, Payment, Notification, Frontend User, Admin Dashboard

------------------------------------------------------------------------
Thành viên 1: @Chgtsuki2

Service (thư mục)	Chức năng bên trong

auth-service	Authentication: đăng ký, đăng nhập, xác thực người dùng

Account: quản lý tài khoản, thông tin người dùng

movie-service	Movie: quản lý phim

Category: quản lý thể loại phim

cinema-service	Cinema: quản lý rạp chiếu

Room: quản lý phòng chiếu

Seat: quản lý ghế trong phòng

------------------------------------------------------------------------

Thành viên 2: APONIA

Service (thư mục)	Chức năng bên trong

showtime-service	Showtime: quản lý suất chiếu

booking-service	Booking: đặt vé, giữ ghế, quản lý đơn đặt vé

payment-service	Payment: thanh toán cho đơn đặt vé

notification-service	Notification: gửi thông báo cho người dùng

cinema-client	Frontend User: giao diện dành cho khách hàng

Admin Dashboard: giao diện quản trị

--------------------------------------------------------------------------
Các thành phần dùng chung

api-gateway	Cổng vào chung, định tuyến request tới các service

discovery-server	Đăng ký và tìm kiếm các service

database	Script khởi tạo cơ sở dữ liệu

scripts	Các script hỗ trợ chạy và triển khai

postman	Bộ collection Postman để thử API

verification	Tài liệu / công cụ kiểm tra chức năng

uploads	Thư mục chứa file được tải lên (ảnh, poster...)
