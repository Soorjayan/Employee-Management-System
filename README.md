# 🏢 SyntechHub – Employee Management System

A modern, full-stack **Employee Management System (EMS)** developed as **SyntechHub Project 3**.

The system provides an administrative platform for managing employees, departments, employee profiles, and administrative settings. It includes a responsive React frontend, RESTful Node.js/Express backend, and MongoDB database integration.

---

## 📌 Project Overview

The **Employee Management System** is designed to simplify employee-related administrative tasks through a centralized web application.

Administrators can:

- Manage employee records
- Add new employees
- Edit employee information
- Delete employees
- View detailed employee profiles
- Search employees
- Filter employees by department and status
- Sort employee records
- Navigate employee records using pagination
- View employees by department
- Manage administrator profile information
- Change administrator password
- Upload employee profile images
- Switch between Light and Dark mode
- Monitor employee statistics through a dashboard

The project follows a full-stack architecture with a separate frontend and backend.

---

# 🎯 Project Objectives

The main objectives of this project are:

1. To develop a centralized employee management platform.
2. To implement complete CRUD operations for employees.
3. To provide an intuitive and responsive user interface.
4. To implement RESTful APIs using Node.js and Express.js.
5. To integrate MongoDB using Mongoose.
6. To implement employee search, filtering, sorting, and pagination.
7. To provide an administrator dashboard with employee statistics.
8. To provide department-based employee management.
9. To implement administrator profile and password management.
10. To practice modern full-stack web development technologies.

---

# ✨ Features

## 🔐 Authentication

- Admin Login
- Admin Sign Up
- Show/Hide Password
- Logout
- Persistent admin session using browser storage
- Login validation
- Authentication-related UI feedback

> **Note:** The current frontend authentication is implemented using browser `localStorage`. For a production deployment, authentication should be moved to a secure backend authentication system using hashed passwords, JWT/session management, and HTTP-only cookies.

---

# 📊 Dashboard

The dashboard provides an overview of the employee management system.

### Dashboard Statistics

- 👥 Total Employees
- 🟢 Active Employees
- 🔴 Inactive Employees
- 🏢 Total Departments

The dashboard is designed to provide administrators with a quick overview of the current workforce.

---

# 👨‍💼 Employee Management

The system provides complete employee CRUD functionality.

### Create Employee

Administrators can add employees with information such as:

- Full Name
- Email
- Phone Number
- Role
- Department
- Salary
- Joining Date
- Employment Status
- Profile Image

### Read Employee

Administrators can:

- View all employees
- Search employees
- Filter employees
- Sort employees
- View employee details
- View employees by department

### Update Employee

Administrators can edit employee information including:

- Name
- Email
- Phone
- Role
- Department
- Salary
- Joining Date
- Status
- Profile Image

### Delete Employee

Administrators can delete employee records from the employee details page.

---

# 👤 Employee Details

Each employee can be selected from the employee directory.

Clicking an employee opens a detailed employee profile containing:

### Profile Information

- Employee Name
- Profile Image
- Role
- Department
- Employment Status

### Contact Information

- Email
- Phone

### Employment Information

- Employee Role
- Department
- Salary
- Joining Date
- Current Status

The employee details page also provides:

- ✏️ Edit Employee
- 🗑️ Delete Employee

---

# 🔎 Employee Search

Administrators can search employees using information such as:

- Employee Name
- Email
- Role

Example:

```text
Search: Software Engineer