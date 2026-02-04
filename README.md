

# 📚 Library Management System (PostgreSQL)

A relational **Library Management System database** designed and implemented using **PostgreSQL**, based on a clean **Entity-Relationship Diagram (ERD)** and real-world library workflows.

---

## 🔹 Features
- Normalized relational database design
- Proper **Primary Key & Foreign Key** relationships
- Tracks:
  - Books
  - Members
  - Employees
  - Branches
  - Issued books
  - Returned books
- Designed for real-world library operations

---

## 🧱 Database Schema

### Tables Included
- **books** – stores book details (ISBN, title, category, rental price, status)
- **members** – registered library members
- **employees** – library staff
- **branch** – library branch details
- **issue_status** – tracks issued books
- **return_status** – tracks returned books

---

## 🔗 Relationships Overview
- A **member** can issue multiple books
- An **employee** can issue books to members
- Each **book** can be issued and returned
- Employees belong to a **branch**

---



## 🛠 Tech Stack
- **PostgreSQL**
- **SQL**
- **ERD-based database design**

---

## 🎯 Learning Outcomes
- Database normalization
- Referential integrity using foreign keys
- Practical SQL schema design
- Understanding issue/return workflows

---


