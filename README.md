# Employee Management System

A web-based Employee Management System developed using Java, JSP, Servlets, JDBC, and MySQL. The application helps organizations manage employee records efficiently through CRUD (Create, Read, Update, Delete) operations.

## 📌 Features

- Add New Employee
- View Employee Details
- Update Employee Information
- Delete Employee Records
- Search Employees
- User-Friendly Interface
- Database Integration with MySQL
- Secure Data Management

## 🛠️ Technologies Used

### Frontend
- HTML
- CSS
- JavaScript
- JSP

### Backend
- Java
- Servlets
- JDBC

### Database
- MySQL

### Server
- Apache Tomcat

## 📂 Project Structure

```
EmployeeManagementSystem
│
├── src/
│   ├── controller/
│   ├── dao/
│   ├── model/
│   └── utility/
│
├── WebContent/
│   ├── css/
│   ├── js/
│   ├── images/
│   └── jsp/
│
└── database/
    └── employee_db.sql
```

## 🚀 Installation and Setup

### Prerequisites

- Java JDK 8 or above
- Apache Tomcat
- MySQL Server
- Eclipse IDE (Recommended)

### Steps

1. Clone the repository

```bash
git clone https://github.com/yourusername/EmployeeManagementSystem.git
```

2. Import the project into Eclipse.

3. Create a MySQL database:

```sql
CREATE DATABASE employee_db;
```

4. Import the SQL file into MySQL.

5. Update database credentials in the JDBC configuration file:

```java
String url = "jdbc:mysql://localhost:3306/employee_db";
String username = "root";
String password = "your_password";
```

6. Configure Apache Tomcat Server.

7. Run the project.

8. Open the browser and visit:

```text
http://localhost:8080/EmployeeManagementSystem
```


## 🎯 Learning Outcomes

- Java Web Development
- MVC Architecture
- JDBC Database Connectivity
- CRUD Operations
- Servlet and JSP Integration
- MySQL Database Management

## 🔮 Future Enhancements

- Employee Authentication
- Role-Based Access Control
- Salary Management
- Attendance Management
- Export Reports to PDF/Excel
- REST API Integration

## 👨‍💻 Author

**Anushka Sarkar**

- BCA Student
- Java Full Stack Developer
- Spring Boot | JSP | Servlets | JDBC | MySQL

## ⭐ If you like this project

Give this repository a Star ⭐ on GitHub.
