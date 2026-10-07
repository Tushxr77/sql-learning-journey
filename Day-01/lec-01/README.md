# Day 01 — Lecture 01 | Introduction to SQL

## 📚 Topics Covered

- What is SQL?
- Why do we need SQL?
- Types of SQL Commands
- Types of Databases
- Basic Database Structure
- SQL Data Types

---

## 1. What is SQL?

**SQL** stands for **Structured Query Language**.

SQL is used to communicate with and manage data stored in databases.

### Main Uses of SQL

- Store data
- Retrieve data
- Insert data
- Update data
- Delete data
- Manage databases

---

## 2. Why Do We Need SQL?

### 🔹 Talk to Data
SQL helps us communicate with databases and perform operations on data.

### 🔹 High Demand
SQL is widely used in:

- Software Development
- Data Analysis
- Data Engineering
- Data Science

### 🔹 Industry Standard
SQL is one of the most commonly used languages for working with relational databases.

---

## 3. Types of SQL Commands

### 3.1 DDL — Data Definition Language

DDL is used to define and change the structure of a database.

**Commands:**

- `CREATE`
- `ALTER`
- `DROP`

Example:

```sql
CREATE TABLE students (
    id INT,
    name VARCHAR(50)
);

### 3.2 DML — Data Manipulation Language

DML is used to insert, update, and delete data inside a table.

Commands:

- `INSERT`
- `UPDATE`
- `DELETE`

INSERT INTO students (id, name)
VALUES (1, 'Tushar');

### 3.3  DQL — Data Query Language

DQL is used to retrieve data from a database.

Command:

- `SELECT`

Example:
SELECT * FROM students;
