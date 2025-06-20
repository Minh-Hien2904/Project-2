# Trạm giám sát chất lượng không khí

## Giới thiệu
Trong thập kỷ qua, ô nhiễm không khí đã trở thành một vấn đề nghiêm trọng, đặc biệt tại các đô thị lớn như Hà Nội và TP. Hồ Chí Minh. Sự gia tăng khí thải từ phương tiện giao thông và quá trình đô thị hóa nhanh chóng là nguyên nhân chính khiến chất lượng không khí suy giảm. Dự án **Trạm giám sát chất lượng không khí** ra đời nhằm xây dựng một thiết bị đo lường thông minh, theo dõi **nhiệt độ**, **độ ẩm**, và **nồng độ bụi mịn PM2.5** trong không khí. Dữ liệu được thu thập và gửi trực tiếp đến điện thoại hoặc máy tính qua Internet, giúp người dùng theo dõi chất lượng không khí theo thời gian thực và đưa ra các biện pháp bảo vệ sức khỏe kịp thời.

## Yêu cầu
### Phần cứng
- ESP32 IOT Shield
- Cảm biến nhiệt độ và độ ẩm (DHT11)
- Cảm biến bụi mịn PM2.5 (GP2Y1010AU0F)
- Module WiFi (ESP32)
- Breadboard, dây nối và nguồn điện

### Phần mềm
- Arduino IDE ([tải tại đây](https://www.arduino.cc/en/software))
- Ứng dụng hoặc nền tảng nhận dữ liệu (như Blynk, ThingSpeak)
- Hệ điều hành: Windows, macOS, hoặc Linux

### Thư viện
- `DHT.h` (cho cảm biến DHT11/DHT22)
- `SoftwareSerial.h` (cho cảm biến PM2.5)
- `ESP8266WiFi.h` hoặc `WiFi.h` (cho module WiFi)
- Thư viện tương ứng với nền tảng IoT (như `Blynk`)