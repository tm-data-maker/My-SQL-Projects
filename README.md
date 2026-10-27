# 🗄️ SQL Projects – Data Technician Bootcamp

<p align="center">
  <img src="https://img.shields.io/badge/Language-SQL-blue.svg?style=for-the-badge&logo=postgresql" alt="SQL" />
  <img src="https://img.shields.io/badge/Database-Supabase-green.svg?style=for-the-badge&logo=supabase" alt="Supabase" />
  <img src="https://img.shields.io/badge/Course-Data%20Technician-orange.svg?style=for-the-badge" alt="Bootcamp" />
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen.svg?style=for-the-badge" alt="Status" />
</p>

---

> 🎯 **Project Overview:**  
> Practical coursework and hands-on exercises completed during Week 3 of the **Data Technician Bootcamp**. This repository covers relational database design concepts, database comparison (SQL vs. NoSQL), and running SQL queries on the **Northwind** and **World** databases using Supabase.

---

## 💡 What I Learned & Practiced

### 🛠️ Core Concepts
* 🔹 **Database Fundamentals:** Understanding primary keys, foreign keys, and table relationships.
* 🔹 **SQL vs. NoSQL:** Comparing structured relational tables with flexible document stores.
* 🔹 **Database Schema Design:** Designing entity-relationship blueprints for training systems.

### 🔍 SQL Querying Techniques
* 🔸 **Data Filtering:** Using `WHERE`, `LIKE`, `IN`, and `BETWEEN` operators.
* 🔸 **Sorting & Pagination:** Sorting results with `ORDER BY` and limiting rows via `LIMIT` / `OFFSET`.
* 🔸 **Aggregations & Grouping:** Calculating summaries using `COUNT`, `SUM`, `AVG`, and `GROUP BY`.
* 🔸 **Relational Joins:** Combining multi-table datasets using `INNER JOIN` and `LEFT JOIN`.

---

## 📂 Repository Contents

```text
📁 My-SQL-Projects/
├── 📄 Data_Technician_Workbook_Week_3_SB_June_2026.docx  # Theory & completed tasks
├── 📄 Create Northwind Tables on Supabase.docx            # Northwind schema setup script
├── 📄 Create World DB on Supabase.txt                      # World DB schema setup script
├── 📄 Day 2 Supabase SQL Queries.txt                      # Executed practice queries
└── 📄 README.md                                           # Repository documentation
```
---

## 💻 Sample SQL Queries

### 🏬 Northwind Database Tasks

* **Export Complete Customer Records:** The management requires a full dataset of all registered clients for internal auditing.  
➡️ *SQL query to select all fields from the Customers table.*
```sql
SELECT * 
FROM customers;

```sql
SELECT * 
FROM customers;
```

###
### High-Value Products Filter
- Task: Retrieve all products priced over £50.

```sql
SELECT * 
FROM products 
WHERE price > 50;
```

###
