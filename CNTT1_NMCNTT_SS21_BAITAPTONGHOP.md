Phần 1 – Googling đúng cách
Vì sao câu hỏi văn nói kém chất lượng: Chứa từ cảm thán, văn nói dài dòng ("thầy ơi", "giúp em với") làm phân tán trọng số tìm kiếm, khiến Google trả về diễn đàn tâm sự thay vì tài liệu kỹ thuật.

Bóc tách lỗi (mục 3a):

Tên phần mềm / HĐH: Node.js / Windows 11

Mã lỗi: 'npm' is not recognized as an internal or external command, operable program or batch file.

Thao tác đang làm: Gõ kiểm tra phiên bản npm -v trên Terminal của VS Code.

3 câu truy vấn chuẩn:

site:stackoverflow.com Node.js npm is not recognized as an internal or external command

Node.js Windows 11 "'npm' is not recognized as an internal or external command, operable program or batch file."

Node.js npm is not recognized Windows 11 -windows-xp -old -fix2012

Phần 2 – Thẩm định StackOverflow
So sánh Câu trả lời A và B:

Vote & Tích xanh: A có +186 upvotes và tích xanh; B có +2 upvotes và không có tích xanh.

Thời gian đăng: A đăng 2 năm trước (mới); B đăng 9 năm trước (cũ).

Tags: A khớp [node.js], [windows], [npm]; B dùng [windows-xp] (lỗi thời).

Kết luận & Bẫy nguy hiểm: Áp dụng Câu trả lời A. B là bẫy nguy hiểm vì hướng dẫn cài lại driver Windows XP cho máy Windows 11, dễ làm hỏng cấu hình hệ điều hành.

Quy trình 30 Giây Đọc lướt: Kiểm tra Tags đúng công nghệ ➔ Nhìn thẳng vào câu trả lời có tích xanh và upvotes cao ➔ Đọc nhanh lệnh giải pháp, bỏ qua phần mô tả dài.

Phần 3 – Hỏi AI đúng cách và nhận diện rủi ro
Prompt hoàn chỉnh 3 Thành phần:

[Context]: Tôi vừa cài Node.js trên Windows 11, mở Terminal trong VS Code gõ npm -v bị lỗi. Tôi đã thử thêm đường dẫn C:\Program Files\nodejs\ vào biến môi trường PATH nhưng vẫn lỗi.
[Raw Error]: 'npm' is not recognized as an internal or external command, operable program or batch file.
[Instruction]: Giải thích nguyên nhân tại sao thêm PATH vẫn lỗi và hướng dẫn các bước kiểm tra tiếp theo bằng tiếng Việt.

Thẩm định câu trả lời AI (mục 3e): KHÔNG AN TOÀN TUYỆT ĐỐI. Lệnh del /f /s /q C:\Windows\System32\* sẽ xóa sạch các file hệ thống trọng yếu và làm sập toàn bộ hệ điều hành Windows (ảo giác AI phá hoại).

Cách phản hồi AI: Từ chối chạy lệnh và bắt AI cung cấp phương án kiểm tra đường dẫn cài đặt Node.js an toàn khác.

Phần 4 – Viết Bug Report chuẩn
Tin nhắn Kém: "Thầy ơi máy em lỗi gõ npm không được giúp em với ạ!"

Tin nhắn chuẩn (Bug Reporting Framework):

Context: Windows 11, mới cài Node.js, thao tác trên Terminal của VS Code.

Expected: Gõ npm -v hiển thị số phiên bản của npm.

Actual: Terminal báo lỗi không nhận diện lệnh.

Log & Screenshot: 'npm' is not recognized as an internal or external command, operable program or batch file. (Kèm ảnh chụp màn hình)

Phím tắt & Lưu ý bảo mật:

Phím tắt chụp màn hình: Win + Shift + S.

Lưu ý bảo mật: Che/bôi đen thông tin cá nhân (tên tài khoản trên đường dẫn Terminal, IP, token) trước khi gửi ảnh.