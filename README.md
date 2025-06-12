# 🛠️ EventPlanner - Backend

A scalable and secure backend service for the **EventPlanner** platform – designed to support multi-role event planning with clean architecture, real-time updates, and RESTful APIs.

---

## 📋 Table of Contents
- [About the Project](#about-the-project)
- [Architecture & Features](#architecture--features)
- [Tech Stack](#tech-stack)
- [Database Design & Schema](#database-design)
- [Testing & Code Quality](#testing--code-quality)
- [Team Collaboration](#team--collaboration)
- [My Contributions](#my-contributions)

---

<a name="about-the-project"></a>
## 📖 About the Project

**EventPlanner** is a cross-platform event planning ecosystem connecting:
- 👤 **Guests** - browse events, products and services
- 🎫 **Authenticated Users** – register, manage profiles, participate in events  
- 🎤 **Event Organizers** – create and manage public or private events  
- 🛠️ **Service/Product Providers** – offer services and products for events  
- 🛡️ **Administrators** – manage the entire system

This repository contains the **Backend** codebase, developed with **Java (Spring Boot)** using a layered architecture and full JWT-based security.

See also:  
- [EventPlanner Frontend](https://github.com/Nikola034/Event-Planner-Frontend)  
- [EventPlanner Android](https://github.com/Nikola034/Event-Planner-Android) 
- [EventPlanner Selenium Tests](https://github.com/Nikola034/Event-Planner-Selenium-Tests)
---

<a name="architecture--features"></a>
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

<a name="tech-stack"></a>
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

<a name="database-design"></a>
## 🗄️ Database Design & Schema

- Utilized **PostgreSQL** for a robust relational database management system.  
- Designed a **complex, scalable schema** supporting multiple interconnected entities: users, events, event types, services, products, reservations, participations, roles, and permissions.  
- Implemented **normalized tables** with strong foreign key constraints ensuring data integrity and relational consistency.  
- Leveraged **JPA/Hibernate** for ORM, enabling easy entity relationship mapping and query optimization.  
- Carefully modeled **many-to-many** and **one-to-many** relationships to reflect real-world domain logic, facilitating complex queries and reporting.  
- Indexed frequently queried columns to optimize performance on large datasets.

---

<a name="testing--code-quality"></a>
## 🧪 Testing & Code Quality

- ✅ **Unit Testing** – JUnit  
- 🧪 **Manual API Testing** – Postman  
- 🧼 **Clean Code** – DTOs, Separation of Concerns  
- 🔍 **Code Reviews** – Pull requests & reviews for all changes  
- 📋 **Agile Workflow** – Trello board with sprints and retrospectives

---

<a name="team--collaboration"></a>
## 🤝 Team & Collaboration

- Developed collaboratively by a team of **3 members**
- Worked in agile sprints with clearly defined roles and responsibilities
- Used **Trello** for task management, sprint planning, and retrospectives
- Maintained high code quality through **pull requests**, **code reviews**, and team discussions
- Initial designs and workflows were created and shared in **Figma**

---

<a name="my-contributions"></a>
## 👨‍💻 My Contributions

- 🔧 Event module: creation, editing, deletion
- 🔐 Complete Spring Security and JWT implementation
- 🏷️ EventType module  
- 👤 Registration, login, and profile update  
- 🛍️ Partial contribution to service/product CRUD  
- 📐 Participated in early design process (Figma prototypes)
- 🧪 JUnit, Jasmin and E2E Seleniumt Tests for each part

---
