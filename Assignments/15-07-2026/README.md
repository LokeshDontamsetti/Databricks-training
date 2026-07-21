# 📚 SQL Joins Practice Assignments

This repository contains my SQL Join practice assignments completed as part of my database learning journey. The exercises cover different types of joins along with practical scenarios to strengthen SQL querying skills.

---

## 📂 Folder Structure

```text
Assignments
└── 📁 15-07-2026
    ├── 📄 01_Inner_Join.sql
    ├── 📄 02_Left_Join.sql
    ├── 📄 03_Right_Join.sql
    ├── 📄 04_Full_Join.sql
    ├── 📄 05_Left_Anti_Join.sql
    ├── 📄 06_Right_Anti_Join.sql
    └── 📄 07_Full_Anti_Join.sql
```

---

## 📖 Topics Covered

### 🔹 INNER JOIN
Returns only the matching records from both tables.

✔ Employee & Department details  
✔ Employee & Project details  
✔ Department-wise statistics  
✔ Manager-Employee relationships

---

### 🔹 LEFT JOIN
Returns all records from the left table and matching records from the right table.

✔ Employees without departments  
✔ Employees without projects  
✔ Departments with zero employees  
✔ Departments with no projects

---

### 🔹 RIGHT JOIN
Returns all records from the right table and matching records from the left table.

✔ Departments without employees  
✔ Projects without employees  
✔ Employee count by department  
✔ Project assignments

---

### 🔹 FULL JOIN
Returns all matching and non-matching records from both tables.

✔ Employees & Departments  
✔ Departments & Projects  
✔ Employees & Projects  
✔ Unmatched records

> **Note:** MySQL does not support `FULL OUTER JOIN` directly. These queries are written for learning purposes.

---

### 🔹 LEFT ANTI JOIN
Returns records present only in the left table.

✔ Employees without departments  
✔ Employees without projects  
✔ Departments without projects  
✔ Projects without departments

---

### 🔹 RIGHT ANTI JOIN
Returns records present only in the right table.

✔ Departments without employees  
✔ Projects without employees  
✔ Invalid department references  
✔ Orphan project records

---

### 🔹 FULL ANTI JOIN
Returns all unmatched records from both tables.

✔ Employees ↔ Departments  
✔ Departments ↔ Projects  
✔ Employees ↔ Projects  
✔ Orphan records

---

## 🗂 Database Tables

- 🏢 Departments
- 👨‍💼 Employees
- 📁 Projects
- 🔗 EmployeeProjects

---

## 🎯 Learning Outcomes

By completing these assignments, I practiced:

- ✅ INNER JOIN
- ✅ LEFT JOIN
- ✅ RIGHT JOIN
- ✅ FULL JOIN
- ✅ LEFT ANTI JOIN
- ✅ RIGHT ANTI JOIN
- ✅ FULL ANTI JOIN
- ✅ Multi-table Joins
- ✅ Self Joins
- ✅ Aggregate Functions with JOINs
- ✅ Group By & Having
- ✅ Real-world SQL Scenarios

---

## 💻 Database

- **MySQL 8.0+**
- **SQL Workbench**

---

⭐ If you found this repository useful, feel free to explore the queries and use them for your own SQL practice.
