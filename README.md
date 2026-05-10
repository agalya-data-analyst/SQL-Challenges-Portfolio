# SQL-Challenges-Portfolio
# 🚀 7-Day SQL Mastery Challenge: From Basics to Automation

Welcome to my SQL Portfolio! This repository documents my intensive 7-day journey where I built and managed multiple databases, solved complex business problems, and implemented database automation.

## 📊 Projects Overview

| Day | Database | Focus Area | Key Concepts |
|:---:|:---|:---|:---|
| 1-2 | **Hospital DB** | Data Definition (DDL) | Schema design, Tables, Primary & Foreign Keys |
| 3 | **Online Bookstore** | Data Manipulation (DML) | CRUD operations (Insert, Update, Delete) |
| 4-5 | **E-Commerce DB** | Data Retrieval & Filtering | WHERE, Clauses, Operators, & Aggregations |
| 6 | **Student DB** | Relationship Management | INNER, LEFT, RIGHT Joins & String Functions |
| 7 | **Company DB** | Advanced SQL & Automation | Subqueries, CTEs, Views, and Triggers |

---

## 📂 Project Breakdown & Commands Used

### 🏥 1. Hospital_db (Day 1-2: DDL Focus)
**Objective:** Building a solid database structure for healthcare management.
* **Commands Used:** `CREATE TABLE`, `ALTER TABLE`, `DROP TABLE`, `TRUNCATE`.
* **Key Technical Skills:** * Defining **Primary Keys** (PatientID, DoctorID) to ensure unique records.
    * Enforcing **NOT NULL** and **UNIQUE** constraints.
    * Establishing **Foreign Key** relationships to link appointments with doctors.


### 📚 2. OnlineBookStore_db (Day 3: DML Focus)
**Objective:** Managing real-time inventory and transactions.
* **Commands Used:** `INSERT INTO`, `UPDATE`, `DELETE`, `SELECT`.
* **Key Technical Skills:** * Performing **CRUD operations** to add new books and update prices.
    * Handling data modifications without affecting table structure.


### 🛒 3. ECommerce_db (Day 4-5: Data Analysis)
**Objective:** Turning raw sales data into business insights.
* **Commands Used:** `WHERE`, `AND/OR`, `LIKE`, `GROUP BY`, `HAVING`, `ORDER BY`.
* **Key Technical Skills:** * **Complex Filtering:** Finding specific orders using pattern matching (`%`).
    * **Aggregations:** Using `SUM()`, `AVG()`, and `COUNT()` to calculate total revenue and inventory stats.


### 🎓 4. Student_db (Day 6: Relationship Management)
**Objective:** Connecting distributed data for unified reporting.
* **Commands Used:** `INNER JOIN`, `LEFT JOIN`, `RIGHT JOIN`, `CONCAT()`, `UPPER()`.
* **Key Technical Skills:** * Linking Students, Courses, and Departments using multi-table **Joins**.
    * **Data Cleaning:** Using String functions to format student names professionally.
.

### 🏢 5. Company_db (Day 7: Advanced Automation)
**Objective:** Automating database tasks and high-level reporting.
* **Commands Used:** `CREATE TRIGGER`, `CREATE VIEW`, `SUBQUERIES`, `CTE`.
* **Key Technical Skills:** * **Triggers:** Automated auditing to track employee insertions and deletions.
    * **Views:** Created virtual tables to mask sensitive salary data for HR reporting.
    * **Complex Logic:** Used **Correlated Subqueries** to compare salaries against department averages.


---

## 🛠️ Key Technical Skills Summary
* **Data Modeling:** Designing ER Diagrams with complex relationships.
* **Automation:** Implementing Triggers for data security and history.
* **Reporting:** Creating Views and using Joins for streamlined analysis.
* **Data Integrity:** Expert use of Constraints (PK, FK, Unique).
  Implemented advanced triggers in the **Company DB** to automate business logic:
- **Audit Logs:** Automatically tracking new employee additions.
- **Salary Tracking:** Keeping history of salary changes (Old vs New).

---

### 2. Complex Data Analysis
Using **Joins** and **Subqueries**, I solved scenarios like:
- Identifying top-performing students and courses.
- Calculating revenue and inventory status in E-Commerce.
- Finding employees earning above the department average using **Correlated Subqueries**.

### 3. Virtual Tables (Views)
Created **Simple and Complex Views** to simplify reporting for HR and Finance departments, ensuring data security and easier access to complex join results.

---

  ## 📂 Repository Structure
- `/Hospital_db`: DDL scripts for healthcare schema.
- `/OnlineBookStore_db`: DML scripts for inventory management.
- `/ECommerce_db`: Analysis queries for sales and filtering.
- `/Student_db`: Join-based queries and string formatting.
- `/Company_db`: Advanced automation (Triggers, Views, Subqueries).

  ---
## 💻 Tools Used
- **Database:** MySQL 8.0
- **IDE:** MySQL Workbench
- **Documentation:** Markdown
- 

---
**Contact:** [Agalya J] | [https://www.linkedin.com/in/agalyajayapal/]
