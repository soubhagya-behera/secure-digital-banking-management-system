# 🏦 Secure Digital Banking Management System

A full-stack digital banking web application built using **Java Spring Boot**, **JSP**, and **MySQL**, designed to provide secure banking operations, intelligent customer assistance, and real-time financial management features.

The system follows a layered MVC architecture and integrates modern technologies like AI chatbot support, Razorpay payment gateway, fraud detection, biometric security, OTP verification, and automated EMI reminder services.

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
| Security | HMAC-SHA256, OTP Verification, Fraud Detection |

---

## 🧩 Architecture Highlights

- MVC architecture using Spring Boot + JSP
- Layered backend structure (Controller → Service → DAO)
- Secure session-based authentication system
- REST API integration with OpenRouter AI
- Automated email and SMS notification workflows
- Fraud detection and transaction monitoring
- Razorpay payment signature verification using HMAC-SHA256
- Responsive and user-friendly dashboard interface

---

## ✨ Key Features

### 👤 Authentication & Security
- User Registration and Login
- BCrypt password encryption
- OTP verification using Twilio SMS
- Session-based authentication
- Password reset via OTP email verification

### 🏦 Banking Operations
- Account creation with admin approval
- Deposit and withdrawal operations
- OTP-secured fund transfers
- Beneficiary management system
- Mini statement and transaction history
- PDF statement download using iTextPDF

### 💳 Razorpay Payment Integration
- Live Razorpay payment gateway integration
- Secure HMAC-SHA256 payment signature verification
- Real-time payment processing

### 🏷️ Loan Management
- Loan application system
- EMI calculation and tracking
- Automated EMI reminder emails using Spring Scheduler
- Loan approval management

### 🤖 AI Chatbot Assistant
- AI-powered banking chatbot using OpenRouter API
- Rule-based customer query assistance
- 24/7 banking support simulation

### 🛡️ Advanced Security Features
- Fraud Detection Engine
- Auto-flagging transactions above ₹50,000
- Rate limiting for suspicious activities
- Admin fraud monitoring dashboard
- Hidden Balance Vault with secure PIN protection
- WebAuthn biometric fingerprint authentication

### 🛠️ Admin Portal
- Customer account approval system
- User management dashboard
- Block/Unblock accounts
- FAQ management
- Active user monitoring
- Fraud alert review system

### 📊 Dashboard & Analytics
- Customer dashboard with account overview
- Real-time transaction tracking
- Payment history monitoring
- Responsive UI design

### 📄 Additional Features
- Docker support
- Email notifications
- SMS integration
- MVC architecture
- JDBC-based database operations

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
- OTP verification via SMS
- Fraud detection and suspicious activity monitoring
- HMAC-SHA256 payment signature verification
- Secure database credential management
- Biometric authentication support
- Protected banking operations

---

## 📸 Screenshots
### Project Opening Page UI
<img width="1897" height="1029" alt="OpeningPageUI" src="https://github.com/user-attachments/assets/03725970-5421-4990-b0b8-2b42efbe4ff9" />


### Login Page
<img width="1917" height="1033" alt="LoginPage" src="https://github.com/user-attachments/assets/4245e630-c841-48d4-952e-fda66bc23e38" />


### Customer Dashboard
<img width="1898" height="1027" alt="CustomerDashboard" src="https://github.com/user-attachments/assets/74daee37-a35e-4ed4-b13b-0ffe0dbe5ae4" />


### Loan Management
<img width="1898" height="1030" alt="LoanDashboard" src="https://github.com/user-attachments/assets/ea44f028-d72a-4435-a5a4-66b4f15e3430" />


### Admin Panel
<img width="1901" height="1030" alt="AdminDashboard" src="https://github.com/user-attachments/assets/22610aca-9e72-47d3-b5c6-e964fc94aaed" />


### Razorpay Payment Integration
<img width="1901" height="1031" alt="RazorPay_PaymentGataeway" src="https://github.com/user-attachments/assets/305f037b-ba0f-4153-8ace-5eca33f00603" />


### Fraud Detection Dashboard
<img width="1903" height="1032" alt="FraudAlert" src="https://github.com/user-attachments/assets/107e7c67-cd96-4e96-a941-e44ee431cac3" />


### Hidden Balance Vault
<img width="1916" height="1024" alt="HiddenBalanceVault" src="https://github.com/user-attachments/assets/fd6d3441-cd25-4e1a-9980-09c0beaa08b3" />


### Balance Check Section
<img width="1913" height="1029" alt="CheckBalanceSection" src="https://github.com/user-attachments/assets/8b5189a1-6e43-4cb5-b054-dd91333e92e0" />

---

## 📈 Future Enhancements

- JWT Authentication
- RESTful API conversion
- React.js frontend integration
- Cloud deployment (AWS)
- AI-based fraud analytics using Machine Learning
- UPI and Net Banking integration
- Mobile application support
- Microservices architecture migration

---

## 👨‍💻 Author

### Soubhagya Behera

MCA Student | Java Full Stack Developer

- GitHub: https://github.com/soubhagya-behera
- LinkedIn: https://www.linkedin.com/in/soubhagyakumar-java

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.
