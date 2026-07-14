# 🔐 Secure File Sharing Manager

A production-ready Full Stack Web Application that enables authenticated users to securely upload, manage, download, and share files using JWT-based authentication and REST APIs.

Built using Spring Boot, React, PostgreSQL, Spring Security, JWT Authentication, Docker, and RESTful APIs.

---

## 🚀 Live Demo

Live URL:
https://file-sharing-manager.onrender.com/files

GitHub Repository:
https://github.com/ARAVEEDUTRIVIKRAM/File_Sharing_Manager

---

## Features

✔ JWT Authentication

✔ Secure File Upload

✔ File Download

✔ File Sharing

✔ File Deletion

✔ Protected REST APIs

✔ Spring Security

✔ Centralized Exception Handling

✔ PostgreSQL Integration

✔ Responsive React UI

✔ Docker Support

---

## Tech Stack

### Backend

- Java
- Spring Boot
- Spring Security
- JWT Authentication
- Spring Data JPA
- Hibernate
- PostgreSQL
- Maven

### Frontend

- React
- HTML
- CSS
- JavaScript

### DevOps

- Docker
- Render

### Tools

- Git
- GitHub
- IntelliJ IDEA
- Postman

---

## Project Architecture

```text
React Frontend
        │
        ▼
REST APIs
        │
        ▼
Spring Boot Backend
        │
        ▼
Spring Security
        │
        ▼
JWT Authentication
        │
        ▼
Service Layer
        │
        ▼
Repository Layer
        │
        ▼
PostgreSQL Database

```

# Folder Structure

```text
File_Sharing_Manager
│
├── src
│   └── main
│       ├── java
│       │   └── com
│       │       └── company
│       │           └── fileSharingManagement
│       │               ├── configuration
│       │               ├── controller
│       │               ├── entity
│       │               ├── exception
│       │               ├── model
│       │               ├── repository
│       │               ├── service
│       │               └── FileSharingManagerApplication
│       │
│       └── resources
│           └── application.properties
│
├── Dockerfile
├── pom.xml
└── README.md
```


# Application Flow

User Login

↓

JWT Token Generated

↓

Frontend Stores Token

↓

Protected REST API Call

↓

Spring Security Validation

↓

Business Logic

↓

Database Operations

↓

Response Returned
---


# Security

- JWT Authentication
- Spring Security
- Stateless Authentication
- Protected REST APIs
- Authorization Filters
- Password Encryption
- Centralized Exception Handling


  # REST APIs

| Module | Sample Endpoints |
|---------|------------------|
| Authentication | `/login` |
| Files | `/upload` |
| Files | `/download/{id}` |
| Files | `/delete/{id}` |
| Files | `/share/{id}` |

  
## 📸 Screenshots

*(Screenshots are included below to demonstrate the user interface and workflows.)*

<img width="1920" height="971" alt="Screenshot (2386)" src="https://github.com/user-attachments/assets/442f762d-c2d2-46ec-a3c5-380d5d68154e" />

<img width="1920" height="969" alt="Screenshot (2387)" src="https://github.com/user-attachments/assets/a3dde8d6-a87d-4fd3-9829-27c0de5555aa" />

<img width="1920" height="973" alt="Screenshot (2388)" src="https://github.com/user-attachments/assets/ff798cb3-bffa-4a75-8725-ad8f793d1385" />

---


# Installation

git clone https://github.com/ARAVEEDUTRIVIKRAM/File_Sharing_Manager.git

cd File_Sharing_Manager

mvn clean install

mvn spring-boot:run


# Testing

Validated using
- Postman
- Browser Testing
- JWT Authentication
- Unauthorized Requests
- File Upload
- File Download
- Exception Handling


# Known Limitations

- Free-tier hosting cold starts
- No cloud object storage
- Manual testing only


# Future Enhancements

- AWS S3 Integration
- Role-Based Access Control
- Email Sharing
- Audit Logs
- CI/CD Pipeline
- Unit & Integration Testing


# Author 

**Araveedu Trivikram**
LinkedIn: https://www.linkedin.com/in/araveedu-trivikram-88b2462bb/
