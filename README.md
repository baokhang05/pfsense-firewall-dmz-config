# pfsense-firewall-dmz-config
Cấu hình Firewall và vùng DMZ trên pfSense
# Cấu hình Quản trị Tường lửa (Firewall) & Vùng phi quân sự (DMZ) với pfSense

## Tổng quan dự án
Dự án thực hành chuyên sâu về quản trị mạng và bảo mật hạ tầng. Trọng tâm là việc phân hoạch mạng, thiết lập các vùng an toàn và kiểm soát chặt chẽ luồng giao thông mạng (Network Traffic) thông qua tường lửa pfSense.

## Hạng mục triển khai
- **Phân tích mạng:** Sử dụng các công cụ quản trị (command-line, nslookup) để truy vấn DNS và phân tích chi tiết định tuyến, địa chỉ IP của các máy chủ đích.
- **Kiểm soát truy cập (Access Control):** Thiết lập và quản lý nghiêm ngặt các quy tắc tường lửa (Firewall Rules) trên WebGUI nhằm kiểm soát luồng truy cập nội bộ (chặn/cho phép cụ thể các gói tin TCP/HTTPS).
- **Thiết lập DMZ:** Cấu hình chính sách an ninh mạng riêng biệt cho vùng phi quân sự (DMZ). Cấp quyền giao tiếp an toàn giữa các vùng mạng và tối ưu hóa cho các giao thức mạng lõi (ICMP, DNS) nhằm ngăn chặn rủi ro xâm nhập từ bên ngoài.
- **Công cụ sử dụng:** pfSense, Command-line networking tools.

## Tài liệu cấu hình chi tiết
Chi tiết về bảng phân hoạch IP, sơ đồ đấu nối mạng và danh sách các Firewall Rules đã thiết lập có thể xem tại **[File Báo cáo PDF đính kèm](https://github.com/baokhang05/pfsense-firewall-dmz-config/blob/main/C%E1%BA%A5u%20h%C3%ACnh%20Firewall%20v%C3%A0%20v%C3%B9ng%20DMZ%20tr%C3%AAn%20pfSense.pdf)**.
