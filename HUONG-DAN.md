# Hướng dẫn cài và sử dụng Account Manager

## Chuẩn bị

- Máy Windows có ứng dụng Codex chính thức từ Microsoft Store/MSIX.
- Bộ cài hỗ trợ tên người dùng Windows và đường dẫn có dấu tiếng Việt.
- Bộ cài không kèm tài khoản hay thông tin đăng nhập. Trên máy mới, bạn đăng nhập bằng tài khoản của mình.

## Cài đặt và mở tool

1. Chạy `Setup.exe` và làm theo hướng dẫn trên cửa sổ cài đặt.
2. Mở **Codex Multi Launcher** bằng shortcut trên Desktop hoặc Start Menu.
3. Giao diện quản lý mở tại `http://localhost:18765/` trong trình duyệt.

Ứng dụng mặc định được cài tại `%LOCALAPPDATA%\Programs\CodexMultiLauncher` theo người dùng Windows hiện tại.

## Sử dụng

- **Thêm Account:** nhập tên tài khoản, tối đa 256 ký tự. Hồ sơ mới cần đăng nhập riêng.
- **Mở Account:** mở cửa sổ Codex của hồ sơ được chọn.
- **Dừng Account:** lưu công việc trước khi xác nhận đóng cửa sổ của hồ sơ đó.
- **Xóa Account:** nằm trong menu thao tác phụ và cần xác nhận. Chỉ xóa khi chắc chắn không cần hồ sơ; không dùng tài khoản thật để thử nút này.
- **Hạn mức:** sidebar hiển thị phần trăm còn lại theo giờ/tuần. Từ 10% trở lên màu xanh, dưới 10% màu đỏ. Khung chi tiết hiển thị phần trăm đã dùng. Thiếu thông tin đăng nhập hoặc chưa đọc được hạn mức sẽ có thông báo, không phải hạn mức bằng 0%.
- **Lịch sử cấu hình:** chọn lần mở để xem thay đổi và bản chụp cấu hình tương ứng.

## Cập nhật mà giữ cửa sổ Codex

1. Thoát riêng **Account Manager** bằng chức năng thoát trên giao diện hoặc menu biểu tượng ở khay hệ thống.
2. Giữ nguyên các cửa sổ Codex của từng Account nếu muốn tiếp tục làm việc.
3. Chạy bộ cài mới, sau đó mở lại Manager.

Chỉ đóng tab trình duyệt không đồng nghĩa với thoát dịch vụ Manager. Nếu bộ cài báo phải đóng Manager trước khi nâng cấp, hãy thoát đúng dịch vụ rồi chạy lại; không cần đóng toàn bộ Codex.

## Khi cần kiểm tra lỗi

- Không mở được Account: kiểm tra đã cài Codex chính thức từ Microsoft Store/MSIX.
- Không vào được giao diện: mở lại shortcut Manager và dùng `http://localhost:18765/`.
- Sau khi Manager khởi động lại: chờ giao diện tự kết nối lại hoặc tải lại trang.
- Không dùng thư mục liên kết junction/symlink cho đường dẫn cài đặt hoặc hồ sơ.

## Bảo mật và dữ liệu

Dữ liệu hồ sơ được lưu riêng trên máy, không nằm trong tệp `Setup.exe`. Không chia sẻ thư mục hồ sơ, tệp xác thực, cookie hoặc nhật ký có thông tin cá nhân. Không gửi token hay mật khẩu khi báo lỗi.

Hướng dẫn là văn bản thuần, có thể mở `HUONG-DAN.md` bằng Notepad.
