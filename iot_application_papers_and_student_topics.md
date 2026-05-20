# Đề xuất bài báo khoa học uy tín làm baseline cho đề tài IoT mức hội thảo

## 1. Mục tiêu tài liệu

Tài liệu này tổng hợp một số bài báo khoa học từ hội thảo, tạp chí/open access hoặc nguồn học thuật uy tín liên quan đến **xây dựng ứng dụng IoT**.  
Mục tiêu là giúp giảng viên và nhóm sinh viên ngành IoT chọn được **baseline paper** để phát triển thành đề tài nghiên cứu ứng dụng ở mức **hội thảo sinh viên/hội thảo khoa học ứng dụng**.

Các hướng ưu tiên:

- Smart Agriculture / Smart Farming
- Smart Home / Smart Lab
- IoT Security / Smart Locker
- Healthcare IoT
- Smart Parking
- IoT Platform / Dashboard / Monitoring System

---

## 2. Danh sách bài báo gợi ý

| STT | Nhóm chủ đề | Bài báo / nguồn tham khảo | Loại nguồn | Nội dung chính | Link tham khảo |
|---|---|---|---|---|---|
| 1 | Smart Agriculture | **IOT Based Smart Farming Application** | E3S Web of Conferences, 2023 | Xây dựng ứng dụng IoT cho nông nghiệp thông minh, tập trung vào giảm lãng phí nước/phân bón và hỗ trợ tăng năng suất. | https://www.e3s-conferences.org/articles/e3sconf/abs/2023/36/e3sconf_iconnect2023_04012/e3sconf_iconnect2023_04012.html |
| 2 | Smart Agriculture Review | **Smart Farming: Internet of Things (IoT)-Based Sustainable Agriculture** | Agriculture, MDPI, 2022 | Tổng quan cảm biến, thiết bị, wireless sensor trong nông nghiệp IoT và các thách thức khi đưa IoT vào canh tác. | https://www.mdpi.com/2077-0472/12/10/1745 |
| 3 | Smart Home Security | **Smart Home Monitoring to Improve Valuable Storage Security Using IoT-Bluetooth** | Procedia Computer Science, Elsevier, 2023 | Đề xuất hệ thống an ninh nhà thông minh dùng Arduino Uno, PIR sensor, ultrasonic sensor và servo làm khóa tự động. | https://www.sciencedirect.com/science/article/pii/S1877050923017854 |
| 4 | Smart Home Energy | **IoT-Enabled Smart Home Energy Monitoring System Using Web Server-Based Control Logic** | Jurnal Informasi dan Teknologi, 2025 | Hệ thống ESP32 cho phép điều khiển và giám sát thiết bị gia đình qua web server, hướng đến tiết kiệm năng lượng. | https://jidt.org/jidt/article/view/611 |
| 5 | Healthcare IoT | **IoT Based Remote Patient Health Monitoring System** | E3S Web of Conferences, 2024 | Hệ thống IoT theo dõi sức khỏe từ xa, phục vụ giám sát bệnh nhân và giảm phụ thuộc vào theo dõi trực tiếp. | https://www.e3s-conferences.org/articles/e3sconf/pdf/2024/121/e3sconf_icrera2024_08005.pdf |
| 6 | Healthcare IoT Review | **Human-centered IoT-based health monitoring in the Healthcare 5.0 era** | Springer Nature, Discover Internet of Things, 2024 | Phân tích literature về IoT health monitoring; chỉ ra gap về human-centered analytics và phân tích dữ liệu dài hạn. | https://link.springer.com/article/10.1007/s43926-024-00082-5 |
| 7 | Smart Agriculture Platform | **Design and application of smart agriculture IoT platform...** | ACM, 2024 | Thiết kế nền tảng IoT phục vụ giám sát điều kiện nông nghiệp và sản xuất nông nghiệp. | https://dl.acm.org/doi/full/10.1145/3697467.3697654 |
| 8 | Smart Parking | **Intelligent and Real-Time Parking System** | E3S Web of Conferences, 2024 | Hệ thống IoT smart parking thời gian thực, hỗ trợ tìm/đặt chỗ đậu xe qua Android/Web application. | https://www.e3s-conferences.org/articles/e3sconf/pdf/2024/02/e3sconf_icregcsd2023_03003.pdf |

---

## 3. Literature Matrix ngắn

