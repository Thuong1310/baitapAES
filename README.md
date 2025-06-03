<h1><b>Giới thiệu</b></h1>h1><br>
Đây là một ứng dụng web đơn giản cho phép người dùng mã hóa và giải mã file dữ liệu (ảnh, Word, Excel, PDF,...) bằng thuật toán AES (Advanced Encryption Standard). Ứng dụng hỗ trợ mã hóa bảo mật bằng mã khóa tùy chọn của người dùng, đồng thời cung cấp giao diện hiện đại, dễ sử dụng.<br>
<b>Chức năng chính:</b><br>
• Mã hóa file với thuật toán AES.<br>
• Giải mã file đã được mã hóa bằng AES.<br>
• Nhập mã khóa tùy chọn (password) khi mã hóa/giải mã.<br>
• Xem trước nội dung file dưới dạng Base64.<br>
• Hiển thị nội dung kết quả mã hóa hoặc giải mã ngay trên giao diện.<br>
• Cho phép tải về file kết quả sau khi xử lý.<br>
• Giao diện hiện đại, dễ sử dụng, hỗ trợ responsive trên mobile.<br>
<h2><b>Công nghệ sử dụng:</b></h2><br>
Thành phần	Công nghệ:<br>
Giao diện người dùng	HTML5, CSS3 (Responsive), JavaScript<br>
Mã hóa/giải mã	CryptoJS – AES (CBC, SHA256, PKCS7 Padding)<br>
Xử lý file	FileReader API, Blob API, Base64 encoding<br>
Trình duyệt hỗ trợ	Chrome, Edge<br>
Giao diện chương trình: 

![image](https://github.com/user-attachments/assets/3218479e-7cfa-4efe-88c7-d5b12cd7d4da)


<h1><b></b>Cách sử dụng:</h1></b><br>
1. Nhập mã khóa tùy chọn.<br>
2. Chọn chế độ mã hóa hoặc giải mã.<br>
3. Chọn file bất kỳ (ảnh, tài liệu, v.v).<br>
4. Nhấn "Thực hiện" để xử lý.<br>
5. Xem kết quả và nhấn "Tải file kết quả" để tải về.<br>
Ghi chú bảo mật:<br>
• Mã khóa được người dùng nhập và không được lưu trữ ở bất kỳ đâu.<br>
• Toàn bộ quá trình mã hóa/giải mã được thực hiện hoàn toàn trên trình duyệt, không gửi dữ liệu ra ngoài.<br>

# baitapAES
