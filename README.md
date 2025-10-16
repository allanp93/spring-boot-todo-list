# Spring Boot To-Do List API

![Java](https://img.shields.io/badge/Java-17-blue)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.3.x-brightgreen)
![Security](https://img.shields.io/badge/Security-JWT-purple)
![Status](https://img.shields.io/badge/Status-Work_In_Progress-yellow)
![Build Status](https://img.shields.io/github/actions/workflow/status/seu-usuario/seu-repo/main.yml)
![Last Commit](https://img.shields.io/github/last-commit/seu-usuario/seu-repo)

## 🎯 About The Project

This project is a complete RESTful API for task management (To-Do List), developed as a personal study project in Java and Spring Boot. The application allows users to register, authenticate, and manage their own task lists securely.

The main goal was to apply core backend development concepts, from creating endpoints and validating data to implementing a robust security system with JWT tokens and deploying the application in a production-like environment.

---

## ✨ Key Features

-   **User Management:** User registration and authentication.
-   **Secure Authentication:** Uses JSON Web Tokens (JWT) with Spring Security to protect endpoints.
-   **CRUD Operations for Tasks:**
    -   Create, list, update, and delete tasks.
    -   Users can only view and manage their own tasks.
-   **Data Validation:** Input data is validated to ensure information integrity (e.g., required fields, character limits).
-   **Exception Handling:** Clear and standardized error responses for the client.

---

## 🛠️ Tech Stack

-   **Language:** Java 17
-   **Framework:** Spring Boot 3
-   **Spring Modules:** Spring Web, Spring Security, Spring Data JPA
-   **Database:** H2 Database and PostgreSQL
-   **Authentication:** JSON Web Token (JWT)
-   **Build Tool:** Maven
-   **Deployment:** Deployment link available soon.

---

## 🚀 How to Run

```bash
# 1. Clone the repository
git clone [https://github.com/allanp93/spring-boot-todo-list.git](https://github.com/allanp93/spring-boot-todo-api.git)

# 2. Navigate to the project directory
cd spring-boot-todo-list

# 3. Run the project using Maven
./mvnw spring-boot:run
