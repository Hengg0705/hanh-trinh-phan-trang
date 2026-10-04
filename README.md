# HÀNH TRÌNH PHẤN TRẮNG — SƯ PHẠM VĂN
## Release candidate: Web 3D RPG

### Có gì trong bản này?
- 3D campus bằng Three.js, nhân vật chính + 4 NPC.
- NPC giảng viên/sinh viên với hội thoại.
- Bản đồ: Thư viện, Khoa Ngữ văn, Giảng đường, khu thực tập, sân trường.
- Hệ thống nhiệm vụ.
- Chỉ số C/S/D/E.
- GPA 4.0.
- Nhiều câu hỏi Ngữ văn và phương pháp dạy học.
- 6 học kỳ đại học + 12 tuần thực tập + học kỳ 8 + bảo vệ khóa luận + lễ tốt nghiệp.
- Lưu/tiếp tục bằng localStorage trên thiết bị.
- Thiết kế responsive để chơi trên điện thoại.
- Có thể phát hành bằng một URL duy nhất.

### Chạy
Mở `index.html` khi có Internet. Three.js được tải từ CDN.

### Phát hành
Đây là game web tĩnh nên có thể host trên GitHub Pages, Netlify, Vercel hoặc dịch vụ hosting tĩnh tương tự.
Sau khi host, URL trang `index.html` chính là URL phát hành duy nhất.

### QR
Không thể tạo QR “công khai” trước khi có URL hosting. Sau khi có URL, tạo QR trỏ thẳng đến URL đó. Người dùng quét QR sẽ mở game trên điện thoại.

### Lưu ý
Bản này là một vertical-slice/release candidate, chưa phải sản phẩm AAA. Nhân vật hiện được dựng procedural bằng Three.js để package nhẹ và không cần tải model bản quyền.
