Giới thiệu
Đây là một ứng dụng web đơn giản cho phép người dùng mã hóa và giải mã file dữ liệu (ảnh, Word, Excel, PDF,...) bằng thuật toán AES (Advanced Encryption Standard). Ứng dụng hỗ trợ mã hóa bảo mật bằng mã khóa tùy chọn của người dùng, đồng thời cung cấp giao diện hiện đại, dễ sử dụng.
Chức năng chính
• Mã hóa file với thuật toán AES (CBC mode).
• Giải mã file đã được mã hóa bằng AES.
• Nhập mã khóa tùy chọn (password) khi mã hóa/giải mã.
• Xem trước nội dung file dưới dạng Base64.
• Hiển thị nội dung kết quả mã hóa hoặc giải mã ngay trên giao diện.
• Cho phép tải về file kết quả sau khi xử lý.
• Giao diện hiện đại, dễ sử dụng, hỗ trợ responsive trên mobile.
Công nghệ sử dụng
Thành phần	Công nghệ
Giao diện người dùng	HTML5, CSS3 (Responsive), JavaScript
Mã hóa/giải mã	CryptoJS – AES (CBC, SHA256, PKCS7 Padding)
Xử lý file	FileReader API, Blob API, Base64 encoding
Trình duyệt hỗ trợ	Chrome, Firefox, Edge, Safari
Giao diện chương trình

![image](https://github.com/user-attachments/assets/3218479e-7cfa-4efe-88c7-d5b12cd7d4da)


Cách sử dụng
1. Nhập mã khóa tùy chọn.
2. Chọn chế độ mã hóa hoặc giải mã.
3. Chọn file bất kỳ (ảnh, tài liệu, v.v).
4. Nhấn "Thực hiện" để xử lý.
5. Xem kết quả và nhấn "Tải file kết quả" để tải về.
Ghi chú bảo mật
• Mã khóa được người dùng nhập và không được lưu trữ ở bất kỳ đâu.
• Toàn bộ quá trình mã hóa/giải mã được thực hiện hoàn toàn trên trình duyệt, không gửi dữ liệu ra ngoài.

# baitapAES
