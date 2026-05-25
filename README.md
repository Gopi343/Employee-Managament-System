# 👨‍💼 Employee Management System

A full-stack Employee Management System built using **React (Vite)** for the frontend and **Spring Boot + MySQL** for the backend.

This application enables organizations to manage employee records efficiently through modern UI and REST APIs.

![Java](https://img.shields.io/badge/Java-17-orange)
![SpringBoot](https://img.shields.io/badge/SpringBoot-Backend-green)
![React](https://img.shields.io/badge/React-Frontend-blue)
![Vite](https://img.shields.io/badge/Vite-Build-purple)
![MySQL](https://img.shields.io/badge/MySQL-Database-blue)
![Bootstrap](https://img.shields.io/badge/Bootstrap-UI-violet)

---

# 📌 Overview

Employee Management System provides a centralized platform to manage employee information with CRUD operations.

Main capabilities:

- Add Employee
- Update Employee
- Delete Employee
- View Employee Details
- REST API Integration
- Responsive UI

---

# 🏗 System Architecture

```text
User
 │
 ▼
React + Vite UI
 │
 ▼
Spring Boot REST APIs
 │
 ▼
Service Layer
 │
 ▼
Repository Layer
 │
 ▼
MySQL Database
```

---

# ⚙ Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | React, Vite |
| Backend | Java, Spring Boot |
| Database | MySQL |
| Styling | Bootstrap |
| API | REST |

---

# 📂 Project Structure

```text
employee-management-system

frontend
├── src
├── components
├── pages
├── services

backend
├── controller
├── service
├── repository
├── entity
├── config
```

---

# 🔥 Features

## Employee Module
- Add employee
- Edit employee
- Delete employee
- Employee listing

## Backend
- REST APIs
- Database integration
- Validation

## UI
- Responsive layout
- Easy navigation

---

# 🚀 Installation

## Clone Repository

```bash
git clone <YOUR_REPO_URL>
```

Move into folder

```bash
cd Employee-Management-Sys
```

---

## Backend Setup

Configure database:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/employee_db
spring.datasource.username=root
spring.datasource.password=your_password
```

Run:

```bash
mvn clean install
mvn spring-boot:run
```

Backend:

```text
http://localhost:8080
```

---

## Frontend Setup

Move:

```bash
cd frontend
```

Install:

```bash
npm install
```

Run:

```bash
npm run dev
```

Frontend:

```text
http://localhost:5173
```

---

# 📡 API Endpoints

## Employee APIs

```http
GET /employees
```

```http
POST /employees
```

```http
PUT /employees/{id}
```

```http
DELETE /employees/{id}
```

---

# 🧪 Workflow

Create Employee  
↓  
Store Data  
↓  
Display Employees  
↓  
Update/Delete  

---

# 📸 Screenshots

Create folder:

```text
screenshots
```

Add:

```text
screenshots/dashboard.png
screenshots/add-employee.png
screenshots/list.png
```

Embed:

```md
![Dashboard](screenshots/dashboard.png)

![Add Employee](screenshots/add-employee.png)

![List](screenshots/list.png)
```

---

# 📈 Future Enhancements

- JWT Authentication
- Search & Filters
- Role-based Access
- Docker Deployment
- Jenkins CI/CD

---

# 👨‍💻 Author

Gopi Jada

GitHub:
https://github.com/Gopi343
