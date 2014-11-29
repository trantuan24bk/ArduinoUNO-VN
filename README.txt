Arduino UNO - VN
    
Phiên bản: 1.0
Ngày cập nhật: 28/11/2014
Tác giả: Trần Tuân

Đã hoàn thiện:
- Phiên bản layout đầu tiên cho kit Arduino
- Sử dụng chip PL2303HX/TA có thể dùng cho Win7/8.1
- Đã thêm nút nhấn điều khiển và 2 LED có điều khiển.
- Firmware sử dụng optiboot.


Cần chỉnh sửa:
- Đổi tụ SMD Alum 330uF sang loại tụ kích thước nhỏ hơn.
- Các header J1, J2, J3 cần ghi rõ ràng hơn.
- Thiếu tụ nạp reset từ DTR (PL2303) -> RESET (ATmega).
- Sửa sai đường VCC và 5V không liên kết với nhau.
- Xem xét sử dụng cổng USB khác bền hơn.
- Xem xét việc thêm các R (điện trở) từ mạch nạp tới chip để đảm bảo an toàn.
