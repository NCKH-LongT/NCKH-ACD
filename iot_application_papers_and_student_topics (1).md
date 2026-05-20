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


---

# 9. Mở rộng đề tài IoT thuần thành IoT + Server + Web để viết bài hội thảo

## 9.1. Có nên mở rộng IoT thuần lên có server và web không?

Có. Đây là hướng **rất phù hợp cho sinh viên IoT** vì đa số đề tài IoT thuần thường chỉ dừng ở mức:

- Đọc dữ liệu từ cảm biến
- Hiển thị lên LCD/Serial Monitor
- Điều khiển relay hoặc thiết bị đầu ra
- Gửi dữ liệu đơn giản qua WiFi/Bluetooth

Nếu chỉ dừng ở mức này, đề tài thường giống **đồ án kỹ thuật** hơn là **bài báo hội thảo**.  
Khi mở rộng thêm **server + database + web dashboard**, đề tài sẽ có tính hệ thống rõ hơn và dễ viết thành bài báo ứng dụng.

## 9.2. Vì sao thêm server và web giúp đề tài mạnh hơn?

| Thành phần mở rộng | Giá trị nghiên cứu / giá trị hội thảo |
|---|---|
| Server/API | Cho thấy hệ thống có kiến trúc rõ ràng, không chỉ là mạch điện tử đơn lẻ |
| Database | Có dữ liệu lịch sử để phân tích, đánh giá và trực quan hóa |
| Web dashboard | Tăng tính ứng dụng thực tế, dễ demo và dễ đánh giá usability |
| Realtime monitoring | Có thể đo latency, reliability, data loss |
| Alert system | Tạo use case rõ: cảnh báo khi vượt ngưỡng |
| User management | Chuyển từ prototype cá nhân sang hệ thống nhiều người dùng |
| Report/statistics | Có kết quả định lượng để đưa vào bài báo |
| Deployment | Cho thấy khả năng vận hành thực tế ở môi trường lab/campus/farm |

Vì vậy, sinh viên học IoT nếu có thể code server và web đơn giản thì nên định hướng đề tài theo mô hình:

> IoT Device → API/MQTT Server → Database → Web Dashboard → Alert/Recommendation

---

## 10. Mô hình kiến trúc đề tài IoT + Web phù hợp cho sinh viên

## 10.1. Kiến trúc tổng quát

```text
[Sensors / Actuators]
        |
        | WiFi / MQTT / HTTP
        v
[ESP32 / Arduino Gateway]
        |
        | REST API or MQTT Publish
        v
[Backend Server]
        |
        | Save / Query
        v
[Database]
        |
        | API Response / WebSocket
        v
[Web Dashboard]
        |
        | Alert / Report / Control
        v
[User / Admin / Lecturer]
```

## 10.2. Stack công nghệ gợi ý

| Layer | Công nghệ dễ dùng cho sinh viên |
|---|---|
| Device | ESP32, Arduino, Raspberry Pi nếu có |
| Sensor | DHT11/DHT22, soil moisture, ultrasonic, PIR, light sensor, current sensor |
| Communication | HTTP REST API, MQTT |
| Backend | Node.js Express, NestJS, Flask, FastAPI |
| Database | MongoDB, MySQL, PostgreSQL, Firebase |
| Realtime | Socket.IO, MQTT subscribe, Firebase realtime |
| Web | ReactJS, Next.js, Vue.js, plain HTML/CSS/JS |
| Chart | Chart.js, Recharts, ECharts |
| Deployment | Docker, Render, Railway, VPS, local server |

## 10.3. Mức tối thiểu để đủ làm bài hội thảo

Một đề tài nên có ít nhất:

- 1 thiết bị IoT gửi dữ liệu thật hoặc dữ liệu mô phỏng hợp lý
- 1 server nhận dữ liệu qua API/MQTT
- 1 database lưu lịch sử dữ liệu
- 1 dashboard hiển thị realtime hoặc gần realtime
- 1 chức năng cảnh báo hoặc khuyến nghị
- 1 bảng đánh giá thực nghiệm

---

# 11. Gợi ý nâng cấp từng chủ đề IoT thành đề tài hội thảo có Web/App

## Chủ đề 1: Smart Agriculture Monitoring + Web Dashboard

### Phiên bản IoT thuần

