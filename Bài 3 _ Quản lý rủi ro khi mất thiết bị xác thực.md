**1\. Báo cáo phân tích (IPO)**  
**Input:** Mã dự phòng (Backup Code) đã được lưu trữ an toàn (bên ngoài điện thoại) từ trước.  
**Process:**  
Đăng nhập AWS bằng mật khẩu và sử dụng Backup Code thay cho mã Authenticator.  
Ngay lập tức truy cập phần cài đặt bảo mật để **Hủy liên kết 2FA** với thiết bị cũ đã mất.  
Thiết lập lại 2FA bằng app Authenticator trên thiết bị mới.  
Tạo và lưu lại danh sách Backup Codes mới (vì các mã cũ có thể đã bị lộ hoặc hết hạn).  
**Output:** Lấy lại quyền kiểm soát, hệ thống an toàn, thiết bị cũ hoàn toàn bị vô hiệu hóa khả năng sinh mã xác thực.  
**2\. Tại sao không lưu Backup Codes dạng ảnh trong điện thoại?**  
Nếu kẻ gian nhặt được điện thoại và mở khóa được màn hình, họ sẽ dễ dàng tìm thấy ảnh Backup Codes trong thư viện.  
Điện thoại thường là thiết bị nhận email hoặc SMS khôi phục mật khẩu. Nếu kẻ gian có cả quyền reset mật khẩu (qua email/SMS trên máy) cộng thêm Backup Codes (trong thư viện ảnh), lớp bảo mật 2FA sẽ bị phá vỡ hoàn toàn, dẫn đến việc mất trắng tài khoản. Backup Codes phải luôn được lưu trữ độc lập với thiết bị tạo mã 