ONBOARDAI - MENTOR MANAGEMENT
============================

Bộ giao diện Mentor được thiết kế theo phong cách tím - trắng trong ảnh mẫu OnboardAI, gồm:
- Danh sách nhân viên/mentee: tìm kiếm, lọc trạng thái, xem hồ sơ và tiến độ.
- Ghi chú check-in: tạo, xem, sửa, xóa ghi chú; ghi nhận khó khăn và hành động tiếp theo.
- Giao nhiệm vụ: tạo, sửa, hủy nhiệm vụ; cập nhật trạng thái; lọc theo trạng thái và mức ưu tiên; nhận diện nhiệm vụ quá hạn.
- Responsive cho desktop, tablet và điện thoại.
- Dữ liệu demo và dữ liệu thao tác được lưu trên trình duyệt bằng LocalStorage.

CÁCH CHẠY
1. Giải nén ZIP.
2. Mở thư mục trong VS Code.
3. Mở mentor-dashboard.html bằng Live Server (khuyến nghị) hoặc mở trực tiếp bằng trình duyệt.
4. Dùng thanh điều hướng bên trái để chuyển giữa 3 chức năng.

LƯU Ý LOCALSTORAGE
- Dữ liệu được lưu trên trình duyệt và máy đang dùng, không tự đồng bộ giữa máy hoặc người dùng khác.
- Muốn xóa dữ liệu demo và bắt đầu lại: mở DevTools > Application > Local Storage, xóa các khóa bắt đầu bằng onboardai_mentor_ rồi tải lại trang.

KIỂM TRA THỦ CÔNG
- Danh sách mentee: thử tìm kiếm, lọc trạng thái, mở hồ sơ.
- Check-in: tạo ghi chú, thử bỏ trống trường bắt buộc, sửa và xóa ghi chú.
- Nhiệm vụ: tạo nhiệm vụ, sửa, đổi trạng thái, lọc ưu tiên/trạng thái, hủy nhiệm vụ.
- Tải lại trang để xác nhận dữ liệu vẫn còn trong cùng trình duyệt.
- Thu nhỏ cửa sổ để kiểm tra menu di động và bảng cuộn ngang.

CẤU TRÚC
mentor-dashboard.html  Trang chính tích hợp 3 chức năng
css/mentor.css         Giao diện tím-trắng responsive
js/mentor.js           Logic giao diện, kiểm tra dữ liệu, LocalStorage
assets/icons/          Dành cho tài nguyên hình ảnh bổ sung (hiện không bắt buộc)
