# Spring Boot Complete Application

This project is a **comprehensive Spring Boot application** demonstrating various core and advanced features of Spring Boot,
including REST API creation, database integration (H2 & MySQL), validation, logging, exception handling, profiles, testing, and actuator endpoints.

---

## 📚 Table of Contents
1. [Overview](#overview)
2. [Technologies Used](#technologies-used)
3. [Features](#features)
4. [Project Structure](#project-structure)
5. [Setup and Installation](#setup-and-installation)
6. [Usage](#usage)
7. [Testing](#testing)
8. [Profiles](#profiles)
9. [Actuator Endpoints](#actuator-endpoints)
10. [Logging](#logging)
11. [License](#license)

---

## 📌 Overview
This application demonstrates:
- Building REST APIs using Spring Boot
- CRUD operations with JPA and Hibernate
- Switching between **H2 in-memory DB** and **MySQL**
- Dependency Injection and Component creation
- Validation, Logging, and Exception Handling
- Profile-based configuration
- Actuator for monitoring
- Unit and Integration Testing

---

## 💻 Technologies Used
- **Java 21 / Java 17 / Java 8** (Compatible)
- **Spring Boot** (Core, Web, JPA, Validation, Actuator)
- **H2 Database** (In-memory)
- **MySQL** (Persistent DB)
- **Project Lombok** (Boilerplate reduction)
- **REST Client / Postman** (API Testing)
- **JUnit 5 & Mockito** (Testing)

---

## ✨ Features

### Core Spring Boot
- Dependency Injection
- Spring Initializr setup
- IDEs supported: IntelliJ IDEA, STS, VS Code
- Spring Boot starters

### API Development
- Simple REST API creation
- CRUD operations:
  - **Create**: Save data to DB
  - **Read**: Fetch data (all/by ID/by property)
  - **Update**: Modify data in DB
  - **Delete**: Remove data from DB

### Database Integration
- H2 in-memory database setup
- Switching to MySQL
- JPA & Hibernate mapping

### Additional Features
- **Hibernate Validation** for request payloads
- **Logging** using `SLF4J` and `LoggerFactory`
- **Lombok** for cleaner code
- **Exception Handling** with `@ControllerAdvice`
- **application.properties** and **application.yml** configuration
- Profile management (`dev`, `prod`, etc.)

### Monitoring
- Spring Boot Actuator
- Custom actuator endpoints
- Excluding actuator endpoints

### Testing
- Unit Testing (Service Layer)
- Repository Testing (with H2 DB)
- Controller Testing (MockMvc)

---
