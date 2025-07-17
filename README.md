# 📚 Online Book Store SQL Project

## 📖 About
This project is a sample **Online Book Store Database** designed to practice SQL concepts.  
It includes:
- A complete relational schema for an online bookstore
- Sample data inserts
- Example queries for reporting and analysis

You can use this project to learn **SQL DDL**, **DML**, **JOINs**, **GROUP BY**, and even integrate it with tools like **Excel** or **Power BI** for dashboards.

---

## 🏗️ Database Schema
The database contains the following tables:

| Table | Description |
|-------|-------------|
| `categories` | Stores book categories (e.g., Fiction, Technology) |
| `books` | Stores book details (title, author, price, stock, category) |
| `customers` | Stores customer details |
| `orders` | Stores order header details |
| `order_items` | Stores individual book items within an order |

---

## 📂 Files in This Repository
- **`online_bookstore.sql`** → Contains:
  - `CREATE TABLE` scripts
  - `INSERT` sample data
  - Example `SELECT` queries
- **`README.md`** → This documentation
- *(Optional)* ER diagram or screenshots if you add them

---

## ⚡ Technologies
- PostgreSQL or MySQL (scripts are generic and can be adapted)
- SQL (DDL, DML, queries)
- *(Optional)* Excel / Power BI for visualization

---

## 🚀 How to Run

### 1️⃣ Create a new database
```sql
CREATE DATABASE online_bookstore;
