# 💰 ExpenseTracker (JDBC + MySQL) - Mini Project

A simple **console-based Java project** for tracking daily expenses using **JDBC** with **MySQL** integration.  
This project allows users to **Add, View, Update, Delete**, and **Summarize** expenses by category.  
Perfect for **college submissions**, **JDBC practice**, and **database connectivity demonstrations**. 🚀

---

## 🧠 Features
- Add new expense entries  
- View all expenses  
- Filter expenses by category  
- Update expense amount by ID  
- Delete expense records  
- View total spending by category  

---

## ⚙️ Requirements
| Component | Version / Notes |
|------------|----------------|
| **JDK** | 8 or higher (17 recommended) |
| **MySQL Server** | 8.x |
| **MySQL Connector/J** | `.jar` file (example: mysql-connector-j-9.0.0.jar) |

---

## 🗄️ Files Included
| File Name | Description |
|------------|-------------|
| `Main.java` | Main program with full CRUD + JDBC logic |
| `Config.java` | Database connection credentials file |
| `create_db.sql` | SQL script to create database & table |
| `README.md` | Project documentation |

---

## 🧱 Database Details
**Database Name:** `ExpenseDB`  
**Table Name:** `Expenses`  

Run this SQL before executing the Java program:
```sql
CREATE DATABASE IF NOT EXISTS ExpenseDB;
USE ExpenseDB;

CREATE TABLE IF NOT EXISTS Expenses (
    expense_id INT AUTO_INCREMENT PRIMARY KEY,
    description VARCHAR(255) NOT NULL,
    amount DECIMAL(10,2) NOT NULL,
    category VARCHAR(100),
    expense_date DATE NOT NULL
);