- ESP32 đọc độ ẩm đất, nhiệt độ, độ ẩm không khí
- Hiển thị dữ liệu lên Serial Monitor hoặc LCD
- Bật/tắt bơm nước theo ngưỡng

### Phiên bản hội thảo nên làm

> A Web-Based IoT Monitoring and Irrigation Recommendation System for Smart Agriculture

### Mở rộng cần có

- ESP32 gửi dữ liệu lên server
- Backend lưu dữ liệu cảm biến
- Dashboard hiển thị realtime
- Biểu đồ độ ẩm đất theo thời gian
- Cảnh báo khi độ ẩm thấp
- Khuyến nghị tưới dựa trên rule
- Trang quản lý nhiều khu vực trồng cây

### Contribution có thể viết

1. Thiết kế hệ thống IoT low-cost cho nông nghiệp.
2. Xây dựng web dashboard realtime phục vụ giám sát.
3. Đề xuất cơ chế cảnh báo và khuyến nghị tưới đơn giản.
4. Đánh giá độ trễ truyền dữ liệu và độ ổn định của hệ thống.

### Metric đánh giá

| Metric | Cách đo |
|---|---|
| Latency | Thời gian từ lúc ESP32 gửi dữ liệu đến lúc dashboard cập nhật |
| Data loss rate | Số bản ghi mất / tổng số bản ghi gửi |
| Alert accuracy | Cảnh báo đúng khi độ ẩm dưới ngưỡng |
| System uptime | Thời gian hệ thống chạy liên tục không lỗi |
| Usability | Khảo sát người dùng về dashboard |

---

## Chủ đề 2: Smart Lab Energy Monitoring + Web Dashboard

### Phiên bản IoT thuần

- ESP32 bật/tắt relay
- Đọc trạng thái thiết bị
- Hiển thị trạng thái thiết bị trên LCD

### Phiên bản hội thảo nên làm

> A Web-Based IoT Energy Monitoring and Alerting System for University Laboratories

### Mở rộng cần có

- Dashboard quản lý thiết bị trong phòng lab
- Ghi nhận thời gian bật/tắt thiết bị
- Cảnh báo khi thiết bị bật ngoài giờ
- Thống kê thời lượng sử dụng theo ngày/tuần
- Admin có thể xem lịch sử thiết bị

### Contribution có thể viết

1. Đề xuất hệ thống IoT giám sát năng lượng cho phòng lab.
2. Xây dựng dashboard theo dõi trạng thái thiết bị.
3. Phát hiện hành vi sử dụng bất thường.
4. Đánh giá hiệu quả cảnh báo và độ trễ cập nhật.

### Metric đánh giá

| Metric | Cách đo |
|---|---|
| Device status accuracy | So sánh trạng thái thiết bị thực tế và trạng thái hiển thị |
| Alert response time | Thời gian từ lúc phát hiện bất thường đến lúc hiển thị cảnh báo |
| Data completeness | Tỷ lệ dữ liệu trạng thái được lưu đầy đủ |
| Dashboard usability | Khảo sát người dùng thử nghiệm |

---

## Chủ đề 3: Smart Locker Security + Access Log Web

### Phiên bản IoT thuần

- Dùng RFID/Bluetooth mở khóa
- Servo mở/đóng tủ
- Buzzer báo động

### Phiên bản hội thảo nên làm

> An IoT-Based Smart Locker Security System with Web-Based Access Logging for University Laboratories

### Mở rộng cần có

- Web quản lý danh sách người dùng
- Lưu log ai mở tủ, mở lúc nào
- Cảnh báo truy cập không hợp lệ
- Trang thống kê lượt mở tủ
- Admin có thể xem lịch sử truy cập

### Contribution có thể viết

1. Thiết kế hệ thống smart locker cho phòng lab.
2. Tích hợp xác thực người dùng và access logging.
3. Xây dựng dashboard giám sát an ninh thiết bị.
4. Đánh giá độ chính xác xác thực và thời gian phản hồi.

### Metric đánh giá

| Metric | Cách đo |
|---|---|
| Authentication accuracy | Tỷ lệ xác thực đúng/sai |
| Unlock response time | Thời gian từ lúc quét thẻ đến lúc mở khóa |
| Unauthorized alert rate | Tỷ lệ cảnh báo đúng khi truy cập không hợp lệ |
| Log completeness | Số lần mở tủ được ghi log đầy đủ |

