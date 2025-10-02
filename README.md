# Java JDBC – Employee Database App

This is **Task 7** of the **Elevate Labs Java Developer Internship**.
The project demonstrates how to connect Java with a relational database using **JDBC** and perform **CRUD (Create, Read, Update, Delete)** operations on an Employee table.

---

## 📌 Objective

* Connect Java application to **MySQL/PostgreSQL database**.
* Perform **Add, View, Update, and Delete** operations on Employee records.
* Understand the use of **Connection, PreparedStatement, Statement, and ResultSet**.

---

## 🛠️ Tools & Technologies

* **Java**
* **MySQL / PostgreSQL**
* **JDBC Driver**
* **IntelliJ IDEA / VS Code**

---

## ⚙️ Setup Instructions

1. Clone this repository:

   ```bash
   git clone https://github.com/Hina7253/Employee-DB-App.git
   ```

2. Create Database and Table in MySQL/PostgreSQL:

   ```sql
   CREATE DATABASE employee_db;
   USE employee_db;

   CREATE TABLE employees (
       id INT PRIMARY KEY AUTO_INCREMENT,
       name VARCHAR(50),
       department VARCHAR(50),
       salary DOUBLE
   );
   ```

3. Add JDBC Driver JAR (`mysql-connector-j-x.x.x.jar` or `postgresql-x.x.jar`) to project libraries.

4. Update your database username & password in `DBConnection.java`:

   ```java
   private static final String URL = "jdbc:mysql://localhost:3306/employee_db";
   private static final String USER = "root";
   private static final String PASSWORD = "your_password";
   ```

5. Run the application using:

   ```bash
   javac *.java
   java EmployeeApp
   ```

---

## 📋 Features

* Add new employee
* View all employees
* Update employee salary
* Delete employee record

---

## 📌 Outcome

By completing this task, you will:

* Master **Java Database Connectivity (JDBC)**.
* Learn how to use **PreparedStatement** and **ResultSet** effectively.
* Build a mini console-based **Employee Management App**.

---

## 👩‍💻 Author

**Hina **
BCA 3rd Year | Elevate Labs Java Developer Intern
GitHub: [Hina7253](https://github.com/Hina7253)