| Paper | Domain | Hardware / Technology | Output chính | Limitation có thể khai thác | Hướng phát triển cho sinh viên |
|---|---|---|---|---|---|
| IOT Based Smart Farming Application | Nông nghiệp thông minh | IoT sensors, cloud/application | Giám sát và hỗ trợ canh tác | Có thể chưa tập trung nhiều vào đánh giá độ trễ, độ ổn định, hoặc dashboard phân tích | Thêm dashboard realtime, cảnh báo, khuyến nghị tưới, đánh giá latency và reliability |
| Smart Farming: IoT-Based Sustainable Agriculture | Nông nghiệp bền vững | Wireless sensor networks, IoT devices | Review công nghệ IoT trong nông nghiệp | Là bài tổng quan, chưa có prototype cụ thể cho môi trường giáo dục | Dùng làm nền để xây prototype low-cost cho farm/lab |
| Smart Home Monitoring to Improve Valuable Storage Security | Smart home security | Arduino, PIR, ultrasonic, servo, Bluetooth | Hệ thống bảo vệ tài sản trong nhà | Ngữ cảnh còn hẹp, chưa có quản lý tập trung/log/audit | Chuyển sang smart locker cho phòng lab, thêm RFID, dashboard và cảnh báo |
| IoT-Enabled Smart Home Energy Monitoring System | Smart home energy | ESP32, web server | Giám sát/điều khiển thiết bị gia đình | Có thể chưa đánh giá sâu hành vi sử dụng năng lượng theo thời gian | Phát triển thành hệ thống quản lý năng lượng phòng học/lab |
| IoT Based Remote Patient Health Monitoring System | Healthcare IoT | Health sensors, IoT gateway | Theo dõi sức khỏe từ xa | Cần cẩn trọng về y tế, dữ liệu thật khó thu thập | Làm prototype giáo dục, dùng dữ liệu giả lập hoặc đo cơ bản, không chẩn đoán |
| Human-centered IoT-based health monitoring | Healthcare 5.0 | IoT, analytics, human-centered design | Review và phân tích xu hướng health monitoring | Thiếu prototype triển khai cụ thể cho bối cảnh nhỏ | Xây dashboard cá nhân hóa cảnh báo theo profile người dùng |
| Design and application of smart agriculture IoT platform | Smart agriculture platform | IoT platform, cloud, dashboard | Nền tảng IoT nông nghiệp | Có thể phức tạp nếu triển khai đầy đủ | Thu nhỏ thành multi-farm dashboard cho sinh viên |
| Intelligent and Real-Time Parking System | Smart parking | IoT sensors, mobile/web app | Theo dõi chỗ đậu xe realtime | Cần đánh giá độ chính xác và độ trễ phát hiện slot | Làm smart parking cho campus với dashboard và API |

---

## 4. Đề xuất chủ đề cho nhóm sinh viên IoT

### Chủ đề 1: IoT-Based Smart Agriculture Monitoring and Irrigation Recommendation System

**Mô tả:**  
Xây dựng hệ thống giám sát nông nghiệp thông minh sử dụng ESP32/Arduino và các cảm biến môi trường như độ ẩm đất, nhiệt độ, độ ẩm không khí, ánh sáng. Dữ liệu được gửi về server qua MQTT hoặc HTTP API, sau đó hiển thị trên dashboard web/mobile.

**Baseline paper:**

- IOT Based Smart Farming Application
- Smart Farming: Internet of Things (IoT)-Based Sustainable Agriculture

**Thành phần hệ thống:**

- ESP32 hoặc Arduino + WiFi module
- Soil moisture sensor
- DHT11/DHT22
- Light sensor
- MQTT broker hoặc REST API
- Database: MySQL/PostgreSQL/Firebase/MongoDB
- Dashboard: ReactJS / Next.js / Flutter / Node.js

**Điểm mới đề xuất:**

- Thêm dashboard realtime
- Thêm cảnh báo khi độ ẩm đất thấp
- Thêm rule-based irrigation recommendation
- Đánh giá độ trễ truyền dữ liệu
- Đánh giá độ ổn định trong nhiều giờ chạy liên tục

**Tên đề tài tiếng Anh gợi ý:**

> A Low-Cost IoT-Based Smart Agriculture Monitoring and Irrigation Recommendation System for Educational Farm Environments

---

### Chủ đề 2: Smart Lab Energy Monitoring System Using ESP32 and Web Dashboard

**Mô tả:**  
Xây dựng hệ thống giám sát năng lượng hoặc trạng thái thiết bị trong phòng học/phòng lab. Hệ thống có thể theo dõi thiết bị đang bật/tắt, nhiệt độ phòng, hoặc mức tiêu thụ điện nếu có cảm biến dòng.

