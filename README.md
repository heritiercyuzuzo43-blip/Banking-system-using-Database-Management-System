# 🏦 Banking Database Management System (Oracle SQL)

## 📖 Project Overview
This project is a **Banking Database Management System** developed using **Oracle SQL** as part of the Database Management System (DBMS) course.

The system models real-world banking operations including:
- Customer Management
- Account Handling
- Transaction Processing
- Loan Management
- Card Services
- Branch & Employee Management

This project demonstrates database design, normalization, constraints, and relational integrity using structured SQL.

---

## 🎯 Objectives
- Design a structured banking database schema
- Implement relationships using **Primary Keys & Foreign Keys**
- Enforce data integrity using **CHECK, UNIQUE, NOT NULL constraints**
- Perform queries using `SELECT`, `JOIN`, `GROUP BY`, `BETWEEN`, `LIKE`
- Simulate real-world banking operations

---

## 🗂 Database Schema

The system consists of **7 main tables**:

1. **Customers**
2. **Accounts**
3. **Transactions**
4. **Loans**
5. **Branches**
6. **Employees**
7. **Cards**

### 🔗 Relationships
- One Customer → Many Accounts
- One Account → Many Transactions
- One Customer → Many Loans
- One Customer → Many Cards
- One Branch → Many Employees
- One Branch → Many Accounts

---

## 🛠 Technologies Used
- Oracle Database
- SQL (DDL & DML)
- SQL*Plus

---

## 📁 Project Structure
Banking-Database/
│
├── 01_create_tables.sql
├── 02_insert_data.sql
├── 03_queries.sql
└── README.md

---

## ⚙️ Features Implemented

### ✔ Table Creation
- Proper use of `PRIMARY KEY`
- `FOREIGN KEY` relationships
- `CHECK` constraints
- `UNIQUE` constraints

### ✔ Data Manipulation
- Insert sample banking records
- Update and delete operations
- Transaction commit control

### ✔ Query Operations
- Filtering using `LIKE` and `BETWEEN`
- Aggregation using `SUM()` and `GROUP BY`
- Date filtering
- Real-time balance checks

---

## 📊 Sample Queries

### Customers with names starting with 'J'
```sql
SELECT * FROM Customers
WHERE FirstName LIKE 'J%';
SELECT * FROM Accounts
WHERE Balance BETWEEN 20000 AND 80000;
SELECT BranchID, SUM(Balance)
FROM Accounts
GROUP BY BranchID;
🚀 Learning Outcomes

Through this project, I gained practical knowledge in:

Relational database design

Normalization concepts

Constraint implementation

Query optimization basics

Real-world banking system modeling

📌 Future Improvements

Implement Stored Procedures

Add Triggers for automatic transaction logging

Create Views for reporting

Add Indexing for performance optimization

Integrate with a front-end application

👨‍💻 Author

Cyuzuzo Twizere Heritier
B.Sc. IT – Marwadi University
Aspiring IT Analyst | Database & Cybersecurity Enthusiast

⭐ Conclusion

This project demonstrates a structured and scalable banking database system built using Oracle SQL, ensuring data integrity, security, and efficient transaction management.

If you found this project helpful, feel free to ⭐ the repository!
