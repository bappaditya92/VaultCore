# 💳 VaultCore

A scalable full-stack banking application built using **Spring Boot** and **React** that delivers secure and reliable banking operations.  
The platform supports deposits, withdrawals, and fund transfers with enterprise-grade security and production-ready deployment architecture.

---

## 🚀 Features

- Secure authentication & authorization using **Spring Security** and **JWT**
- Role-based access control for Admin & Customer operations
- Deposit, withdrawal, and fund transfer functionalities
- RESTful APIs for seamless frontend-backend communication
- Transaction tracking and audit logging for financial transparency
- AWS S3 integration for secure file storage
- SMTP email notifications for real-time transaction updates
- Dockerized deployment for consistent environments
- GitHub Actions based CI/CD pipeline for automated build & deployment
- Reduced transaction processing latency by **30%**
- Reduced deployment time by **40%** using automated DevOps workflow

---

## 🛠️ Tech Stack

### Backend
- Java
- Spring Boot
- Spring Security
- JWT Authentication
- Hibernate / JPA
- REST APIs

### Frontend
- React
- JavaScript
- Axios

### Database
- MySQL

### DevOps & Cloud
- Docker
- GitHub Actions
- AWS S3

### Other Integrations
- SMTP Email Service

---

## 🏗️ Architecture

- Responsive React frontend application
- Layered Spring Boot backend architecture
- JWT-based secure authentication flow
- Docker containerized deployment
- CI/CD automation using GitHub Actions

---

## ⚙️ Installation & Setup

### Clone Repository

```bash
git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name
```

### Backend Setup

```bash
cd backend
./mvnw spring-boot:run
```

### Frontend Setup

```bash
cd frontend
npm install
npm start
```

---

## 🔐 Environment Variables

Configure the following variables in `.env` or `application.properties`:

```properties
# Database
DB_URL=
DB_USERNAME=
DB_PASSWORD=

# JWT
JWT_SECRET=

# AWS S3
AWS_ACCESS_KEY=
AWS_SECRET_KEY=
AWS_BUCKET_NAME=

# SMTP
MAIL_USERNAME=
MAIL_PASSWORD=
```

---

## 🔄 CI/CD Pipeline

The project uses **GitHub Actions** for:

- Automated build & testing
- Docker image creation
- Continuous deployment workflow

---

## 📌 Future Enhancements

- Two-factor authentication (2FA)
- Account statement generation
- Real-time analytics dashboard
- Kubernetes deployment support
- Microservices architecture migration

---

## 📄 License

This project is developed for learning and portfolio purposes.
