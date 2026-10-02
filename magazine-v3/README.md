# Gamuda Central Park — Magazine v3

Mở index.html trong trình duyệt. File đã nhúng ảnh và StPageFlip 2.0.7 nên không cần mạng, CDN hoặc build để đọc. Khung xem trước tệp có thể chặn JavaScript; cần mở trong trình duyệt hỗ trợ hoặc đưa index.html lên hosting HTTPS.

## Trải nghiệm
- Bìa cứng riêng, 10 trang nội dung, bìa cuối.
- Giấy mềm: kéo góc trang, bóng đổ, mặt sau, thả lại để hủy lật.
- Máy tính: trang đôi; điện thoại: một trang.
- Phím trái/phải, nút điều hướng, mục lục.
- Phóng to mặt bằng; thông tin sale; xuất bản HTML độc lập.
- Chế độ đọc tĩnh trong Thông tin; tôn trọng giảm chuyển động khi dùng nút/phím.

## Giới hạn
Đây là mô phỏng giấy trên màn hình, không phải mô hình vật lý hoàn toàn chính xác. Chưa đăng lên hosting. Chưa có CMS, form thu lead hay phân quyền. Chưa kiểm tra trên thiết bị iPhone/Safari thật; đã kiểm tra bằng Chromium ở 1440px và 390px, thao tác kéo, hủy lật, chuyển trang, mục lục, phóng to, xuất file và mở lại.

## Hình ảnh và nội dung
Nguồn tham khảo: https://www.gamudacityhanoi.com/central-park/
- https://www.gamudacityhanoi.com/media/2120/gamuda-central-park-yen-so.jpg
- https://www.gamudacityhanoi.com/media/2123/cong-vien-va-khu-vui-choi-central-park-yen-so.jpg
- https://www.gamudacityhanoi.com/media/2103/mat-bang-central-park-gamuda.png

Chưa xác minh nguồn là chủ đầu tư hoặc các ảnh/mặt bằng là phiên bản được duyệt. Ảnh chỉ dùng trong bản thiết kế thử và có chú thích ngay trên trang. Cần thay/duyệt bộ tài liệu chính thức trước khi phát hành cho khách. Không đưa giá, tiến độ, chính sách vay hay cam kết đầu tư không được xác minh.

## Mã nguồn
index.html là bản chạy độc lập. template.html và build.py là nguồn biên tập. Để build lại: npm install page-flip@2.0.7, sau đó python3 build.py. build.py sẽ ghi index.html và một bản HTML ở thư mục cha. assets chứa ảnh gốc. THIRD-PARTY-LICENSE.txt là giấy phép MIT của thư viện lật trang.
