(IPO)
Input: Ngữ cảnh Kiosk sạc VoltCharge Windows 11 + Lỗi UnauthorizedAccessException: Access to the path 'C:\Program Files\VoltCharge\data\session.log' is denied.

Process: AI nhận diện lỗi phân quyền hệ thống do ghi dữ liệu vào Program Files mà không có quyền Admin, sau đó tổng hợp giải pháp từng bước.

Output: Bản dịch, nguyên nhân gốc rễ và 3 bước xử lý.

CÂU PROMPT 3 THÀNH PHẦN HOÀN CHỈNH
[Context]: Tôi là kỹ thuật viên vận hành hệ thống Kiosk sạc nhanh VoltCharge chạy trên Windows 11 tại Bến xe Miền Đông, phần mềm gặp sự cố khi khởi động.

[Raw Error]:

Plaintext
[TERMINAL ERROR LOG - VOLTCHARGE CHARGER #04]
System.UnauthorizedAccessException: Access to the path 'C:\Program Files\VoltCharge\data\session.log' is denied.
Process terminated with exit code 5 (0x00000005).
Suggestion: Run the application with elevated administrator privileges or verify NTFS file permissions.
[Instruction]: Hãy dịch ngắn gọn, giải thích nguyên nhân và hướng dẫn 3 bước khắc phục bằng tiếng Việt.

GIẢI MÃ LỖI & 3 BƯỚC KHẮC PHỤC
Bản dịch & Nguyên nhân: Quyền truy cập vào đường dẫn tệp nhật ký bị từ chối do ứng dụng cố ghi dữ liệu vào thư mục bảo mật Program Files mà không có quyền Quản trị viên (Administrator).

3 bước xử lý:

Bước 1: Click chuột phải vào biểu tượng ứng dụng VoltCharge và chọn Run as administrator.

Bước 2: Vào thư mục C:\Program Files\VoltCharge, nhấp chuột phải vào thư mục data -> Properties -> Security -> cấp quyền Full Control cho tài khoản hiện tại.

Bước 3: Khởi động lại dịch vụ phần mềm.

Xử lý bẫy an ninh: Bắt buộc phải xóa hoặc thay thế các chuỗi nhạy cảm (như API_KEY: volt_secret_token_889922 thành API_KEY: [REDACTED]) trước khi gửi lên AI công cộng để tránh rò rỉ mã khóa độc quyền của doanh nghiệp.