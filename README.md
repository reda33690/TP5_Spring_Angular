# Student Payment Management System 🎓💸

## Overview 🌟

This application is designed to manage the payment processes for students, allowing for tracking and management of multiple payments per student. It features a comprehensive backend developed with Spring Boot and a dynamic frontend using Angular with Angular Material.

## Objectives 🎯

### Part 1: Backend Development with Spring 🍃
- **Entities and Repositories**: Develop JPA entities and repositories for students and payments.
- **Random Data Generation**: Generate sample data for students and their payments.
- **RESTful API**: Implement RESTful services to manage and query payments and student details.
- **Advanced Features**:
  - Filter payments by type, status, student, and field of study.
  - Perform CRUD operations on payments and students.
  - Upload and retrieve payment receipts as PDF files.
- **Testing**: Use Postman and SWAGGER UI for API testing and documentation.
- **Refactoring**: Enhance the backend with service layers, DTOs, and Mappers.

### Part 2: Frontend Development with Angular 🖥️
- **Angular Project Setup**: Initialize an Angular project with Angular Material.
- **UI Components**: Create a dashboard with Toolbar, Side Menu, and various functional components.
- **Authentication System**: Implement simple authentication and route guards for app security.
- **Functional Components**:
  - Paginated display of payments.
  - Search and display of student information.
  - Student dashboard showcasing detailed info and payments.
  - Add new payments with PDF receipt uploads.
  - Detailed view and status updates of payments.

### Part 3: Integration and Deployment 🚀
- **Full System Integration**: Ensure the frontend and backend work seamlessly together.
- **Deployment**: Prepare the application for deployment and real-world testing.

## Technologies Used 🛠️

- **Backend**: Spring Boot, Spring Data JPA, Hibernate, Swagger UI
- **Frontend**: Angular, Angular Material, Angular CLI
- **Database**: H2 Database for development; plan for migration to a more scalable option as needed.

## Getting Started 🏁

### Prerequisites
- Java 11 or newer
- Node.js and npm
- Angular CLI

### Running the Application
1. **Backend**:
   ```
   cd backend
   mvn spring-boot:run
   ```
2. **Frontend**:
   ```
   cd frontend-angular
   ng serve
   ```
   Access the application at `http://localhost:4200`.
