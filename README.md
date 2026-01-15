# Employee Management System - Backend

A RESTful backend application built with **Java** and **Spring Boot** that provides CRUD operations for managing employee data.  

This project demonstrates a clean layered architecture, database persistence, and input validation.

---

## Features

- Create, Read, Update, Delete (CRUD) endpoints for employee records
- Data validation to ensure input integrity
- Exception handling for robust API responses
- Persistence using PostgreSQL (or configured database)
- Layered architecture with Controller, Service, and Repository layers

---

## Tech Stack

- **Java 17+**  
- **Spring Boot** – Web, Data JPA, Validation  
- **PostgreSQL** (or any relational DB configured)  
- **Maven** – Dependency management  
- **JUnit & Mockito** – Testing (if tests included)  

---

## Project Structure

```
src/
├── main/
│ ├── java/com/example/ems/
│ │ ├── controller/ # REST controllers handling HTTP requests
│ │ ├── service/ # Business logic
│ │ ├── repository/ # Data access layer (JPA Repositories)
│ │ ├── model/ # Entity and DTO classes
│ │ └── exception/ # Custom exceptions and handlers
│ └── resources/
│ ├── application.properties # Configurations
│ └── data.sql (optional) # Sample DB data
└── test/ (optional)
```

