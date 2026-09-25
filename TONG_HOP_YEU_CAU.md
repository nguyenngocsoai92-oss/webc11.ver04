# VBNA Chapter 11 — tổng hợp yêu cầu và định hướng hoàn thiện

Cập nhật 23/09/2026. Tài liệu tổng hợp yêu cầu trong cuộc trao đổi “Thiết kế hệ thống quản trị”, bảng 132 đầu mục, nội dung bổ sung ngày 17/09, YC WEB 2.xlsx và các điều chỉnh đã duyệt trong tác vụ hiện tại. Đây là phạm vi sản phẩm; không phải xác nhận rằng mọi chức năng đã triển khai hoàn chỉnh.

## 1. Định hướng mới nhất

Website gồm ba không gian liên kết: website công khai của Chapter; catalog năng lực công khai của từng hội viên; cổng làm việc riêng của hội viên và các ban. Khách ngoài xem thông tin public và tham gia các luồng được cho phép, không tự có tài khoản nội bộ.

Giao diện phải có chất lượng thương mại: bố cục rõ, ảnh lớn có chọn lọc, nội dung có thứ bậc, chữ dễ đọc bằng tiếng Việt, đồng nhất một hệ màu đỏ mận. Bản mới dùng Arial / Helvetica Neue / Helvetica sans-serif, bỏ tiêu đề serif trên nội dung giao diện. Logo hoặc hình ảnh doanh nghiệp giữ bản sắc riêng trong vùng ảnh, không đổi toàn bộ ứng dụng theo màu từng hội viên.

**Tổng quan VBNA: giữ nguyên câu từ.** Nội dung từ Sheet1!F2 của YC WEB 2.xlsx được lưu riêng nguyên văn. Giữ cả cách viết “Success Refferals”, “New Refferals”, hoa/thường, dấu câu và những câu chưa chuẩn ngữ pháp. Chỉ chuyển ký hiệu Markdown thành định dạng, chia khối, cỡ chữ và khoảng cách; không biên tập lại nội dung. Lời dẫn của tài liệu đặt trong phần có thể mở xem, tách khỏi nội dung thương hiệu.

Catalog công khai là hồ sơ năng lực có câu chuyện cá nhân, doanh nghiệp, ngành nghề, năng lực, ảnh và sản phẩm mẫu. Trang riêng là nơi hội viên biên tập, lưu nháp, xem trước, gửi duyệt, nhận thông báo và theo dõi hoạt động.

## 2. Quy tắc khi yêu cầu thay đổi qua các phiên

| Chủ đề | Yêu cầu đang áp dụng / điểm cần phân biệt |
|---|---|
| Màu và chữ | Điều chỉnh mới nhất ưu tiên hệ đỏ mận đồng nhất và chữ sans-serif; các yêu cầu cũ về đỏ tươi hoặc vàng trang trí không áp dụng cho thiết kế mới |
| VBNA | Yêu cầu mới nhất cấm sửa câu từ; các bản tóm tắt trước đó được thay bằng nguyên văn trong trang Tổng quan |
| Public / nội bộ | “Public nội bộ” là tất cả hội viên C11 đã đăng nhập được xem; không phải khách Internet tự do truy cập |
| Lucky Draw | Không có công cụ Lucky Draw cho hội viên thường; bước 17 của quy trình họp vẫn được giới thiệu công khai |
| Phí gia nhập | Bổ sung sau: hội viên mới 4.500.000đ; tái phí 3.000.000đ; phần trăm tri ân tính trên 3.000.000đ |
| Phí quỹ | Mặc định 500.000đ/tháng, nộp ngày 01–10; Thư ký có thể đề nghị thay đổi theo cơ chế duyệt |
| Họp / điểm danh | Quy tắc vận hành bổ sung: bắt đầu 13:30, sau 14:00 là muộn. Giữ nguyên mốc 08:00 & 14:00 trong nội dung 20 bước do nguồn yêu cầu, không tự sửa tài liệu thành lịch họp thực tế |
| Tên miền | Trao đổi đầu là vbna.chapter11.vn; tài liệu bổ sung ghi vbna.chapter11.com; giao diện đã duyệt đang ghi .vn. Cấu hình V6 kế thừa .com. Cần chốt tên miền chính trước khi cấu hình triển khai/QR chính thức, không tự thay DNS |
| Nhạc quay | Yêu cầu sau thay nhạc nền ban đầu bằng video YouTube đã cung cấp, có phát/dừng/tiếp tục |
| Dữ liệu | Desktop và mobile dùng cùng quy tắc, hồ sơ, buổi họp, cơ hội và quyền. Lưu trong trình duyệt hiện tại chưa đạt đồng bộ máy chủ giữa thiết bị |

## 3. Website công khai

