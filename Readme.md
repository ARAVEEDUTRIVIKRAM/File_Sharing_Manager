# 🔐 Secure File Sharing Manager

## Problem Statement

File sharing is deceptively simple but risky. Many applications allow users to upload and download files, yet fail to handle **authentication, access control, token expiry, invalid requests, and error scenarios** correctly. This often leads to broken links, unauthorized access, and poor reliability.

This project was built to solve that problem by implementing a **secure, token-based file sharing system** where access is explicitly controlled, validated, and traceable through backend APIs.

---

## 🧠 System Overview

The Secure File Sharing Manager is a **full-stack web application** that enables authenticated users to upload, manage, and securely share files through REST APIs.

The system emphasizes:

* Authentication and authorization correctness
* Backend-driven validation and error handling
* Clear separation of frontend and backend responsibilities

---

## 🏗️ Architecture

### Frontend

* Built using **React.js** with a component-based structure
* Communicates with backend services using REST APIs
* Handles authentication state and attaches JWT tokens to protected requests
* Displays server-side validation and error messages to users

### Backend

* Implemented using **Spring Boot** following a layered architecture:

  * **Controller layer** for request handling
  * **Service layer** for business logic
  * **Repository layer** using JPA/Hibernate
* JWT-based authentication and authorization
* Centralized exception handling for consistent API responses

### Database

* **PostgreSQL** database for storing user and file metadata
* ORM handled using JPA/Hibernate

---

## 🛠️ Tech Stack

**Backend**

* Java
* Spring Boot
* REST APIs
* JWT Authentication
* JPA / Hibernate

**Frontend**

* React.js
* HTML5
* CSS3
* JavaScript

**Database**

* PostgreSQL

**Tools & Platforms**

* Git & GitHub
* Postman
* IntelliJ IDEA

**Deployment**

* Hosted on Render (free tier)

---

## 🔑 Core Features

* User registration and login using JWT-based authentication
* Secure file upload, download, deletion, and sharing
* Token-based validation for protected endpoints
* Centralized error handling and request validation
* Responsive frontend integrated with backend APIs

---

## 🔁 Application Flow

1. User registers or logs in to obtain a JWT token
2. Frontend stores the token and attaches it to subsequent API requests
3. Backend validates the token using authentication filters
4. Authorized requests are processed by service-layer logic
5. File metadata is stored in the database and files are served securely
6. Errors and invalid access attempts are handled centrally

---

## 🧪 Testing & Validation

The system was manually tested using **Postman** and browser-based workflows.

### Validated Scenarios

* Successful and failed authentication attempts
* Access to protected APIs with valid and invalid JWT tokens
* Unauthorized file access attempts
* Invalid file identifiers and malformed requests
* File upload and download validation
* Correct HTTP status codes for error scenarios

### Error Handling Strategy

* Centralized exception handler for uniform API responses
* Proper HTTP status codes for authentication, validation, and server errors
* Clear error messages returned to the frontend

---

## ⚠️ Edge Cases Considered

* Expired or invalid authentication tokens
* Accessing files without authorization
* Non-existent or deleted file references
* Concurrent file access requests
* Invalid or missing request parameters

---

## 🌐 Live Demo

🔗 [https://file-sharing-manager.onrender.com/files](https://file-sharing-manager.onrender.com/files)

---

## 📸 Screenshots

*(Screenshots are included below to demonstrate the user interface and workflows.)*

---

## 📌 Known Limitations

* Free-tier hosting causes cold-start latency
* No automated unit or integration test suite implemented
* File storage handled at application level rather than external object storage

---

## 🔮 Future Improvements

* Add automated unit and integration testing
* Integrate cloud object storage (e.g., AWS S3)
* Implement role-based access control
* Add audit logging and rate limiting
* Introduce CI/CD pipeline for automated builds and deployments

---

## 👨‍💻 Author

**Araveedu Trivikram**
GitHub: [https://github.com/ARAVEEDUTRIVIKRAM](https://github.com/ARAVEEDUTRIVIKRAM)
