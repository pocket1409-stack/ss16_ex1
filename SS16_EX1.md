
 **1.Vấn đề:**
 Ổ cứng máy tính của bạn bị lỗi "Bad Sector" khiến thiết kế tệp bị hỏng, khi bản gửi trên Zalo đã hết hạn tải xuống.
 **2.Yêu cầu:**
 Sơ đồ luồng dữ liệu từ Local SSD lên Cloud và cách hệ thống xử lý khi có xung đột phiên bản (File Version Conflict)
       
 Ctrl + S
      │
SSD)──Ghi file tạm / Atomic Write
      │
       
Phát hiện thay đổi file
       │
       
 Local Cache ──(Nếu mất mạng: Lưu tạm chờ kết nối)
       │
  
 Cloud Storage (Google Drive / OneDrive / Dropbox)] 
       ├─► Tạo bản ghi mới 
       └─► Cập nhật trạng thái đồng bộ real-time cho toàn team		
       							

Quy trình thực thi: Danh sách 3 bước thiết lập phần mềm đồng bộ chuẩn cho một Designer.

Cấu hình thư mục làm việc đồng bộ:
-Cài đặt phần mềm đồng bộ  (Google Drive for Desktop, OneDrive hoặc Dropbox). Tạo một thư mục chung của dự án nằm  trong ổ đĩa ảo của đám mây.  
-Kích hoạt tính năng lịch sử phiên bản trên Cloud . Đồng thời, chọn chế độ **"Always keep on this device"** cho các thư mục hiện vật đang làm việc để Designer có thể làm việc mượt mà ngay cả khi ngoại tuyến
-Tắt các thông báo không cần thiết của ứng dụng chat trong giờ làm việc s). Hướng dẫn toàn nhóm sử dụng tôn trọng không gian tập trung của nhau, giải quyết triệt để áp lực.
