# Library Management System

A full-stack **Library Management System** developed using **Java, Spring Boot, React, and MySQL**.  
The application simulates real-world library operations with a clean architecture, RESTful APIs, and an interactive user interface.

---

## Project Overview
This system provides a complete solution for managing library activities such as book records, issuing, returning, and user operations.  
It follows a layered architecture with a Spring Boot backend and a React-based frontend to ensure scalability, maintainability, and a smooth user experience.

---

## Key Features
- Book management (Add, update, delete, and view books)
- Issue and return book functionality
- User management module
- RESTful API implementation
- MySQL database integration
- Responsive and interactive frontend interface

---

## Technology Stack

### Backend
- Java
- Spring Boot
- Spring Data JPA
- Maven

### Frontend
- React.js
- JavaScript
- HTML5
- CSS3

### Database
- MySQL

---

## System Architecture
- Layered backend architecture (Controller → Service → Repository)
- REST API communication between frontend and backend
- Persistent data storage using MySQL

---

## How to Run the Project

### Step 1: Download the Project
1. Open the project repository on GitHub.
2. Click the **Code** button.
3. Select **Download ZIP**.
4. Extract the ZIP file on your system.

**OR** use Git:

```bash
git clone YOUR_GITHUB_REPOSITORY_LINK
cd library-management-system
```

---

### Step 2: Install Required Software
Make sure the following tools are installed on your system:

- Java JDK 17 or higher
- MySQL
- Node.js (LTS version)
- Maven (or use the included Maven wrapper)
- IDE (IntelliJ IDEA or VS Code)

---

### Step 3: Database Setup (MySQL)

1. Open MySQL.
2. Create a new database:

```sql
CREATE DATABASE library_db;
```

---

### Step 4: Run the Backend (Spring Boot)

1. Navigate to the backend folder:

```bash
cd backend
```

2. Open the file:

```
backend/src/main/resources/application.properties
```

3. Configure your MySQL credentials:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/library_db
spring.datasource.username=root
spring.datasource.password=YOUR_PASSWORD

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.jpa.database-platform=org.hibernate.dialect.MySQL8Dialect
server.port=8080
```

4. Start the backend server:

```bash
mvnw spring-boot:run
```

Or run the main class from your IDE.

Backend will start at:
```
http://localhost:8080
```

---

### Step 5: Run the Frontend (React)

1. Open a new terminal.
2. Navigate to the frontend folder:

```bash
cd frontend
```

3. Install dependencies:

```bash
npm install
```

4. Start the React app:

```bash
npm start
```

Frontend will start at:
```
http://localhost:3000
```

---

## Final Steps
1. Ensure MySQL database is running.
2. Start the backend server.
3. Start the frontend application.
4. Open your browser and go to:

```
http://localhost:3000
```

---

## Author
**Nakul Sonkar**
