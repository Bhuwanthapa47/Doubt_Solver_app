# 🚀 Doubt Solver App

An intelligent, modern platform connecting **students and mentors** for instant doubt resolution.  
Built with **Spring Boot**, **Thymeleaf**, and **MySQL**, the app offers a beautiful UI, secure role-based access, and **AI-powered answers using Gemini API**.

---

## ✨ Features

### 🌐 Modern UI
- Responsive **Home** and **About** pages
- Clean design with modern CSS & SVG illustrations
- User-friendly dashboards

### 🔐 Authentication & Roles
- Secure **Login & Registration**
- Role-based access:
    - **Students**
    - **Mentors**

### ❓ Doubt Management
- Students can:
    - Post doubts
    - Edit and track their doubts
- Mentors can:
    - Answer doubts
    - Edit and manage responses

### 🤖 AI Integration
- Instant doubt resolution using **Gemini AI API**

### 👤 Profile Management
- Update personal information
- View user activity

---

## 🛠️ Tech Stack

### Backend
- Spring Boot 3
- Java 17
- Spring Security
- Spring Data JPA

### Frontend
- Thymeleaf
- HTML5
- CSS3

### Database
- MySQL

### AI
- Gemini API

### Tools & Deployment
- Maven
- Docker
- Railway

---

## ⚡ Quick Start

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/doubt-solver-app.git
cd doubt-solver-app

2️⃣ Configure Database

Edit src/main/resources/application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/doubt_app?createDatabaseIfNotExist=true&useSSL=false&allowPublicKeyRetrieval=true&serverTimezone=UTC
spring.datasource.username=root
spring.datasource.password=yourpassword

server.port=8081

3️⃣ Build & Run
▶ Using Maven

./mvnw spring-boot:run

Windows:
mvnw.cmd spring-boot:run

🐳 Using Docker
docker build -t doubt-solver-app .
docker run -p 8081:8081 doubt-solver-app

4️⃣ Access the Application

Home: http://localhost:8081/
About: http://localhost:8081/about
Login / Register: Available via navigation bar

🧑‍💻 Project Structure

src/
 └── main/
     ├── java/com/doubtapp/backend/
     │   ├── controller/     # MVC Controllers
     │   ├── model/          # JPA Entities
     │   ├── repository/     # Spring Data Repositories
     │   └── service/        # Business Logic & AI Integration
     └── resources/
         ├── templates/      # Thymeleaf Templates
         ├── static/         # CSS, JS, Images
         └── application.properties

🙋‍♂️ Meet the Developer

Bhuwan Thapa
Made with ❤️ for learning, growth, and helping students resolve doubts smarter.

📄 License
This project is created for educational purposes only.