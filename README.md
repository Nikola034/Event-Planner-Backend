# 🛠️ EventPlanner - Backend

A scalable and secure backend service for the **EventPlanner** platform – designed to support multi-role event planning with clean architecture, real-time updates, and RESTful APIs.

---

## 📋 Table of Contents
- [📖 About the Project](#about-the-project)
- [Architecture & Features](#architecture--features)
- [Tech Stack](#tech-stack)
- [Testing & Code Quality](#testing--code-quality)
- [My Contributions](#my-contributions)

---

## 📖 About the Project

**EventPlanner** is a cross-platform event planning ecosystem connecting:
- 🎫 **Authenticated Users** – register, manage profiles, participate in events  
- 🎤 **Event Organizers** – create and manage public or private events  
- 🛠️ **Service/Product Providers** – offer services and products for events  
- 🛡️ **Administrators** – manage the entire system

This repository contains the **Backend** codebase, developed with **Java (Spring Boot)** using a layered architecture and full JWT-based security.

---

## 🧱 Architecture & Features

### 🔐 Authentication & Authorization
- Secure login using **JWT tokens**
- Role-based access control via **Spring Security**
- Middleware to protect sensitive endpoints

### 📦 Event & User Management
- Full CRUD for **events**, **event types**, **services**, **products**, **product/service-reservations**, **event participations** and **user profiles**
- DTO pattern for clean and safe data transfer
- Modular services: `Repository → Service → Controller`

### 🔔 Communication
- Email service for account-related notifications
- WebSocket support for real-time event updates and messages (chat)

### 🔗 API
- RESTful API design
- Fully tested using Postman collections

---

## 🧰 Tech Stack

| Category     | Technologies Used                          |
|--------------|---------------------------------------------|
| **Language** | Java 17                                     |
| **Framework**| Spring Boot, Spring Security                |
| **Auth**     | JWT, Role-based Access Control              |
| **Database** | PostgreSQL + JPA (Hibernate)                |
| **Messaging**| WebSockets                                  |
| **Tools**    | Maven, Postman, Mail Service (SMTP)         |

---

## 🧪 Testing & Code Quality

- ✅ **Unit Testing** – JUnit  
- 🧪 **Manual API Testing** – Postman  
- 🧼 **Clean Code** – DTOs, Separation of Concerns  
- 🔍 **Code Reviews** – Pull requests & reviews for all changes  
- 📋 **Agile Workflow** – Trello board with sprints and retrospectives

---

## 👨‍💻 My Contributions

- 🔧 Event module: creation, editing, deletion  
- 🏷️ EventType module  
- 👤 Registration, login, and profile update  
- 🛍️ Partial contribution to service/product CRUD  
- 📐 Participated in early design process (Figma prototypes)
- 🧪 JUnit, Jasmin and E2E Seleniumt Tests for each part

---
