# 🏦 Secure Digital Banking Management System

A full-stack digital banking web application built using **Java Spring Boot**, **JSP**, and **MySQL**, designed to provide secure banking operations, intelligent customer assistance, and real-time financial management features.

The application follows a layered MVC architecture and integrates modern services like AI chatbot support, SMS notifications, email automation, and PDF statement generation.

---

## 🚀 Tech Stack

| Layer | Technology |
|-------|------------|
| Backend | Java 17, Spring Boot 3.2.4, Spring JDBC |
| Frontend | JSP, HTML5, CSS3, Bootstrap 5, JavaScript |
| Database | MySQL |
| Authentication | BCrypt Password Hashing, Session Management |
| SMS Service | Twilio API |
| Email Service | Spring Mail (Gmail SMTP) |
| AI Chatbot | OpenRouter API (Nemotron) |
| PDF Generation | iTextPDF |
| Payment Gateway | Razorpay |
| Build Tool | Maven |
| Containerization | Docker |

---

## 🧩 Architecture Highlights

- MVC architecture using Spring Boot + JSP
- Layered backend structure (Controller → Service → DAO)
- Secure session-based authentication system
- REST API integration with OpenRouter AI
- Automated email and SMS notification workflows
- Modular banking transaction management
- Responsive and user-friendly dashboard interface

---

## ✨ Key Features

### 👤 Authentication & Security
- User Registration and Login
- BCrypt password encryption
- OTP verification using Twilio SMS
- Secure session handling

### 💳 Banking Operations
- Account creation and management
- Deposit and withdrawal operations
- Fund transfer system
- Beneficiary management
- Transaction history and mini statements

### 📊 Customer Dashboard
- Account overview
- Balance inquiry
- Payment history
- Profile management

### 🏦 Loan Management
- Loan application system
- EMI schedule tracking
- Automated EMI reminder emails
- Loan dashboard management

### 🤖 AI Chatbot Assistant
- Intelligent banking chatbot
- Customer query assistance
- OpenRouter AI integration

### 🛠️ Admin Panel
- User management
- Active user monitoring
- FAQ management
- Customer account administration

### 📄 Additional Features
- PDF statement export
- Email notifications
- Responsive UI design
- Docker support

---

## 📂 Project Structure

```bash
src/
├── main/
│   ├── java/
│   │   └── com/example/online_banking_system
│   ├── resources/
│   └── webapp/
│       ├── WEB-INF/jsp/
│       ├── css/
│       ├── js/
│       └── images/
```

---

## 🛠️ Setup Instructions

### Prerequisites

- Java 17+
- MySQL 8+
- Maven 3.6+

### Installation

```bash
# Clone repository
git clone https://github.com/soubhagya-behera/secure_digital_banking_management_system.git

# Navigate to project
cd secure_digital_banking_management_system

# Create MySQL database
mysql -u root -p -e "CREATE DATABASE digital_banking;"

# Configure database credentials
# Update src/main/resources/application.properties

# Run the application
./mvnw spring-boot:run
```

---

## 🌐 Application Access

Open the application in your browser:

```bash
http://localhost:8082
```

---

## 🔐 Security Features

- BCrypt password hashing
- Session-based authentication
- Secure database credential management
- OTP verification via SMS
- Protected banking operations

---

## 📸 Screenshots

### Login Page
(Add screenshot here)

### Customer Dashboard
(Add screenshot here)

### Loan Management
(Add screenshot here)

### Admin Panel
(Add screenshot here)

---

## 📈 Future Enhancements

- JWT Authentication
- RESTful API conversion
- React.js frontend integration
- Cloud deployment (AWS)
- Online payment analytics
- Role-based authorization

---

## 👨‍💻 Author

### Soubhagya Behera

MCA Student | Java Full Stack Developer

- GitHub: https://github.com/soubhagya-behera
- LinkedIn: Add your LinkedIn profile here

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.