**Baseline paper:**

- IoT-Enabled Smart Home Energy Monitoring System Using Web Server-Based Control Logic

**Thành phần hệ thống:**

- ESP32
- Relay module
- Current sensor nếu có
- Temperature sensor
- Web dashboard
- API lưu dữ liệu thiết bị

**Điểm mới đề xuất:**

- Ứng dụng cho phòng lab thay vì nhà thông minh
- Thống kê thời gian sử dụng thiết bị
- Cảnh báo khi thiết bị bật ngoài giờ
- Dashboard tiết kiệm năng lượng
- Báo cáo theo ngày/tuần

**Tên đề tài tiếng Anh gợi ý:**

> An IoT-Based Smart Laboratory Energy Monitoring and Alerting System Using ESP32 and Web Dashboard

---

### Chủ đề 3: IoT-Based Smart Locker Security System for University Laboratories

**Mô tả:**  
Xây dựng hệ thống tủ thông minh quản lý thiết bị phòng lab. Người dùng mở tủ bằng RFID/QR/Bluetooth, hệ thống lưu log, cảnh báo khi mở trái phép, và hiển thị lịch sử truy cập trên dashboard.

**Baseline paper:**

- Smart Home Monitoring to Improve Valuable Storage Security Using IoT-Bluetooth

**Thành phần hệ thống:**

- Arduino/ESP32
- RFID module hoặc QR login
- PIR sensor
- Ultrasonic sensor
- Servo lock
- Buzzer
- Dashboard quản lý lịch sử mở tủ

**Điểm mới đề xuất:**

- Chuyển ngữ cảnh từ smart home sang smart lab
- Có user management
- Có access log
- Có cảnh báo bất thường
- Có dashboard quản trị thiết bị

**Tên đề tài tiếng Anh gợi ý:**

> An IoT-Based Smart Locker Security and Access Logging System for University Laboratories

---

### Chủ đề 4: Campus Smart Parking Monitoring System with Real-Time Slot Availability

**Mô tả:**  
Xây dựng hệ thống giám sát chỗ đậu xe trong khuôn viên trường. Mỗi slot có cảm biến phát hiện có xe/không có xe. Dữ liệu được gửi về server và hiển thị trạng thái realtime trên dashboard hoặc mobile app.

**Baseline paper:**

- Intelligent and Real-Time Parking System

**Thành phần hệ thống:**

- ESP32/Arduino
- Ultrasonic sensor hoặc IR sensor
- API server
- Dashboard bản đồ slot
- Mobile/web interface

**Điểm mới đề xuất:**

- Ứng dụng cho campus
- Đánh giá độ chính xác phát hiện slot
- Đánh giá latency cập nhật trạng thái
- Giao diện trực quan cho người dùng
- Có thống kê giờ cao điểm

**Tên đề tài tiếng Anh gợi ý:**

> A Real-Time IoT-Based Smart Parking Monitoring System for University Campus Environments

---

### Chủ đề 5: Human-Centered IoT Health Monitoring Dashboard for Elderly Care Simulation

**Mô tả:**  
Xây dựng dashboard IoT theo dõi một số chỉ số sức khỏe cơ bản như nhịp tim, nhiệt độ, SpO2 hoặc dữ liệu giả lập. Hệ thống tập trung vào cảnh báo và hiển thị thân thiện cho người chăm sóc.

**Baseline paper:**

- IoT Based Remote Patient Health Monitoring System
- Human-centered IoT-based health monitoring in the Healthcare 5.0 era

**Lưu ý:**  
Đề tài này chỉ nên triển khai ở mức prototype giáo dục. Không nên tuyên bố hệ thống có khả năng chẩn đoán bệnh hoặc thay thế bác sĩ.

**Thành phần hệ thống:**

- ESP32
- MAX30102 nếu có
- Temperature sensor
- Dashboard cảnh báo
- Dữ liệu giả lập hoặc dữ liệu thử nghiệm cá nhân đơn giản

**Điểm mới đề xuất:**

- Cá nhân hóa ngưỡng cảnh báo theo từng user
- Dashboard thân thiện với người chăm sóc
- Lưu lịch sử chỉ số
- Phân tích xu hướng đơn giản

**Tên đề tài tiếng Anh gợi ý:**

> A Human-Centered IoT Health Monitoring Dashboard for Elderly Care Simulation

---

## 5. Chủ đề nên chọn nhất