Thanh menu: Trang chủ; Tổng quan VBNA; BĐH các nhiệm kỳ; Hội viên; Các hoạt động; 20 bước buổi họp. Nút riêng Đăng ký khách mời và Đăng nhập hội viên. Dropdown có thể sử dụng chuột, bàn phím và chạm trên điện thoại.

Trang chủ: banner thương hiệu; buổi họp gần nhất; Đăng ký khách mời / Điểm danh / Trao cơ hội / Báo cáo sơ bộ; Tổng quan VBNA; BĐH theo nhiệm kỳ; hội viên và điểm vào bản đồ; Video / Album; giới thiệu quy trình 20 bước; lời mời đăng ký; chân trang.

Các yêu cầu cấu hình từ các phiên trước cần duy trì: upload logo trái/phải; ảnh trang chủ có căn riêng desktop/mobile; slogan và dòng giới thiệu có quyền cập nhật; thông tin liên hệ Ban Khách mời; ngành nghề đang mở theo Power Team; giới thiệu Chapter 11; HĐSL và BĐH có tên, chức danh, ảnh. Trang chủ mới ưu tiên thứ tự theo YC WEB 2.xlsx; các danh mục quản trị không bị xóa chỉ vì không nằm trên trang chủ.

Tổng quan VBNA phải đầy đủ: tên tổ chức, các mục tiêu kết nối; mục đích và triết lý; sứ mệnh; sản phẩm dịch vụ; 7 giá trị cốt lõi; 5 lợi ích; tiêu chuẩn gia nhập và 5 nhiệm vụ hàng tuần. Câu từ xem trực tiếp tại trang Tổng quan được dựng từ nguồn nguyên văn.

20 bước giữ đúng thứ tự và nội dung nguồn, bao gồm cả bước 10 báo cáo Trưởng ban Hội viên và bước 11 báo cáo Ban Hội viên. Không gộp hai bước này vì tên gần nhau.

## 4. Catalog năng lực công khai của hội viên

| Khối | Thông tin / hành động |
|---|---|
| Bìa | Ảnh bìa, thông điệp của doanh nghiệp, lĩnh vực, Power Team, liên kết xem sản phẩm và kết nối |
| Người đại diện | Ảnh cá nhân, họ tên, chức danh, doanh nghiệp |
| Giới thiệu cá nhân | Nội dung hội viên tự cung cấp về bản thân, định hướng nghề nghiệp, kinh nghiệm hoặc cách làm việc; không tự sinh thành tích |
| Doanh nghiệp | Tên, phần giới thiệu dài, logo, địa chỉ kinh doanh, website, email doanh nghiệp công khai nếu chủ hồ sơ điền |
| Ngành nghề / năng lực | Ngành chính, ngành phụ, sản phẩm dịch vụ giới thiệu ngắn, các năng lực nổi bật theo từng dòng |
| Sản phẩm mẫu | Tên, nhóm, mô tả và hình ảnh; mở xem chi tiết ảnh/sản phẩm; tối đa 12 mục trong bản biên tập hiện tại |
| Thư viện ảnh | Ảnh hoạt động, không gian, sản phẩm hoặc dự án do hội viên cung cấp; mỗi ảnh có chú thích; tối đa 8 ảnh trong bản hiện tại |
| Kết nối | Họ tên, doanh nghiệp, địa chỉ kinh doanh, SĐT che đúng 3 số giữa, email doanh nghiệp tùy chọn, tham dự buổi họp Chapter |

Không đưa lên catalog: email tài khoản mặc định, ngày sinh, địa chỉ nhà riêng, CCCD, GPLKD gốc, công nợ, thông báo cá nhân, chi tiết cơ hội và tài liệu riêng tư. Website/ảnh phải qua kiểm tra định dạng trước khi hiển thị. Hồ sơ không còn hoạt động không còn xuất hiện trong danh sách công khai.

Catalog minh họa dùng doanh nghiệp giả định và ảnh minh họa, không gán cho một hội viên thật và không tự điền vào dữ liệu hội viên. Những hồ sơ chưa có nội dung hiển thị trạng thái đang cập nhật, không giả lập thành tích.

## 5. Trang cá nhân riêng và quy trình cập nhật

Sáu mục: Tổng quan; Hồ sơ; Cơ hội; Tài chính; Điểm danh; Thông báo. Desktop có điều hướng bên trái; mobile có thanh công cụ phía dưới, nội dung thông báo vẫn có lối truy cập.

Trình biên tập Hồ sơ chia bốn phần: Cá nhân; Doanh nghiệp; Hình ảnh; Sản phẩm. Mỗi phần có hướng dẫn ngắn ngay tại trường nhập. Ảnh hỗ trợ JPG/PNG/WebP, tối đa 6 MB mỗi tệp, được tối ưu kích thước trước khi lưu thử nghiệm.