---

## Chủ đề 4: Campus Smart Parking + Realtime Web Map

### Phiên bản IoT thuần

- Cảm biến ultrasonic/IR phát hiện xe
- LED báo slot trống/có xe

### Phiên bản hội thảo nên làm

> A Real-Time Web-Based IoT Smart Parking Monitoring System for University Campuses

### Mở rộng cần có

- Web dashboard hiển thị sơ đồ bãi xe
- Trạng thái từng slot realtime
- Thống kê giờ cao điểm
- API cho mobile/web truy vấn slot trống
- Cảnh báo khi bãi xe đầy

### Contribution có thể viết

1. Xây dựng hệ thống phát hiện slot đậu xe bằng IoT.
2. Thiết kế dashboard realtime cho campus parking.
3. Đánh giá độ chính xác phát hiện và độ trễ cập nhật.
4. Phân tích dữ liệu sử dụng bãi xe theo thời gian.

### Metric đánh giá

| Metric | Cách đo |
|---|---|
| Slot detection accuracy | So sánh trạng thái cảm biến với quan sát thực tế |
| Update latency | Thời gian cập nhật từ sensor lên web |
| False detection rate | Tỷ lệ phát hiện sai có xe/không có xe |
| Peak hour statistics | Thống kê số slot sử dụng theo khung giờ |

---

## Chủ đề 5: IoT Health Monitoring + Caregiver Dashboard

### Phiên bản IoT thuần

- Đọc nhịp tim, nhiệt độ hoặc SpO2
- Hiển thị trên OLED/LCD

### Phiên bản hội thảo nên làm

> A Web-Based IoT Health Monitoring Dashboard for Elderly Care Simulation

### Mở rộng cần có

- Dashboard cho người chăm sóc
- Lưu lịch sử chỉ số
- Cảnh báo khi chỉ số vượt ngưỡng
- Cá nhân hóa ngưỡng cảnh báo theo từng user
- Biểu đồ xu hướng theo thời gian

### Lưu ý đạo đức và phạm vi

Đề tài này chỉ nên viết ở mức **prototype hỗ trợ giám sát**.  
Không nên tuyên bố hệ thống có khả năng chẩn đoán bệnh hoặc thay thế bác sĩ.

### Contribution có thể viết

1. Xây dựng prototype IoT health monitoring.
2. Thiết kế dashboard thân thiện với người chăm sóc.
3. Đề xuất cảnh báo cá nhân hóa theo ngưỡng.
4. Đánh giá độ trễ, độ ổn định và khả năng sử dụng.

---

# 12. Cách biến đề tài IoT + Web thành bài báo hội thảo

## 12.1. Công thức đặt tên đề tài

Có thể dùng công thức:

> A Web-Based IoT [Monitoring/Control/Alerting] System for [Domain/Context]

Ví dụ:

- A Web-Based IoT Monitoring and Irrigation Recommendation System for Smart Agriculture
- A Web-Based IoT Energy Monitoring and Alerting System for University Laboratories
- An IoT-Based Smart Locker Security System with Web-Based Access Logging
- A Real-Time Web-Based IoT Smart Parking Monitoring System for University Campuses
- A Web-Based IoT Health Monitoring Dashboard for Elderly Care Simulation

## 12.2. Công thức contribution

Một bài hội thảo ứng dụng IoT có thể ghi contribution như sau:

1. We design a low-cost IoT architecture for real-time monitoring in a specific domain.
2. We implement an end-to-end prototype integrating sensor nodes, backend server, database, and web dashboard.
3. We provide alerting or recommendation functions based on collected sensor data.
4. We evaluate the system in terms of latency, data completeness, reliability, and usability.

## 12.3. Công thức đánh giá

Không nên chỉ demo hoạt động. Cần có số liệu đánh giá.

| Loại đánh giá | Ví dụ |
|---|---|
| Technical performance | latency, data loss rate, uptime |
| Sensor accuracy | so sánh với thiết bị đo tham chiếu hoặc quan sát thủ công |
| Alert performance | cảnh báo đúng/sai theo kịch bản test |
| Usability | khảo sát 5–10 người dùng thử dashboard |
| System reliability | chạy liên tục 2–8 giờ và ghi nhận lỗi |
| Scalability nhỏ | thử nhiều sensor node hoặc nhiều device giả lập |

## 12.4. Test case gợi ý

