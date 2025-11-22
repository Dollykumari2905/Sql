👨‍💼 Employee Management System (SQL Project)

The Employee Management System is a fully functional SQL-based project designed to efficiently store, manage, and retrieve organizational data.
It includes modules for employees, departments, attendance, salary, and project assignments, making it a complete mini-DBMS project.

📌 Project Overview

This SQL project demonstrates:

Database creation

Table design with relationships

Data insertion and updating

Use of primary keys, foreign keys, constraints

Join queries

Aggregation functions

Real-world HR and payroll-related queries

🗂️ Database Structure
1. Department Table

Stores department details and manager assignments.

2. Employee Table

Stores employee information including personal details, department, and designation.

3. Attendance Table

Tracks employee daily attendance status (Present, Absent, Leave).

4. Salary Table

Stores salary components & calculates net salary.

5. Project Table

Maintains employee project assignments.

🔗 ER Relationships

Department → Employee: One-to-Many

Employee → Attendance: One-to-Many

Employee → Salary: One-to-One

Employee → Project: One-to-Many

⭐ Key Features

✔ Employee Registration
✔ Department Management
✔ Attendance Tracking
✔ Payroll Calculation (Net Salary)
✔ Project Assignment
✔ Manager Mapping
✔ Useful Business Reports

🧠 Concepts Used

. SQL DDL (CREATE DATABASE, CREATE TABLE)

. SQL DML (INSERT, UPDATE)

. JOINs (INNER JOIN)

. GROUP BY & Aggregations

. Constraints:

   . Primary Key

   . Foreign Key

   . CHECK

   . UNIQUE

. Functions: SUM(), AVG(), ROUND()

. Case-based counting (Present/Absent/Leave)

📊 Sample Output Queries
✔ Employee with Department

Shows employee details with department name.

✔ Department Managers

Displays each department with assigned manager.

✔ Attendance Summary

Counts Present, Absent, Leave per employee.

✔ Salary Report

Shows employees with their net salary.

✔ Average Salary by Department

Groups salary by department.

✔ Project Assignments

Lists employees and their assigned projects.
