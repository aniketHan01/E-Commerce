# E-Commerce
A production-ready E-Commerce REST API built using Spring Boot 3.x, Spring Data JPA, and Spring Security. Features secure authentication, clean architecture, and enterprise best practices.


# E-Commerce REST API

A production-ready, enterprise-grade backend service for an E-Commerce platform built using the Spring Boot ecosystem. This project focuses on high performance, clean architecture, secure authentication, and robust data management.

---

## 🚀 Key Features

* **Secure Authentication:** JWT (JSON Web Tokens) with Spring Security and role-based access control (Admin/Customer).
* **Product Catalog:** Advanced filtering, pagination, and sorting for products and categories.
* **Shopping Cart & Orders:** State management for user carts, secure checkout flows, and order history tracking.
* **Database Management:** Clean relational data modeling using Spring Data JPA (Hibernate) with connection pooling.
* **Robust Error Handling:** Global exception handling returning structured, client-friendly JSON error responses.

---

## 🛠️ Tech Stack & Tools

* **Backend Framework:** Java 17+ & Spring Boot 3.x
* **Data Access:** Spring Data JPA, Hibernate
* **Database:** PostgreSQL / MySQL (Production), H2 (Development/Testing)
* **Security:** Spring Security, JWT
* **Build Tool:** Maven / Gradle

---

## 📂 Architecture Overview

The project follows a clean, layered architecture to ensure separation of concerns and maintainability:
* **Controller Layer:** Exposes REST endpoints and handles HTTP request validation.
* **Service Layer:** Houses core business logic, transactional boundaries, and domain rules.
* **Repository Layer:** Manages direct database communication via JPA interfaces.
* **DTO (Data Transfer Object) Pattern:** Decouples internal database entities from API request/response payloads.

---

## ⚙️ Local Setup & Running instructions

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/aniketHan01/E-Commerce.git](https://github.com/aniketHan01/E-Commerce.git)
