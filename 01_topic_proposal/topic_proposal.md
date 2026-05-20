# Topic Proposal

## 1. Group Information

- Class: SE1839
- Group: 01
- Leader: Trương Gia Kiệt
- Members: Trương Gia Kiệt, Lê Vũ Tiến Dũng, Trần Ánh Quốc

## 2. Proposed Title

English title: An IoT-Based Smart Locker Security and Access Logging System for University Laboratories

Vietnamese title: Hệ thống tủ thông minh bảo mật và ghi nhận truy cập cho phòng thí nghiệm đại học dựa trên IoT

## 3. Application Domain

University laboratory management — quản lý thiết bị và kiểm soát truy cập phòng thí nghiệm.

## 4. Problem Statement

Các phòng thí nghiệm đại học hiện nay thường quản lý thiết bị và tủ đựng dụng cụ theo phương thức thủ công (chìa khóa vật lý, sổ ghi tay). Điều này dẫn đến rủi ro mất mát thiết bị, khó kiểm tra lịch sử truy cập, không có cơ chế cảnh báo khi có truy cập trái phép, và tốn thời gian quản lý của giáo viên/nhân viên phòng lab.

## 5. Motivation

Với số lượng sinh viên đông và thiết bị có giá trị cao trong phòng lab, việc thiếu hệ thống kiểm soát truy cập tự động dẫn đến thất thoát, khó truy xuất trách nhiệm và quản lý kém hiệu quả. Một hệ thống IoT tự động hóa quá trình này sẽ giảm rủi ro và tăng minh bạch.

## 6. Target Users

- Sinh viên: mở tủ lấy/trả thiết bị bằng thẻ RFID hoặc mã QR.
- Giảng viên / Quản lý phòng lab: theo dõi lịch sử truy cập, nhận cảnh báo bất thường qua dashboard.

## 7. Proposed AI Model / Method

Hệ thống này tập trung vào IoT và không dùng AI model phức tạp. Tuy nhiên có thể tích hợp:

- Rule-based anomaly detection: cảnh báo khi tủ bị mở ngoài giờ quy định hoặc mở quá lâu.
- (Mở rộng) ML-based access pattern analysis: phát hiện hành vi truy cập bất thường dựa trên lịch sử.

## 8. System Features

1. Xác thực người dùng bằng thẻ RFID hoặc mã QR để mở tủ.
2. Ghi nhận log truy cập: ai mở, thời điểm nào, tủ nào.
3. Cảnh báo tức thời khi phát hiện truy cập trái phép (PIR sensor + buzzer + thông báo dashboard).
4. Dashboard quản trị: xem lịch sử truy cập, quản lý người dùng, xem trạng thái tủ realtime.
5. Báo cáo theo ngày/tuần cho quản lý phòng lab.

## 9. Expected Contribution

1. Đề xuất và triển khai kiến trúc hệ thống IoT smart locker chi phí thấp phù hợp với môi trường đại học.
2. Xây dựng pipeline từ phần cứng (ESP32 + RFID + sensor) đến dashboard web quản trị.
3. Đánh giá thực nghiệm về độ chính xác xác thực, độ trễ phản hồi và độ ổn định hệ thống.

## 10. Evaluation Plan

- Dataset: dữ liệu log truy cập thu thập trong quá trình thử nghiệm (thật hoặc giả lập có kiểm soát).
- Baseline: hệ thống khóa vật lý thông thường (manual), so sánh thời gian xử lý và khả năng truy vết.
- Metrics:
  - Authentication accuracy: tỷ lệ xác thực đúng/sai.
  - Response latency: thời gian từ quẹt thẻ đến mở khóa.
  - Alert accuracy: tỷ lệ phát hiện đúng truy cập bất thường.
  - System uptime / reliability: độ ổn định khi chạy liên tục.
  - Usability: khảo sát người dùng (SUS hoặc bảng đánh giá đơn giản).

## 11. Related Papers

| No  | Title                                                                                | Year | Source                              | Link / DOI                                                                                                              |
| --- | ------------------------------------------------------------------------------------ | ---- | ----------------------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| 1   | Smart Home Monitoring to Improve Valuable Storage Security Using IoT-Bluetooth       | 2023 | Procedia Computer Science, Elsevier | https://www.sciencedirect.com/science/article/pii/S1877050923017854                                                     |
| 2   | IOT Based Smart Farming Application                                                  | 2023 | E3S Web of Conferences              | https://www.e3s-conferences.org/articles/e3sconf/abs/2023/36/e3sconf_iconnect2023_04012/e3sconf_iconnect2023_04012.html |
| 3   | Intelligent and Real-Time Parking System                                             | 2024 | E3S Web of Conferences              | https://www.e3s-conferences.org/articles/e3sconf/pdf/2024/02/e3sconf_icregcsd2023_03003.pdf                             |
| 4   | IoT-Enabled Smart Home Energy Monitoring System Using Web Server-Based Control Logic | 2025 | Jurnal Informasi dan Teknologi      | https://jidt.org/jidt/article/view/611                                                                                  |
| 5   | Human-centered IoT-based health monitoring in the Healthcare 5.0 era                 | 2024 | Springer Nature                     | https://link.springer.com/article/10.1007/s43926-024-00082-5                                                            |