Nếu chỉ chọn một hướng để giao cho nhiều nhóm sinh viên, nên chọn:

# IoT-Based Smart Agriculture Monitoring and Irrigation Recommendation System

## Lý do chọn

- Dễ triển khai với chi phí thấp
- Phù hợp với bối cảnh Việt Nam
- Có nhiều paper nền để viết literature review
- Dễ mở rộng sang AIoT hoặc Agentic AI sau này
- Dễ đánh giá bằng số liệu: độ trễ, độ ổn định, sai số cảm biến, độ chính xác cảnh báo
- Dễ demo trong hội thảo hoặc seminar

## Contribution có thể viết trong bài hội thảo

1. Thiết kế hệ thống IoT low-cost cho giám sát nông nghiệp.
2. Xây dựng pipeline dữ liệu từ sensor node đến dashboard.
3. Đề xuất cơ chế cảnh báo và khuyến nghị tưới dựa trên ngưỡng/rule.
4. Đánh giá thực nghiệm về latency, reliability và usability.
5. Cung cấp prototype có thể tái sử dụng trong môi trường giáo dục.

## Cấu trúc bài hội thảo gợi ý

### Abstract

Tóm tắt vấn đề, giải pháp IoT, kết quả demo và đóng góp chính.

### 1. Introduction

- Nhu cầu smart agriculture
- Vấn đề giám sát thủ công
- Lý do cần giải pháp low-cost
- Mục tiêu nghiên cứu

### 2. Related Work

- Tóm tắt các bài IoT smart farming
- Tóm tắt bài review về IoT agriculture
- Chỉ ra gap: thiếu prototype giáo dục, thiếu đánh giá độ trễ/độ ổn định, thiếu dashboard dễ dùng

### 3. System Design

- Kiến trúc tổng thể
- Sensor node
- Communication layer
- Backend/API
- Database
- Dashboard

### 4. Implementation

- Thiết bị sử dụng
- Luồng dữ liệu
- Cấu trúc API
- Giao diện dashboard

### 5. Evaluation

Các chỉ số nên đo:

| Metric | Mô tả |
|---|---|
| Latency | Thời gian từ sensor gửi dữ liệu đến dashboard cập nhật |
| Data loss rate | Tỷ lệ bản ghi bị mất |
| Sensor stability | Độ ổn định khi chạy liên tục |
| Alert accuracy | Cảnh báo đúng/sai theo điều kiện ngưỡng |
| Usability | Đánh giá giao diện qua khảo sát người dùng |

### 6. Results and Discussion

- Trình bày bảng kết quả
- Phân tích điểm mạnh/yếu
- So sánh với baseline paper ở mức chức năng

### 7. Conclusion

- Tổng kết hệ thống
- Nêu đóng góp
- Hướng mở rộng: ML prediction, AI agent, RAG advisory, mobile app

---

## 6. Gợi ý chia nhóm sinh viên

| Vai trò | Công việc |
|---|---|
| Hardware Engineer | Kết nối ESP32/sensor, đọc dữ liệu |
| Backend Developer | Xây API, database, MQTT/HTTP |
| Frontend Developer | Xây dashboard realtime |
| Data/Evaluation Member | Thiết kế test case, đo latency, tạo bảng kết quả |
| Paper Writer | Viết introduction, related work, methodology, results |

---

## 7. Checklist để nhóm sinh viên đủ điều kiện viết bài hội thảo

- [ ] Có ít nhất 5 bài liên quan trong Related Work
- [ ] Có một baseline paper rõ ràng
- [ ] Có prototype chạy được
- [ ] Có sơ đồ kiến trúc hệ thống
- [ ] Có ảnh phần cứng hoặc mô phỏng
- [ ] Có dashboard hoặc giao diện
- [ ] Có dữ liệu thực nghiệm hoặc dữ liệu giả lập hợp lý
- [ ] Có bảng đánh giá latency/reliability/accuracy
- [ ] Có phần discussion so sánh với baseline
- [ ] Có hướng mở rộng rõ ràng

---

## 8. Kết luận

Các chủ đề IoT ứng dụng như smart agriculture, smart lab energy, smart locker, smart parking và health monitoring đều phù hợp để sinh viên phát triển thành bài hội thảo.  
Trong đó, hướng **Smart Agriculture Monitoring and Irrigation Recommendation** là lựa chọn tối ưu nhất vì có tính thực tiễn cao, dễ triển khai, dễ đánh giá và phù hợp với xu hướng AIoT trong đào tạo kỹ thuật.

