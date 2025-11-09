# ExpenseTracker (JDBC + MySQL) - Mini Project

## Files
- Main.java
- create_db.sql

## Requirements
- JDK 8+ (17 recommended)
- MySQL server
- MySQL Connector/J (.jar)

## Setup
1. Run `create_db.sql` in MySQL Workbench or CLI.
2. Put `mysql-connector-j-x.x.x.jar` in project folder or set classpath.

## Build & Run
(Windows)
javac Main.java
java -cp .;mysql-connector-j-9.0.0.jar Main

(Linux/Mac)
javac Main.java
java -cp .:mysql-connector-j-9.0.0.jar Main

## Notes for evaluator
- DB name: `ExpenseDB`
- Change DB credentials in `Main.java` if needed (URL, USER, PASS)

## Author
Name: Gopinath S

Reg No: 421622104039

Dept: B.E CSE

College: Mailam Engineering College

Project Title: Simple Budget and Expense Tracker using JDBC and MySQL


