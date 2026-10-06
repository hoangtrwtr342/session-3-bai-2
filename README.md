HỌ VÀ TÊN : BÙI MINH HOÀNG
LỚP :HCM-CNTT1
BÀI 2 SESSION 3

1. Báo cáo phân tích
 Tại sao đường dẫn tuyệt đối bị lỗi?
 Vì đường dẫn tuyệt đối gắn cố định tên ổ đĩa/tên User của máy bạn (Ví dụ: C:\Users\Ban\...). Sang máy bạn thân có tên ổ đĩa/User khác nên Python không tìm thấy file.
2.Luồng IPO (Nạp từ Storage vào RAM):
  Input (Nhập): Đọc code và ảnh từ Ổ cứng (Storage) nạp lên RAM.
  Process (Xử lý): CPU lấy dữ liệu từ RAM để giải mã ảnh và chạy giao diện.
  Output (Xuất): Hiển thị màn hình ứng dụng Shopee-Lite.


3. Giải pháp kỹ thuật
  Cấu trúc đường dẫn tương đối (. và ..):. là thư mục hiện tại, .. là lùi ra thư mục cha 1 cấp.
  Viết lại chuẩn: './assets/logo.png' (Bê sang máy nào cũng tự tìm đúng thư mục assets cạnh file code).

3 bước giảm lag (hạ RAM 98%) cho máy bạn thân:
    * Mở Task Manager, tắt bớt các ứng dụng ngốn RAM (như Chrome, app chạy ngầm).
    * Kiểm tra code Python: Tránh nạp ảnh dung lượng quá lớn cùng lúc hoặc dính vòng lặp vô tận làm tràn RAM.
    * Restart máy tính để xóa sạch toàn bộ bộ nhớ đệm và tiến trình rác bị kẹt trong RAM
