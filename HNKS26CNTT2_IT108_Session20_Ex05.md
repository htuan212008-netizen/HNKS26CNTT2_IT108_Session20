# Bài 5 : Xây dựng cơ chế xác thực an toàn cho Crypto Wallet
- Thiết kế kiến trúc

Lớp 1: MFA/OTP chặn đăng nếu thiếu mã OTP thay đổi sau mỗi 30s

Lớp 2: Sinh trắc học quét vân tay hoặc mặt

Lớp 3: Lưu khoá bí mật trong chip phần cứng biệt lâập, tự động khoá phiên khi không hoạt động

- Xử lý bẫy

Giải pháp: Sử dụng thuật toán TOTP

Ứng dụng Authenticator tự động gửi OTP dựa trên thời gian thực
