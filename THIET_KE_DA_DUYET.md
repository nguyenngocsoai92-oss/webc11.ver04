# Trang chủ và hồ sơ hội viên — bản đã triển khai

Ngày cập nhật: 23/09/2026. Cấu trúc dựa trên YC WEB 2.xlsx và mockup được duyệt trong tác vụ này.

## Xem giao diện

- `index.html`: trang chủ đỏ mận, buổi họp gần nhất, 4 thao tác nhanh, tổng quan, BĐH, hội viên, hoạt động và quy trình.
- Bấm Tổng quan VBNA, BĐH các nhiệm kỳ, Hội viên hoặc Các hoạt động để mở menu chi tiết. Bàn phím: Tab, Enter và Escape. Mobile có nút Menu.
- `members.html`: tìm theo tên, doanh nghiệp, ngành nghề và Power Team.
- `member-profile.html?id=C11-0003`: ví dụ hồ sơ công khai lấy từ dữ liệu chạy thử sẵn có. Số điện thoại che 3 số giữa. Không hiển thị địa chỉ nhà riêng, email, tài chính hoặc cơ hội cá nhân.
- `member-portal.html`: trang riêng sau đăng nhập. Có Tổng quan, Hồ sơ, Cơ hội, Tài chính, Điểm danh và Thông báo. Trên điện thoại có thanh điều hướng cố định ở dưới.
- `about.html`, `leadership.html`, `meeting-process.html`, `member-map.html`, `meeting-summary.html`: các trang con của menu đã duyệt.
- `media.html#video` và `media.html#album`: hai luồng hoạt động riêng.

## Thử trang riêng

Tài khoản hội viên mẫu kế thừa bản trước: `0978219198` / `Member123`. Lần đầu yêu cầu đổi mật khẩu. Nếu tài khoản này đã được đổi mật khẩu trên trình duyệt đang dùng, tiếp tục dùng mật khẩu đã đổi.

Trang riêng chỉ đọc hồ sơ theo tài khoản đang đăng nhập; tham số ID trên URL không chọn được hồ sơ riêng của hội viên khác. Cập nhật hồ sơ vẫn đi qua phê duyệt; xác nhận cơ hội vẫn dùng quy trình lưu dữ liệu hiện có. Không có nút Lucky Draw cho hội viên.

## Phạm vi dữ liệu

Đây là bản chạy thử cục bộ, chưa có máy chủ đăng nhập, dữ liệu hoặc phân quyền thật. Web desktop và mobile đọc cùng mô hình dữ liệu của V6, nhưng trình duyệt trên các thiết bị khác nhau chưa đồng bộ. Không thay đổi tài khoản hay dữ liệu thật trong quá trình kiểm thử; các thử nghiệm dùng phiên trình duyệt độc lập.

Giữ các dữ liệu đang thiếu ở trạng thái chờ cập nhật: ảnh đại diện, video, album, danh sách nhân sự lịch sử và quan hệ sơ đồ các ban. Bản đồ chưa hiển thị địa chỉ nhà vì chưa có quyền xem và tọa độ được xác nhận. Lịch họp và hồ sơ mặc định kế thừa dữ liệu chạy thử V6, không phải thông tin chính thức mới.

## Thay đổi và kiểm tra

Mã giao diện mới ở `src/approved-design.js`, kiểu trình bày ở `approved-design.css`. Bộ build đưa module này vào cuối `app.js` sau các module V6. Những luồng quản trị, tài chính và xử lý hồ sơ hiện có được tái sử dụng.

Kiểm tra bằng trình duyệt tại các chiều rộng 1440, 768 và 390 px: menu, bàn phím, danh sách lọc, che số điện thoại, không xuất địa chỉ nhà vào hồ sơ public, chuyển đăng nhập, phạm vi dữ liệu cá nhân, xác nhận cơ hội, cập nhật chờ duyệt, 20 bước và trạng thái không có buổi họp. Ảnh chụp và kết quả kiểm tra nằm trong `outputs/homepage-desktop-review/implemented` ở thư mục dự án.