| Test case | Mô tả | Kết quả mong đợi |
|---|---|---|
| TC01 - Normal data transmission | Sensor gửi dữ liệu mỗi 5 giây | Server nhận và lưu đầy đủ |
| TC02 - Dashboard update | Có dữ liệu mới từ server | Dashboard cập nhật trong thời gian chấp nhận được |
| TC03 - Threshold alert | Giá trị cảm biến vượt ngưỡng | Hệ thống hiển thị cảnh báo |
| TC04 - Missing data | Device ngừng gửi dữ liệu | Dashboard báo mất kết nối hoặc dữ liệu cũ |
| TC05 - Wrong/abnormal data | Sensor gửi giá trị bất thường | Hệ thống đánh dấu hoặc cảnh báo |
| TC06 - Multi-device simulation | Nhiều thiết bị gửi dữ liệu | Server xử lý và phân loại đúng thiết bị |
| TC07 - User interaction | Người dùng xem chart/log/report | Giao diện phản hồi đúng |

---

# 13. Gợi ý chia mức độ đề tài cho sinh viên

## Mức cơ bản

Phù hợp với nhóm mới học IoT.

- 1 ESP32
- 2–3 cảm biến
- Gửi dữ liệu HTTP
- Backend Node.js Express
- Database MongoDB/Firebase
- Dashboard hiển thị bảng và chart
- Cảnh báo theo ngưỡng

## Mức khá

Phù hợp với nhóm có khả năng web/backend tốt.

- Nhiều device
- MQTT broker
- WebSocket realtime
- User login
- Dashboard nhiều màn hình
- Export report CSV
- Test latency/data loss

## Mức tốt để viết hội thảo mạnh hơn

Phù hợp với nhóm muốn có bài nghiêm túc.

- Multi-device hoặc multi-zone
- Rule-based recommendation
- Anomaly detection đơn giản
- Đánh giá hệ thống theo kịch bản
- So sánh REST API và MQTT nếu có thời gian
- Viết paper đầy đủ theo cấu trúc hội thảo

---

# 14. Template giao đề tài cho sinh viên

## Tên đề tài

A Web-Based IoT Monitoring and Alerting System for [Domain]

## Bối cảnh

Mô tả vấn đề thực tế trong một domain cụ thể như nông nghiệp, phòng lab, bãi xe, smart home hoặc chăm sóc sức khỏe.

## Mục tiêu

- Xây dựng thiết bị IoT thu thập dữ liệu cảm biến
- Xây dựng server nhận và lưu dữ liệu
- Xây dựng dashboard hiển thị realtime
- Tạo chức năng cảnh báo hoặc khuyến nghị
- Đánh giá hệ thống bằng các chỉ số kỹ thuật

## Yêu cầu chức năng

- Device gửi dữ liệu lên server
- Server lưu dữ liệu vào database
- Web hiển thị dữ liệu mới nhất
- Web hiển thị biểu đồ lịch sử
- Hệ thống cảnh báo khi vượt ngưỡng
- Admin có thể xem log hoặc report

## Yêu cầu phi chức năng

- Dữ liệu cập nhật trong vòng 1–5 giây
- Hệ thống chạy ổn định ít nhất 2 giờ trong thử nghiệm
- Giao diện dễ sử dụng
- API có tài liệu đơn giản
- Dữ liệu có timestamp và device ID

## Kết quả cần nộp

- Source code device
- Source code backend
- Source code web dashboard
- Database schema
- Sơ đồ kiến trúc
- Video demo
- Báo cáo kết quả thử nghiệm
- Bài viết dạng conference paper

---

# 15. Kết luận cập nhật

Với sinh viên IoT có thể code server và web đơn giản, hướng đề tài tốt nhất không nên chỉ là **IoT device prototype**, mà nên nâng thành:

> IoT device + backend server + database + web dashboard + alert/recommendation + evaluation

Cách mở rộng này giúp đề tài có đủ thành phần của một **application/system paper**:

- Có vấn đề thực tế
- Có kiến trúc hệ thống
- Có prototype end-to-end
- Có dashboard dễ demo
- Có dữ liệu thực nghiệm
- Có metric đánh giá
- Có khả năng so sánh với baseline paper

Do đó, đây là hướng rất phù hợp để giao cho nhóm sinh viên ngành IoT làm đề tài hội thảo.
