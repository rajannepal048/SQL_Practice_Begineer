# 🗃️ SQL Practice Projects for Beginners

This project documents my hands-on SQL practice using beginner-friendly tutorials online. I recreated, experimented with, and modified multiple SQL queries to build a solid foundation in relational databases, table operations, constraints, joins, functions, and logical operators.

---

## 📌 Overview

This practice project covers essential SQL concepts using MySQL syntax.  
All tasks were performed using a local MySQL setup to simulate real-world data manipulation scenarios.

---

## 📁 Project Structure

- `SQL Project.docx` – Contains all the SQL commands used in this practice.
- `README.md` – Describes the purpose and summary of SQL operations covered.

---

## 🔧 Skills Demonstrated

### 📂 Database and Table Management
- Creating and renaming databases and tables  
- Adding, modifying, and dropping columns  
- Inserting and deleting data records

### 🔍 Data Retrieval
- Basic `SELECT` statements  
- Filtering with `WHERE`, `BETWEEN`, `IN`, and `LIKE`  
- Sorting results with `ORDER BY`  
- Limiting results with `LIMIT`

### ✏️ Updating Data
- Updating single or multiple columns with `UPDATE`  
- Applying conditional updates using `WHERE`

### 🔑 Constraints and Integrity
- Adding `PRIMARY KEY`, `FOREIGN KEY`, `UNIQUE`, `CHECK`, and `NOT NULL` constraints  
- Using `AUTO_INCREMENT` for unique identifiers

### 🔗 Joins
- Combining data with `INNER JOIN`, `LEFT JOIN`, and `RIGHT JOIN`

### 🧠 SQL Functions
- Aggregate functions: `COUNT()`, `MAX()`, `MIN()`, `AVG()`, `SUM()`  
- String concatenation using `CONCAT()`

### 🤖 Logical Operators
- Combining conditions with `AND`, `OR`, `NOT`

### 🔁 Advanced Filtering
- Using wildcards (`%`, `_`) with `LIKE`  
- Combining logical operators for complex conditions

### 🧾 UNION Operation
- Merging query results from multiple tables using `UNION`

---

## ✅ Sample Tables Used

- **employees**  
  Stores employee information including name, hourly pay, hire date, and job role.

- **products**  
  Demonstrates usage of `UNIQUE`, `NOT NULL`, and `DEFAULT` constraints.

- **customers** and **transactions**  
  Used to practice relational database design and `FOREIGN KEY` constraints.

---

## 🧪 Example Query

```sql
SELECT first_name, last_name
FROM employees
WHERE hire_date BETWEEN "2023-01-04" AND "2023-01-07"
ORDER BY last_name DESC;

---
🧠 What I Learned
- How to create and manipulate SQL databases and tables from scratch

- Practical understanding of constraints and keys

- The importance of relationships in relational databases

- How to retrieve and manage data using various queries and filters

---

🚀 How to Use This Project
- Clone this repository to your local machine.

- Open SQL Project.docx to view documented queries.

- Optionally, convert them into .sql and run in your local MySQL environment.


