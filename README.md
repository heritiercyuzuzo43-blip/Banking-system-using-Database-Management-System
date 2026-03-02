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
