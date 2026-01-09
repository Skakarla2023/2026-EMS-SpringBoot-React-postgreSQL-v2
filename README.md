<h1 align="center"><b>2026-EMS-SpringBoot-React-postgreSQL-v2</b></h1>

<p align="center">A backend REST API built using Java and SpringBoot to manage employees, departments and related operations.</p>

## 🛠️ Tech Stack
- Java
- Spring Boot
- Spring Data JPA
- Hibernate
- REST APIs
- PostgreSQL 
- Maven
- Lombok
- Swagger
- Validation

## 🍁Project Overview 

EMS-v2 is a backend application designed to manage employee-related data such as employee details, roles, departments.

This project focuses on building clean REST APIs, proper layered architecture, and database integration using SpringBoot.

## 🚀 Features
- Create, update, delete, and fetch employee details
- RESTful API design
- Layered architecture (Controller, Service, Repository)
- Database integration using JPA & Hibernate
- Exception handling and validation

## 📂 Project Structure

```
ems-v2
│
├── src
│   ├── main
│   │   ├── java
│   │   │   └── com.example.ems
│   │   │       ├── config
│   │   │       │   └── OpenApiConfig.java
│   │   │       │ 
│   │   │       ├── controller
│   │   │       │   └── EmployeeController.java
│   │   │       │   └── DepartmentController.java
│   │   │       │ 
│   │   │       ├── dto 
│   │   │       │   └── DepartmentRequestDTO.java
│   │   │       │   └── DepartmentResponseDTO.java
│   │   │       │   └── DepartmentSummaryDTO.java
│   │   │       │   └── EmployeeRequestDTO.java
│   │   │       │   └── EmployeeResponseDTO.java
│   │   │       │   └── EmployeeSummaryDTO.java
│   │   │       │
│   │   │       ├── entity
│   │   │       │   └── Employee.java
│   │   │       │   └── Department.java
│   │   │       │
│   │   │       ├── exception
│   │   │       │   └── GlobalExceptionHandler.java
│   │   │       │   └── ResourceNotFoundException.java
│   │   │       │   └── ErrorResponse.java
│   │   │       │   └── DuplicateResourceException.java
│   │   │       │
│   │   │       ├── repository
│   │   │       │   └── EmployeeRepository.java
│   │   │       │   └── DepartmentRepository.java
│   │   │       │
│   │   │       ├── service
│   │   │       │   └── EmployeeService.java
│   │   │       │   └── DepartmentService.java
│   │   │       │   └── impl
│   │   │       │   	└── EmployeeServiceImpl.java
│   │   │       │   	└── DepartmentServiceImpl.java
│   │   │       │   
│   │   │       ├── util        
│   │   │       │   └── MapperUtil.java
│   │   │       │   └── PageResponse.java
│   │   │       │
│   │   │       └── Application.java
│   │   │
│   │   └── resources
│   │       └── application.yml      
│   │
│   └── test
│       └── java
│           └── com.example.ems
│               └── EmsV2ApplicationTests.java
│
├── pom.xml
├── README.md
└── .gitignore


```


## 👩‍💻 Author
Satwika Kakarla  
Aspiring Backend / Full Stack Developer
