# 🧑‍💼 Job Portal – Microservices Architecture

A full-stack job portal application built using **Java Spring Boot microservices**, **React.js**, **PostgreSQL**, and **Apache Kafka**.

---

## 🏗️ System Architecture Overview

| Layer              | Technology Stack                           |
|--------------------|--------------------------------------------|
| **Frontend**       | React.js                |
| **Backend**        | Java Spring Boot Microservices             |
| **Database**       | PostgreSQL                                 |
| **Message Broker** | Apache Kafka                               |
| **API Gateway**    | Spring Cloud Gateway                       |
| **Service Discovery** | Eureka                                  |
| **Authentication** | JWT + Spring Security                      |
| **Containerization** | Docker + Docker Compose (Optional)       |
| **Deployment**     | Kubernetes (Optional)                      |

---

## 🧩 Microservices

| Service Name          | Responsibilities                        |
|------------------------|------------------------------------------|
| **User-Service**       | User registration, login, profile        |
| **Job-Service**        | Job posting, job updates                 |
| **Application-Service**| Job applications by users               |
| **Notification-Service**| Email/SMS notifications                |
| **Search-Service**     | Search/filter jobs                      |
| **API Gateway**        | Unified entry point for frontend        |
| **Kafka Broker**       | Asynchronous communication               |

---

## 🔗 REST API Contracts

### 🧑 User-Service
- `POST /api/users/register` → Register a new user  
- `POST /api/users/login` → Authenticate and login  
- `GET /api/users/{id}` → Get user profile by ID  

---

### 💼 Job-Service
- `POST /api/jobs` → Create a new job  
- `GET /api/jobs` → List all jobs  
- `GET /api/jobs/{id}` → Get job details by ID  
- `GET /api/jobs/user/{userId}` → Get jobs posted by a specific user  

---

### 📄 Application-Service
- `POST /api/applications` → Apply to a job  
- `GET /api/applications/user/{userId}` → Get applications submitted by a user  
- `GET /api/applications/job/{jobId}` → Get applications for a specific job  

---

## 🚀 Getting Started

> Setup instructions, running locally with Docker, and development steps will be added as the project evolves.

---

## 🛠️ Tech Stack

- Spring Boot
- Spring Cloud
- React.js
- PostgreSQL
- Kafka
- Eureka
- JWT + Spring Security
- Docker & Docker Compose