Luồng: **chỉnh sửa → lưu bản nháp → xem trước riêng tư → gửi Chủ tịch/Admin duyệt → công khai bản được duyệt → thông báo về hội viên**.

Bản nháp không thay đổi catalog đang public. Có thể tiếp tục nháp sau khi tải lại trang. Gửi một bản mới thay thế yêu cầu chờ duyệt cũ của cùng catalog để tránh duyệt nhầm nhiều bản. Người duyệt xem toàn bộ catalog, phê duyệt hoặc yêu cầu chỉnh sửa kèm lý do. Nếu hồ sơ gốc đã thay đổi từ lúc tạo nháp, chặn duyệt ghi đè và yêu cầu tạo lại bản mới. Có nút lấy lại hồ sơ đang công khai làm bản nháp mới.

Ngày sinh và địa chỉ nhà được cập nhật trong phần Cá nhân riêng tư và không hiển thị trên catalog. Ngày gia nhập/kết nạp/dừng, phí, CCCD/GPLKD/quyết định/tệp khác vẫn thuộc module quản trị hồ sơ riêng; không biến tài liệu nội bộ thành ảnh sản phẩm.

Báo cáo trong trang riêng: cơ hội trao/nhận, số buổi đã tham dự, công nợ của các khoản đã lập, lịch sử thanh toán, lịch sử điểm danh, thông báo của riêng hội viên; liên kết các dashboard Ban theo quyền.

## 6. Hội viên, tài khoản và tổ chức

Hồ sơ quản trị: thông tin cá nhân, doanh nghiệp, ngành nghề chính/phụ, Power Team, ngày gia nhập, kết nạp, dừng, lý do dừng; ảnh đại diện, mặt tiền, CCCD, GPLKD; quyết định và tối đa 10 tệp khác. Các thay đổi quan trọng có phê duyệt và lịch sử.

Tài khoản: phê duyệt hội viên rồi cấp tài khoản theo SĐT, mật khẩu tạm; bắt đổi lần đầu, tối thiểu 8 ký tự gồm chữ hoa, chữ thường, số. Admin/Chủ tịch khóa/mở/reset; dừng hoạt động dẫn đến khóa đăng nhập. Email chào mừng, email reset và thông báo đổi mật khẩu thuộc luồng máy chủ; bản hiện tại chỉ có mô phỏng/hộp thư nháp.

Danh mục tổ chức: HĐSL, HĐTV, Chủ tịch các Chapter, LT các Chapter; mỗi người có thông tin và vai trò, LT gắn Ban. Chapter do Admin/Chủ tịch cấu hình. Thành viên HĐSL và sơ đồ BĐH có bố cục ảnh theo chức danh; Chủ tịch ở giữa, Thư ký trái, Phó Chủ tịch phải theo yêu cầu lịch sử khi thể hiện sơ đồ hiện hành.

Nhiệm kỳ lịch sử: 2 Giám đốc mở và Trưởng ban định hướng; NK1–2 có 7 ban; NK3–6 có 8 ban; NK7 có 9 ban. Lộ trình các ban đi từ dưới lên. File chưa có danh sách nhân sự/quan hệ đầy đủ; không tự gán người hiện tại vào nhiệm kỳ cũ.

## 7. Chín Ban và dashboard

| Ban / vai trò | Phạm vi yêu cầu |
|---|---|
| Chủ tịch | Tổng quan và chi tiết từ các Ban, phê duyệt, xuất Excel/in báo cáo |
| Phó Chủ tịch | Hiện diện, muộn/về sớm, nghỉ ốm, đi thay, vắng, tỷ lệ hiện diện; tổng kết tuần; cơ hội/giá trị xác nhận; doanh số đầu kỳ và cộng dồn |
| Thư ký | Hồ sơ liên hệ, nghĩa vụ phí, gạch nợ, chia bill, thu chi/sổ quỹ/chứng từ, tài trợ, báo cáo và thư nhắc phí chờ duyệt |
| Đào tạo | Bài/tệp đào tạo theo tuần, người đào tạo và người đăng; chủ đề; like/dislike, ý kiến; báo cáo buổi, bài và tệp; hội viên được đăng bài |
| Khách mời | CRM, liên hệ được/chưa được; khách trong/ngoài VBNA; dữ liệu từ check-in và bổ sung có lý do; chuyển đổi hội viên; báo cáo thời gian |
| Sự kiện & Truyền thông | Tin/album/video, đối tượng nội bộ hoặc public, đánh dấu quan trọng, popup một lần; điều phối Lucky Draw |
| Phát triển | Power Team, hội viên từng nhóm, ngành nghề đang mở; 5 nhóm, còn thiếu tên chính thức của hai nhóm trong nguồn bổ sung |
| Định hướng | Thông báo và tài liệu định hướng cho đối tượng nội bộ, đánh dấu quan trọng, popup một lần |
| Giám đốc hỗ trợ | Dashboard theo phạm vi hỗ trợ, thông tin hoạt động của Chapter và các Ban |

