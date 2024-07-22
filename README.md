# Hướng Dẫn Sử Dụng Công Cụ Tự Động Tính Điểm Cho Sinh Viên FPTU

**Lưu Ý:** Hiện tại chỉ áp dụng cho sinh viên từ K18 trở lên có mail FPT.

## Bước 1: Tạo Mã Xác Thực 2 Yếu Tố Cho Tài Khoản Google
1. Đăng nhập vào tài khoản Google của bạn.
2. Truy cập vào [trang quản lý bảo mật của Google](https://myaccount.google.com/security).
3. Chọn "Xác minh 2 bước".
4. Chọn "Thêm ứng dụng xác thực"
5. Chọn "Không thể quét mã?"
6. Lưu lại mã xác thực 2 yếu tố (24 ký tự) để sử dụng ở các bước sau.
7. Sử dụng các ứng dụng xác thực như "Authenticator" để sử dụng mã xác thực.
8. Nhập mã 6 số được tạo từ ứng dụng xác thực.

## Bước 2: Mở File `config.txt` và Điều Chỉnh Thông Số Như Sau
- `campus`: theo format FU-[Tên thành phố của campus bạn đang học]
- `username`: mail FPT của bạn
- `password`: mật khẩu mail
- `secret_key`: mã xác thực 2 yếu tố khi tạo ở Bước 1 (24 ký tự)
- `number_of_credits`: tổng số tín chỉ, mỗi chuyên ngành mỗi khác (Mặc định ngành AI là 132)

## Bước 3: Lấy Dữ Liệu
1. Chạy file `getFAP.exe` và chờ nó chạy hết.
2. Sau khi chạy xong, dữ liệu sẽ lưu vào file `transcript.csv`.

## Bước 4: Tính Điểm Dựa Vào Dữ Liệu
1. Chạy file `GPA.exe`.
2. Điểm sẽ được lưu vào file `gpa.png`. Bạn có thể mở file để xem điểm đã qua tính toán.
