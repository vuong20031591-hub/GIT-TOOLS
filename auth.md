# User Authentication

## Tính năng
- Đăng ký tài khoản mới
- Đăng nhập
- Đăng xuất
- Quên mật khẩu
- Xác thực email

## Luồng đăng ký
1. Người dùng điền form (email, password, name)
2. Hệ thống validate dữ liệu
3. Gửi email xác thực
4. Người dùng xác nhận email
5. Tài khoản được kích hoạt

## Luồng đăng nhập
1. Nhập email và password
2. Hệ thống kiểm tra thông tin
3. Tạo session/token
4. Chuyển đến trang chủ