Admin là quyền cao nhất. Chức danh hiển thị và quyền thao tác cần tách riêng. Thành viên Ban được quyền theo phân công, không chỉ dựa vào việc nhìn thấy menu. Phân quyền máy chủ là điều kiện để triển khai dữ liệu thật.

## 8. Cuộc họp, điểm danh và khách mời

Chủ tịch/Admin đặt tên, ngày, giờ, địa điểm, nhiệm kỳ/tuần; mỗi buổi họp có link public và mã QR riêng. QR in với logo, thông tin ngày họp và hướng dẫn.

Điểm danh không cần tài khoản khách: chọn HĐSL/HĐTV/Chủ tịch Chapter/hội viên Chapter/khách ngoài; người mời bởi; Chapter 11 thì chọn hội viên và tự điền hồ sơ; Chủ tịch Chapter chọn số Chapter. Chống trùng trong cùng buổi, ghi thời điểm, hội viên cần ảnh hiện diện. Có ghi nhận vắng/nghỉ ốm/đi thay/về sớm kèm lý do.

Đăng ký khách mời thu tên, SĐT, email, địa chỉ, ngành nghề, sản phẩm, loại hình cá nhân/HKD/doanh nghiệp, người giới thiệu. Vào CRM Ban Khách mời; theo dõi từ đăng ký, liên hệ, mời, tham dự, quan tâm, hồ sơ đến kết nạp; giữ lịch sử khi chuyển Guest thành Member và cảnh báo trùng ngành nghề.

## 9. Cơ hội, Referral và vinh danh

Phiếu public theo buổi họp; tự điền ngày; người trao và SĐT; một phiếu nhập nhiều người nhận, mỗi dòng là một cơ hội. Loại: Referral 1–5, Dance 1-2-1, cảm ơn cơ hội. Tên không viết toàn HOA hoặc toàn thường, có thông báo/ví dụ.

Người nhận nhận thông báo ai trao/SĐT, xác nhận tiền thực nhận hoặc không thành công và lý do. Phân biệt giá trị dự kiến với giá trị xác nhận. Không cộng lặp khi xác nhận lại; báo cáo tuần trước có điều kiện thời gian và chỉ tính hội viên theo yêu cầu bổ sung.

Báo cáo: tổng phiếu, tổng giá trị, thành công, lũy kế, danh sách chi tiết, top người trao/người nhận, vinh danh 1–2–3, ngày/tuần/tháng/quý/năm/nhiệm kỳ. Dashboard public sơ bộ chỉ có số tổng hợp được công khai; dữ liệu chi tiết và tài chính cá nhân ở bên trong.

## 10. Tài chính và phí

Thư ký lập/quản lý khoản thu, chi, cố định và linh hoạt; ngày giờ, phương thức tiền mặt/ngân hàng, chứng từ ảnh/PDF/Excel, sổ quỹ, số dư, công nợ và lịch sử. Có nghĩa vụ phí cho một hoặc nhiều hội viên, thu một phần, chia bill, tài trợ cam kết và tài trợ thực nhận tách riêng.

Các yêu cầu phạm vi đầy đủ còn có ngân sách, quyết toán từng sự kiện, khóa sổ, xử lý sửa/hủy và xuất báo cáo. Không coi các phần này hoàn chỉnh chỉ vì V6 có một số màn hình liên quan.

Phí: gia nhập mới 4,5 triệu; tái phí 3 triệu; tri ân theo % của 3 triệu; phí quỹ mặc định 500 nghìn/tháng, hạn 01–10; cảnh báo thường niên trước 30 ngày; xác nhận đã nộp thì tắt cảnh báo tương ứng. Báo cáo công nợ, quá hạn/đúng hạn và chứng từ cần xử lý.

Thư ký có thể soạn thông báo/nhắc phí theo hội viên, chỉnh tiêu đề và nội dung trước khi gửi. Việc gửi email thật, nội dung AI và đối tượng nhận cần kết nối dịch vụ máy chủ; chưa được coi là đã gửi khi mới tạo bản nháp.

## 11. Lucky Draw

Danh sách theo người đã check-in đúng buổi; khử trùng bằng ID/SĐT; xáo tên; quay một/nhiều người; số lượng và số giây; ảnh nền phủ màn hình; hai logo không kèm chữ khi dùng logo tải lên; nhạc được yêu cầu có dừng/tiếp tục/loop. Tên trúng nổi bật, bảng kèm vai trò, Chapter, SĐT, doanh nghiệp; loại người đã trúng khỏi lượt tiếp, phân biệt người trùng tên và người về trước.

