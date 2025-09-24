# 🐾 PetService - Hệ thống quản lý dịch vụ thú cưng

[![Java](https://img.shields.io/badge/Java-17-orange.svg)](https://www.oracle.com/java/)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-green.svg)](https://spring.io/projects/spring-boot)
[![React](https://img.shields.io/badge/React-18-blue.svg)](https://reactjs.org/)
[![Vite](https://img.shields.io/badge/Vite-5.x-purple.svg)](https://vitejs.dev/)

## 📋 Mục lục

- [Giới thiệu](#giới-thiệu)
- [Tính năng](#tính-năng)
- [Công nghệ sử dụng](#công-nghệ-sử-dụng)
- [Cài đặt](#cài-đặt)
- [Cấu trúc dự án](#cấu-trúc-dự-án)
- [Screenshots](#screenshots)
- [API Documentation](#api-documentation)

## 🎯 Giới thiệu

PetService là một hệ thống quản lý dịch vụ thú cưng toàn diện, bao gồm:
- **Frontend**: Giao diện người dùng được xây dựng bằng React + Vite
- **Backend**: API server được phát triển bằng Spring Boot
- **Database**: Hỗ trợ nhiều loại cơ sở dữ liệu ở đây là mysql

Hệ thống cho phép người dùng đặt lịch hẹn, mua sắm sản phẩm, quản lý thông tin thú cưng và nhiều tính năng khác.

Đây là một bài tập lớn của tôi - Trịnh Lê Xuân Bách. Kết quả bài tập lớn là được A. Mặc dù còn nhiều thiếu xót từ BE cho đến FE nhưng cũng là sự cố gắng khoảng 3 tháng trời. Tôi đã mất 1 tháng trời chỉ để tìm hiểu về code giao diện để code ra cái homepage, riêng giao diện homepage chỉ là code tay. Bản thân tôi khá tâm huyết với bài tập lớn này.
Nói sơ qua một chút, bản thân tôi rất yêu thích thú cưng, cụ thể là chó mèo, vậy nên từ năm nhất đã ấp ủ có thể làm được 1 trang web kiểu dạng cộng đồng, forum mà ở đó tích hợp hết mọi thứ, từ viết bài trao đổi cách chăm sóc thú cưng, cho đến mua sắm sản phẩm thú ăn, quản lí thông tin, đặt lịch hẹn các kiểu. Nhưng do bản thân còn nhiều thiếu xót, thời gian cũng có hạn cộng thêm với việc làm 1 mình cũng khiến cho bản thân nhiều lúc bị mệt mỏi, nản chí làm cho dự án chưa được như ý muốn. Từ đầu năm 3 lần đầu làm bài tập lớn OOP bản thân đã code 1 PetService rồi, nhưng web đó khá cùi, chả có gì nhưng cũng là bước đầu cho niềm ấp ủ từ lâu. Đến kì 2 năm 3 là lập trình web, bản thân đã làm lại và cũng khá như ý (ở tại thời điểm đó). Và thành quả là ở đây.
Còn bây giờ, tôi đã biết thêm đôi thứ, nhiều công nghệ hơn, thiết kế database cho dự án này tốt hơn, thêm rất nhiều module hay ho, quan trọng nữa để làm cho PetService không còn là bài tập lớn mà với mong muốn là có thể là 1 hệ sinh thái, 1 cái gì đó thực tế. Chắc chắn tôi sẽ làm lại từ đầu đến đuôi dự án này, và tất nhiên sẽ là đồ án tốt nghiệp của tôi, bây giờ tôi đang lên quá trình làm base các kiểu rùi.
Đôi lời nếu có HR xem, bản thân em là sinh viên còn nhiều thiếu xót, mong anh chị nhẹ tay ạ.

## ✨ Tính năng

### 👤 Dành cho khách hàng
- 🔐 Đăng ký/Đăng nhập tài khoản
- 🐕 Quản lý thông tin thú cưng
- 📅 Đặt lịch hẹn với bác sĩ
- 🛒 Mua sắm sản phẩm online
- 📝 Xem blog và bài viết
- 💳 Thanh toán trực tuyến

### 👨‍⚕️ Dành cho bác sĩ
- 📊 Dashboard quản lý lịch hẹn
- 📋 Xem thông tin bệnh nhân
- 📝 Ghi chú và chẩn đoán

### 👩‍💼 Dành cho lễ tân
- 📞 Quản lý cuộc gọi và lịch hẹn
- 👥 Hỗ trợ khách hàng

### 🔧 Dành cho admin
- 📈 Dashboard tổng quan
- 👥 Quản lý người dùng
- 🛍️ Quản lý sản phẩm
- 📝 Quản lý nội dung

## 🛠️ Công nghệ sử dụng

### Backend
- **Java 21**
- **Spring Boot 3.2.3**
- **Spring Security**
- **Spring Data JPA**
- **JWT Authentication** (io.jsonwebtoken)
- **Jackson JSR310** (LocalDateTime support)
- **Lombok** (Code generation)
- **SpringDoc OpenAPI** (Swagger UI)
- **MySQL Connector** (8.0.33)
- **Maven**
- **Docker**

### Frontend
- **React 19.0.0**
- **Vite 6.1.0**
- **React Router DOM 7.4.0**
- **Ant Design 5.24.0** (UI Components)
- **Tailwind CSS 4.0.8**
- **Framer Motion 12.7.4** (Animations)
- **Styled Components 6.1.15**
- **React Intersection Observer 9.16.0**
- **ESLint 9.19.0**
- **PostCSS & Autoprefixer**

### Database
- **MySQL 8.0** (Primary database)
- **Hibernate JPA** (ORM)
- **MySQL8Dialect**

### Development Tools
- **Maven** (Build tool)
- **Docker** (Containerization)
- **Git** (Version control)
- **ESLint** (Code linting)
- **SpringDoc OpenAPI** (API documentation)

## 🚀 Cài đặt

### Yêu cầu hệ thống
- Java 21+
- Node.js 18+
- Maven 3.6+
- MySQL 8.0+

### Backend Setup

1. **Clone repository**
```bash
git clone <repository-url>
cd PetService/PetService_BE/PetService
```

2. **Cấu hình database**
```properties
# application.properties
spring.datasource.url=jdbc:mysql://localhost:3306/petservice
spring.datasource.username=your_username
spring.datasource.password=your_password
```

3. **Chạy ứng dụng**
```bash
# Sử dụng Maven
./mvnw spring-boot:run

# Hoặc build JAR
./mvnw clean package
java -jar target/PetService-0.0.1-SNAPSHOT.jar
```

### Frontend Setup

1. **Vào thư mục frontend**
```bash
cd PetService/PetService_FE/PetService_FE
```

2. **Cài đặt dependencies**
```bash
npm install
```

3. **Chạy development server**
```bash
npm run dev
```

4. **Build production**
```bash
npm run build
```

### Docker Setup

```bash
# Build và chạy với Docker
docker build -t petservice-backend .
docker run -p 8080:8080 petservice-backend
```

## 📁 Cấu trúc dự án

```
PetService/
├── PetService_BE/                 # Backend (Spring Boot)
│   └── PetService/
│       ├── src/main/java/        # Source code
│       ├── src/main/resources/   # Config files
│       └── target/               # Build output
├── PetService_FE/                # Frontend (React)
│   └── PetService_FE/
│       ├── src/                  # Source code
│       ├── public/               # Static files
│       └── dist/                 # Build output
└── pic/                          # Screenshots & images
```

## 📸 Screenshots

### 🏠 Trang chủ
![Homepage 1](pic/homepage1.png)
*Giao diện trang chủ với banner*

![Homepage 2](pic/homepage2.png)
*Phần giới thiệu về dịch vụ chăm sóc thú cưng*

![Homepage 3](pic/homepage3.png)
*Thông tin bảng giá*

![Homepage 4](pic/homepage4.png)
*Một vài thông tin nhỏ*

![Homepage 5](pic/homepage5.png)
*Thông tin bảng giá*

![Homepage 6](pic/homepage6.png)
*Pet Service*

![Homepage 7](pic/homepage7.png)
*Thông tin bảng giá*

![Homepage 8](pic/homepage8.png)
*Sản phẩm nổi bật*

![Homepage 9](pic/homepage9.png)
*Footer, thông tin liên hệ*

### 🔐 Đăng nhập/Đăng ký
![Login](pic/login.png)
*Giao diện đăng nhập hệ thống*

![Logout](pic/logout.png)
*Giao diện đăng kí*

### 🛒 Cửa hàng
![Shop 1](pic/shop1.png)
*Trang danh sách sản phẩm*

![Shop 2](pic/shop2.png)
*Bộ lọc và tìm kiếm sản phẩm*

![Shop 3](pic/shop3.png)
*Giỏ hàng và thanh toán*

![Shop Detail 1](pic/shop_detail1.png)
*Chi tiết sản phẩm*

![Shop Detail 2](pic/shop_detail2.png)
*Thông tin sản phẩm*

### 📅 Đặt lịch hẹn
![Appointment](pic/appointment.png)
*Giao diện đặt lịch hẹn với bác sĩ*

### 📝 Blog
![Blog](pic/blog.png)
*Trang blog với danh sách bài viết*

![Blog Detail](pic/blog_detail.png)
*Chi tiết bài viết blog*

### 👤 Thông tin cá nhân
![Info 1](pic/info1.png)
*Dashboard thông tin cá nhân*

![Info 2](pic/info2.png)
*Đổi mật khẩu*

![Info 3](pic/info3.png)
*Quản lý thông tin thú cưng*

![Info 4](pic/info4.png)
*Lịch sử đặt hẹn*

![Info 5](pic/info5.png)
*Lịch sử mua hàng*

![Info 6](pic/info6.png)
*Danh sách bài viết*

### 💳 Thanh toán
![Payment 1](pic/pay1.png)
*Giao diện thanh toán*

![Payment 2](pic/pay2.png)
*Xác nhận thanh toán*

![Payment 3](pic/pay3.png)
*Kết quả thanh toán*

### 👨‍⚕️ Dashboard bác sĩ
![Doctor 1](pic/doctor1.png)
*Dashboard quản lý lịch hẹn*

![Doctor 2](pic/doctor2.png)
*Chi tiết thông tin bệnh nhân*

### 👩‍💼 Dashboard lễ tân
![Receptionist](pic/receptionist.png)
*Giao diện quản lý cho lễ tân*

### 🔧 Dashboard admin
![Admin 1](pic/admin1.png)
*Quản lí các user*

![Admin 2](pic/admin2.png)
*Quản lý các thú cưng*

![Admin 3](pic/admin3.png)
*Quản lý bài viết*

![Admin 4](pic/admin4.png)
*Quản lí đơn hàng*

## 📚 API Documentation

### Authentication Endpoints
```
POST   /api/users/register    # Đăng ký tài khoản mới
POST   /api/users/login        # Đăng nhập hệ thống
GET    /api/users/me           # Lấy thông tin user hiện tại
```

### User Management
```
GET    /api/users              # Lấy danh sách tất cả users (Admin)
GET    /api/users/{id}         # Lấy thông tin user theo ID
GET    /api/users/doctors      # Lấy danh sách bác sĩ
PUT    /api/users/{id}         # Cập nhật thông tin user
DELETE /api/users/{id}         # Xóa user (Admin)
```

### Pet Management
```
GET    /api/pets               # Lấy danh sách thú cưng
GET    /api/pets/{id}          # Lấy thông tin thú cưng theo ID
POST   /api/pets               # Thêm thú cưng mới
PUT    /api/pets/{id}          # Cập nhật thông tin thú cưng
DELETE /api/pets/{id}          # Xóa thú cưng
```

### Appointment Management
```
GET    /api/appointments       # Lấy danh sách lịch hẹn
GET    /api/appointments/{id}  # Lấy chi tiết lịch hẹn
POST   /api/appointments       # Tạo lịch hẹn mới
PUT    /api/appointments/{id}  # Cập nhật lịch hẹn
DELETE /api/appointments/{id} # Hủy lịch hẹn
PUT    /api/appointments/{id}/status # Cập nhật trạng thái lịch hẹn
PUT    /api/appointments/{id}/note  # Cập nhật ghi chú lịch hẹn
```

### Product Management (Items)
```
GET    /api/items              # Lấy danh sách sản phẩm
GET    /api/items/{id}         # Lấy chi tiết sản phẩm
POST   /api/items              # Tạo sản phẩm mới (Admin)
PUT    /api/items/{id}         # Cập nhật sản phẩm (Admin)
DELETE /api/items/{id}         # Xóa sản phẩm (Admin)
```

### Article Management (Blog)
```
GET    /api/articles           # Lấy danh sách bài viết
GET    /api/articles/{id}       # Lấy chi tiết bài viết
POST   /api/articles            # Tạo bài viết mới (Admin)
PUT    /api/articles/{id}       # Cập nhật bài viết (Admin)
DELETE /api/articles/{id}       # Xóa bài viết (Admin)
```

### Comment Management
```
GET    /api/articles/{id}/comments     # Lấy bình luận của bài viết
POST   /api/articles/{id}/comments     # Thêm bình luận mới
PUT    /api/comments/{id}              # Cập nhật bình luận
DELETE /api/comments/{id}              # Xóa bình luận
```

### Like Management
```
POST   /api/articles/{id}/like         # Like/Unlike bài viết
GET    /api/articles/{id}/likes        # Lấy số lượt like
```

### Invoice Management
```
GET    /api/invoices           # Lấy danh sách hóa đơn
GET    /api/invoices/{id}      # Lấy chi tiết hóa đơn
POST   /api/invoices           # Tạo hóa đơn mới
PUT    /api/invoices/{id}       # Cập nhật hóa đơn
```

### API Documentation
```
GET    /swagger-ui.html        # Swagger UI Interface
GET    /api-docs               # OpenAPI JSON Documentation
```

### Response Format
Tất cả API responses đều trả về JSON với format:
```json
{
  "data": {}, // Dữ liệu trả về
  "message": "Success", // Thông báo
  "status": 200 // HTTP status code
}
```

### Authentication
API sử dụng JWT Bearer Token:
```
Authorization: Bearer <your-jwt-token>
```

### Error Handling
```json
{
  "error": "Error message",
  "status": 400,
  "timestamp": "2024-01-01T00:00:00Z"
}
```

<div align="center">
  <p>Được phát triển bởi Trịnh Lê Xuân Bách</p>
  <p>Design tham khảo ở PetService</p>
  <p>Mọi vấn đề liên quan liên quan liên hệ qua facebook: https://www.facebook.com/cac.trinh.3572</p>
</div>
