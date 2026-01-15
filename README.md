# Employee Management System - Backend

A RESTful backend application built with **Java** and **Spring Boot** that provides CRUD operations for managing employee data.  

This project demonstrates a clean layered architecture, database persistence, and input validation.

---

## Features

- Create, Read, Update, Delete (CRUD) endpoints for employee records
- Exception handling for robust API responses
- Persistence using relational database (configured in application.properties)
- Layered architecture with Controller, Service, Repository, DTO, Entity, and Mapper layers

---

## Tech Stack

- **Java 17+**  
- **Spring Boot** – Web, Data JPA, Validation  
- **Maven** – Dependency management  

---

## Project Structure

```
employee-management-system-backend/
├── .mvn/
│ └── wrapper/
├── src/
│ └── main/
│ ├── java/
│ │ └── com/
│ │ └── rohitCRUD/
│ │ └── employee_management_system/
│ │ ├── controller/
│ │ ├── dto/
│ │ ├── entity/
│ │ ├── exception/
│ │ ├── mapper/
│ │ ├── repository/
│ │ └── service/
│ └── resources/
│ └── application.properties
├── .gitattributes
├── .gitignore
├── mvnw
├── mvnw.cmd
└── pom.xml
```