Lịch sử yêu cầu đầu có đề cập Admin ấn định người trúng trước. Nội dung này không được bổ sung trong đợt thiết kế/catalog hiện tại và không được tính là đã hoàn thành. Yêu cầu mới nhất về quyền: hội viên thường không có công cụ quay; Ban Sự kiện/Chủ tịch/Admin theo phân quyền.

## 12. Báo cáo, thông báo, hỗ trợ và dữ liệu

Nhiệm kỳ bắt đầu tháng 10/2026 đến hết tháng 9/2027, tổng kết cuối năm; báo cáo theo ngày/tuần/tháng/quý/năm/nhiệm kỳ, lọc và xuất Excel/in PDF tùy quyền. Phó Chủ tịch có báo cáo hiện diện và bảng tuần đầy đủ; Chủ tịch/Admin tổng hợp các Ban. Chỉ số hoạt động dựa trên dữ liệu, không tự suy ra phẩm chất cá nhân.

Thông báo có đối tượng hội viên/Ban/LT/toàn bộ/public, trạng thái kiểm duyệt, mức quan trọng và popup một lần khi phù hợp. Kỷ niệm 4 năm Chapter ngày 11/11/2026 là sự kiện đã yêu cầu. Có kênh hỗ trợ/ticket và nhật ký hệ thống.

Hệ thống cần tìm kiếm, nhập/xuất Excel, tài liệu tập trung và một nguồn dữ liệu. Bản production cần database, đăng nhập và quyền phía máy chủ, private storage, gửi email, sao lưu, HTTPS/tên miền. CCCD, GPLKD, tài chính thật không được bảo vệ chỉ bằng ẩn giao diện.

## 13. Phân loại tình trạng trong đợt này

| Nhóm | Tình trạng |
|---|---|
| Nguyên văn VBNA | Khôi phục từ ô F2, dựng 7 khối nội dung; có kiểm tra câu chữ so với nguồn |
| Màu và chữ | Áp dụng một hệ đỏ mận và chữ sans-serif cho giao diện, giữ ảnh/logo là nội dung riêng |
| Catalog công khai | Bổ sung bìa, cá nhân, doanh nghiệp, năng lực, sản phẩm, ảnh và kết nối; có bản minh họa riêng |
| Cập nhật catalog | Bổ sung biên tập, lưu nháp, tải ảnh, xem trước riêng tư, gửi duyệt, xem bản duyệt, chấp thuận/yêu cầu sửa, thông báo |
| Trang riêng và báo cáo | Giữ các mục Tổng quan/Cơ hội/Tài chính/Điểm danh/Thông báo của bản hiện có; nâng cấp mục Hồ sơ |
| ERP các Ban và luồng nền | Kế thừa V6; không tuyên bố kiểm thử toàn bộ 132 đầu mục trong đợt thiết kế này |
| Nhân sự nhiệm kỳ và bản đồ | Chờ dữ liệu và quyền xem cụ thể; không điền giả |
| Đồng bộ đa thiết bị và bảo mật production | Chưa có backend triển khai; local prototype chưa đạt điều kiện này |

## 14. Tiêu chí nghiệm thu cho phần vừa nâng cấp

1. Nội dung các khối VBNA khớp nguyên văn nguồn sau khi chuyển định dạng Markdown.
2. Catalog hoạt động ở desktop/tablet/mobile, không tràn ngang, ảnh/sản phẩm mở xem được.
3. Khách ngoài không xem được nháp; trang public không có email tài khoản, địa chỉ nhà và thông tin nghiệp vụ riêng tư.
4. Lưu nháp và tải lại trang giữ nội dung/ảnh; thêm/xóa/lưu nhiều lần không đổi nhầm ảnh sản phẩm.
5. Chỉ Chủ tịch/Admin phê duyệt được; bản chờ duyệt không thay bản public; hồ sơ nền thay đổi thì không cho duyệt ghi đè.
6. Sau duyệt, nội dung public cập nhật, hội viên nhận thông báo; trạng thái luồng và lỗi được nói rõ.
7. Những dữ liệu minh họa được ghi là minh họa; nội dung thiếu không biến thành thành tích hay thông tin có thật.

## 15. Danh mục gốc 132 đầu mục

Danh mục dưới đây giữ để đối chiếu phạm vi lịch sử. Các điều chỉnh ở các phần trên có độ ưu tiên cao hơn khi cùng nói về một chức năng. Không dùng danh mục này làm bảng xác nhận hoàn thành.


