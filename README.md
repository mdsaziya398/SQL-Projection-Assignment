# SQL Projection Assignment

## 📌 Project Overview

This repository contains my SQL Projection Assignment completed as part of my SQL practice.

The assignment focuses on using the `SELECT` statement to retrieve specific columns from database tables instead of displaying all columns.

The queries are performed mainly on the standard EMP and DEPT tables.



## 🎯 Objective

The main objective of this assignment is to practice SQL projection queries and understand how to retrieve required columns from database tables using the `SELECT` statement.



## 🗂️ Tables Used

### EMP Table

The `EMP` table contains employee-related information such as:

* EMPNO
* ENAME
* JOB
* MGR
* HIREDATE
* SAL
* COMM
* DEPTNO

The assignment begins by displaying all records from the `EMP` table.

### DEPT Table

The `DEPT` table is used to retrieve department information such as:

* DNAME
* LOC

The assignment retrieves department names and their locations.


## 💻 SQL Concepts Practiced

The assignment covers:

* `SELECT` statement
* Selecting specific columns
* Selecting multiple columns
* Retrieving employee information
* Retrieving salary information
* Retrieving commission information
* Retrieving department numbers
* Retrieving hire dates
* Retrieving job information
* Retrieving department names
* Retrieving department locations
* Identifying SQL errors


## 📝 Queries Practiced

### 1. Display All Employee Details

```sql
SELECT * FROM EMP;
```

### 2. Display Employee Names

```sql
SELECT ENAME FROM EMP;
```

### 3. Display Employee Names and Salaries

```sql
SELECT ENAME, SAL FROM EMP;
```

### 4. Display Employee Names and Commission

```sql
SELECT ENAME, COMM FROM EMP;
```

### 5. Display Employee Number and Department Number

```sql
SELECT EMPNO, DEPTNO FROM EMP;
```

### 6. Display Employee Names and Hire Dates

```sql
SELECT ENAME, HIREDATE FROM EMP;
```

### 7. Display Employee Names and Jobs

```sql
SELECT ENAME, JOB FROM EMP;
```

### 8. Display Employee Names, Jobs and Salaries

```sql
SELECT ENAME, JOB, SAL FROM EMP;
```

### 9. Display Department Names

```sql
SELECT DNAME FROM DEPT;
```

### 10. Display Department Names and Locations

```sql
SELECT DNAME, LOC FROM DEPT;
```

These queries and their Oracle SQL outputs are included in the provided assignment.



## ⚠️ SQL Error Practice

The assignment also includes an incorrect query:

```sql
SELECT ENAME.COMM FROM EMP;
```

Oracle returns:

```text
ORA-00904: "ENAME"."COMM": invalid identifier
```

The corrected query is:

```sql
SELECT ENAME, COMM FROM EMP;
```

This demonstrates the importance of using the correct column-selection syntax in SQL.



## 📊 Sample Data

The `EMP` table contains **14 employee records**, including employees such as:

* SMITH
* ALLEN
* WARD
* JONES
* MARTIN
* BLAKE
* CLARK
* SCOTT
* KING
* TURNER
* ADAMS
* JAMES
* FORD
* MILLER

The assignment also retrieves department information for:

* ACCOUNTING — NEW YORK
* RESEARCH — DALLAS
* SALES — CHICAGO
* OPERATIONS — BOSTON

---

## 🛠️ Technologies Used

* **Oracle SQL**
* **SQL*Plus / Oracle SQL environment**




## 📁 Project Structure

```text
SQL-Projection-Assignment/
│
├── README.md
│
└── PROJECTIONS.txt



## 🚀 How to Run

1. Open an Oracle SQL environment such as SQL*Plus.
2. Connect to the database.
3. Make sure the `EMP` and `DEPT` tables are available.
4. Execute the SQL queries from the assignment.
5. View the query results in the Oracle SQL output.


## 📚 Learning Outcome

Through this assignment, I practiced retrieving selected columns from database tables using SQL `SELECT` statements.

I also practiced working with employee and department data and identified and corrected an invalid SQL query.



## 👩‍💻 Author

Mohammad Saziya

GitHub: `mdsaziya398`


## ⭐ Repository Purpose

This repository is maintained as part of my SQL learning and practice journey, documenting SQL queries, assignments, and hands-on database exercises.