| STT | Module | Đầu mục | Yêu cầu gốc |
|---|---|---|---|
| 1 | Website công khai | Trang chủ | Giới thiệu VBNA Chapter 11; giao diện tone đỏ; hình ảnh doanh nghiệp, chuyên nghiệp; menu điều hướng đầy đủ |
| 2 | Website công khai | Giới thiệu Chapter 11 | Giới thiệu tổ chức, lịch sử, định hướng, hoạt động, thông tin Chapter |
| 3 | Website công khai | Đăng nhập | Nút đăng nhập hội viên; khách ngoài không cần tài khoản để dùng link Public |
| 4 | Website công khai | Đăng ký khách mời | Nút “Đăng ký làm khách mời ngay”; form thu thập họ tên, SĐT, email, địa chỉ, ngành nghề, sản phẩm, loại hình Cá nhân/HKD/Doanh nghiệp, người giới thiệu |
| 5 | Website công khai | Hội viên | Trang giới thiệu thành viên Chapter 11 |
| 6 | Website công khai | Ngành nghề | Danh mục ngành nghề và sản phẩm/dịch vụ hội viên |
| 7 | Website công khai | Power Team | Hiển thị các Power Team và hội viên thuộc từng nhóm |
| 8 | Website công khai | Leader Team | Giới thiệu LT và các Ban nhiệm kỳ hiện tại |
| 9 | Tài khoản | Cấp tài khoản | Admin/Chủ tịch phê duyệt hội viên xong hệ thống tự tạo tài khoản bằng SĐT |
| 10 | Tài khoản | Mật khẩu ban đầu | Hệ thống tự tạo mật khẩu tạm và gửi email cho hội viên |
| 11 | Tài khoản | Đổi mật khẩu lần đầu | Bắt buộc đổi mật khẩu sau lần đăng nhập đầu |
| 12 | Tài khoản | Chuẩn mật khẩu | Tối thiểu 8 ký tự, có chữ hoa, chữ thường và số |
| 13 | Tài khoản | Reset mật khẩu | Admin/Chủ tịch reset; hệ thống tạo mật khẩu mới và gửi email |
| 14 | Tài khoản | Khóa/Mở | Admin/Chủ tịch được khóa hoặc mở tài khoản |
| 15 | Tài khoản | Rời Chapter | Khi hội viên chuyển trạng thái không hoạt động/rời Chapter thì tài khoản tự khóa |
| 16 | Email | Email chào mừng | Tự sinh nội dung giới thiệu bằng AI, kèm link đăng nhập, tài khoản, mật khẩu tạm |
| 17 | Email | Email đổi mật khẩu | Gửi thông báo đổi mật khẩu thành công |
| 18 | Hội viên | Hồ sơ cá nhân | Họ tên, ngày sinh, giới tính nếu cần, SĐT, email, địa chỉ nhà riêng |
| 19 | Hội viên | Hồ sơ doanh nghiệp | Tên DN/HKD, chức vụ, MST, địa chỉ kinh doanh, website, sản phẩm/dịch vụ |
| 20 | Hội viên | Ngành nghề | Ngành nghề đăng ký trong VBNA |
| 21 | Hội viên | Power Team | Gắn hội viên vào Power Team |
| 22 | Hội viên | Ngày trạng thái | Ngày gia nhập, ngày kết nạp, ngày dừng |
| 23 | Hội viên | Dừng tham gia | Lý do dừng, loại rời tự nguyện/tạm dừng/chấm dứt tư cách |
| 24 | Hội viên | File quyết định | Upload quyết định rời/chấm dứt |
| 25 | Hội viên | CCCD | Upload ảnh CCCD |
| 26 | Hội viên | GPLKD | Upload ảnh giấy phép kinh doanh |
| 27 | Hội viên | Ảnh doanh nghiệp | Upload ảnh mặt tiền cửa hàng/doanh nghiệp |
| 28 | Hội viên | File khác | Tối đa 10 file đính kèm khác |
| 29 | Hội viên | Workflow duyệt | Các thay đổi quan trọng phải có đề xuất → kiểm tra → phê duyệt |
| 30 | Hội viên | Lịch sử thay đổi | Lưu ai sửa, lúc nào, dữ liệu trước/sau |
| 31 | Tổ chức | HĐSL | Quản lý danh sách Hội đồng Sáng lập |
| 32 | Tổ chức | HĐTV | Quản lý danh sách Hội đồng Thành viên |
| 33 | Tổ chức | Chủ tịch Chapter | Danh sách Chủ tịch Chapter 1–23 |
| 34 | Tổ chức | LT các Chapter | Quản lý Leader Team các Chapter |
| 35 | Tổ chức | Ban trong LT | Chọn thành viên thuộc ban nào |
| 36 | Ban | Chủ tịch | Có menu và Dashboard riêng |
| 37 | Ban | Phó Chủ tịch | Có menu và Dashboard riêng |
| 38 | Ban | Ban Thư ký | Có menu, Dashboard và module tài chính |
| 39 | Ban | Ban Đào tạo | Có menu và Dashboard riêng |
| 40 | Ban | Ban Khách mời | Có menu và Dashboard riêng |
| 41 | Ban | Sự kiện & Truyền thông | Có menu và Dashboard riêng |
| 42 | Ban | Ban Phát triển | Có menu, Dashboard và Power Team |
| 43 | Ban | Ban Định hướng | Có menu và Dashboard riêng |
| 44 | Ban | Giám đốc hỗ trợ | Có menu và Dashboard riêng |
| 45 | Ban | Phân quyền | Trưởng ban và thành viên ban được xem dữ liệu chi tiết theo quyền |
| 46 | Ban | Public nội bộ | Dashboard Ban được hội viên Chapter 11 có đăng nhập xem; khách ngoài không được xem |
| 47 | Admin | Full quyền | Admin là quyền cao nhất hệ thống |
| 48 | Dashboard | Tổng quan | Báo cáo toàn Chapter |
| 49 | Dashboard | Thời gian | Báo cáo theo tuần, tháng, quý, năm, toàn nhiệm kỳ |
| 50 | Dashboard | Nhiệm kỳ | NK tính từ tuần 1 tháng 10/2026 đến hết tháng 9/2027 |
| 51 | Dashboard | Tổng kết năm | Hết nhiệm kỳ có báo cáo tổng hợp |
| 52 | Cuộc họp | Tạo cuộc họp | Chủ tịch/Admin đặt tên buổi họp, ngày, giờ, địa điểm |
| 53 | Cuộc họp | Meeting Landing Page | Mỗi buổi họp có một trang Public riêng |
| 54 | Cuộc họp | QR/Link | Tạo link/QR điểm danh, trao cơ hội, khách mời |
| 55 | Điểm danh | Public | Không cần đăng nhập |
| 56 | Điểm danh | Loại người tham dự | HĐSL, HĐTV, Chủ tịch Chapter, hội viên các Chapter, khách VBNA, khách ngoài |
| 57 | Điểm danh | Chapter 11 | Chọn Chapter 11 thì xổ danh sách hội viên để chọn |
| 58 | Điểm danh | Tự điền dữ liệu | Tự lấy họ tên, SĐT, DN, ngành nghề, vai trò |
| 59 | Điểm danh | Người mời bởi | Chọn hội viên Chapter 11 đã mời khách |
| 60 | Điểm danh | Chống trùng | Không điểm danh trùng một người trong cùng buổi |
| 61 | CRM khách mời | Lead | Người đăng ký website vào danh sách khách tiềm năng |
| 62 | CRM khách mời | Trạng thái | Mới đăng ký → Đã liên hệ → Đã mời → Đã tham dự → Quan tâm → Hồ sơ → Kết nạp |
| 63 | CRM khách mời | Chuyển hội viên | Chuyển Guest thành Member mà giữ lịch sử |
| 64 | CRM khách mời | Kiểm tra ngành nghề | Cảnh báo nếu ngành nghề có khả năng trùng hội viên hiện tại |
| 65 | Referral | Public form | Có link Public không cần tài khoản |
| 66 | Referral | Người trao | Chọn hội viên/khách được phép |
| 67 | Referral | Người nhận | Một form thêm nhiều người nhận |
| 68 | Referral | Loại cơ hội | Referral cấp 1–5, Dance 1-2-1, Cảm ơn đã nhận cơ hội |
| 69 | Referral | Giá trị | Nhập số tiền từng cơ hội |
| 70 | Referral | Mỗi dòng = 1 phiếu | Mỗi người nhận trên mỗi dòng tính một cơ hội |
| 71 | Referral | Chuẩn hóa tên | Tên không viết HOA hết hoặc thường hết |
| 72 | Referral | Lũy kế | Tổng cơ hội toàn nhiệm kỳ |
| 73 | Referral | Thành công | Lũy kế cơ hội thành công |
| 74 | Referral | Báo cáo buổi họp | Tổng số cơ hội trao trong buổi họp hiện tại |
| 75 | Referral | Người trao Top | Xếp hạng hội viên trao nhiều cơ hội |
| 76 | Referral | Người nhận Top | Xếp hạng hội viên/khách nhận nhiều cơ hội |
| 77 | Referral | Vinh danh | Top 1, 2, 3; dashboard đẹp để Chủ tịch đọc |
| 78 | Referral | Bộ lọc | Ngày, tuần, tháng, quý, năm, nhiệm kỳ |
| 79 | Referral | Danh sách chi tiết | Danh sách toàn bộ cơ hội được trao |
| 80 | Tài chính | Phân quyền | Trưởng ban Thư ký nhập và quản lý |
| 81 | Tài chính | Phiếu thu | Quản lý từng khoản thu |
| 82 | Tài chính | Phiếu chi | Quản lý từng khoản chi |
| 83 | Tài chính | Khoản cố định | Khoản chi cố định định kỳ |
| 84 | Tài chính | Khoản linh hoạt | Khoản phát sinh |
| 85 | Tài chính | Chứng từ | Upload hóa đơn/ảnh/PDF |
| 86 | Tài chính | Excel | Upload file Excel để lưu trữ/import |
| 87 | Tài chính | Export | Xuất báo cáo Excel |
| 88 | Tài chính | Sổ quỹ | Số dư đầu kỳ + thu – chi = số dư cuối kỳ |
| 89 | Tài chính | Tiền mặt/Ngân hàng | Theo dõi riêng từng quỹ |
| 90 | Tài chính | Ngân sách | Dự toán, thực chi, còn lại, vượt ngân sách |
| 91 | Tài chính | Sự kiện | Quyết toán riêng từng sự kiện |
| 92 | Tài chính | Khóa sổ | Cuối tháng có quy trình khóa sổ |
| 93 | Tài chính | Audit log | Giao dịch sửa/hủy phải lưu lịch sử |
| 94 | Phí hội viên | Phí thường niên | 3.000.000đ |
| 95 | Phí hội viên | Nhắc phí thường niên | Popup trước 30 ngày |
| 96 | Phí hội viên | Phí quỹ | 500.000đ/tháng |
| 97 | Phí hội viên | Hạn phí quỹ | Nộp từ ngày 01 đến ngày 10 hàng tháng |
| 98 | Phí hội viên | Tắt cảnh báo | Thư ký xác nhận đã nộp thì popup không hiện nữa |
| 99 | Lucky Draw | Nguồn dữ liệu | Lấy danh sách người đã điểm danh buổi họp |
| 100 | Lucky Draw | Khử trùng | Nhận diện bằng Member ID/SĐT để không nhầm người trùng tên |
| 101 | Lucky Draw | Xáo danh sách | Có nút Shuffle trước/giữa các lượt |
| 102 | Lucky Draw | Chế độ | Quay 1 người hoặc nhiều người |
| 103 | Lucky Draw | Số lượng | Chọn số người cần trúng |
| 104 | Lucky Draw | Thời gian | Chọn số giây ra kết quả |
| 105 | Lucky Draw | Nhạc | Nhạc quay thưởng phát xuyên suốt, loop; có pause/resume |
| 106 | Lucky Draw | Nền | Cho upload ảnh nền |
| 107 | Lucky Draw | Logo | Logo VBNA trái, Logo Chapter 11 phải |
| 108 | Lucky Draw | Người trúng | Tên nổi bật khi trúng |
| 109 | Lucky Draw | Bảng kết quả | Họ tên, vai trò, Chapter, SĐT, DN |
| 110 | Lucky Draw | Loại người trúng | Có nút xóa/loại khỏi danh sách quay tiếp |
| 111 | Lucky Draw | Chống trúng lại | Người đã trúng không được trúng lại nếu đã loại |
| 112 | Lucky Draw | Trùng tên | Phải xác định đúng người qua ID/SĐT |
| 113 | Power Team | Quản lý | Nằm trong Ban Phát triển |
| 114 | Power Team | Auto assign | Hội viên gắn Power Team nào thì hiện đúng nhóm đó |
| 115 | Sự kiện | Sinh nhật Chapter | Sự kiện 11/11/2026 – kỷ niệm 4 năm |
| 116 | Sự kiện | Popup | Nhắc Admin/Ban Sự kiện & Truyền thông |
| 117 | Hỗ trợ | Kênh hỗ trợ | Trang/kênh hỗ trợ nội bộ |
| 118 | Hỗ trợ | Ticket | Có thể phát triển thành yêu cầu hỗ trợ, trạng thái xử lý |
| 119 | Hệ thống | Phân quyền | Role + Permission tách riêng |
| 120 | Hệ thống | Audit | Nhật ký hoạt động toàn hệ thống |
| 121 | Hệ thống | Thông báo | Popup/cảnh báo theo quyền và dữ liệu |
| 122 | Hệ thống | Upload | Kho tài liệu tập trung |
| 123 | Hệ thống | Tìm kiếm | Tìm hội viên, khách, cơ hội, giao dịch |
| 124 | Hệ thống | Import | Import dữ liệu hội viên/thu chi từ Excel |
| 125 | Hệ thống | Export | Export báo cáo |
| 126 | Hệ thống | Responsive | Dùng tốt trên máy tính và điện thoại |
| 127 | Hệ thống | Liên kết module | Một nguồn dữ liệu, nhập một lần, tự động dùng lại ở các module khác |
| 128 | Hệ thống | Bảo mật dữ liệu | CCCD/GPLKD/tài chính chỉ người đủ quyền được xem |
| 129 | Hệ thống | Database | Production dùng PostgreSQL/Supabase |
| 130 | Hệ thống | Storage | File production lưu private storage |
| 131 | Hệ thống | Email | Production nối email thật |
| 132 | Hệ thống | Domain | Dự kiến vbna.chapter11.vn |
