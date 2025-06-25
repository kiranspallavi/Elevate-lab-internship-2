# 📚 SQL Developer Internship – Task 2

### ✅ Task Title: Data Insertion and Handling Nulls

This task focuses on inserting sample data into the database, handling `NULL` values, and practicing basic Data Manipulation Language (DML) commands such as `INSERT`, `UPDATE`, and `DELETE`.

---

## 🧩 **Domain**: Online Bookstore

This database simulates a basic online bookstore system with the following key entities:

- **Users**
- **Authors**
- **Books**
- **Categories**
- **Orders**
- **OrderItems**
- **Payments**

---

## 🎯 **Objectives**

- Practice `INSERT INTO` to add data.
- Handle missing or unknown values using `NULL`.
- Update and delete records with appropriate `WHERE` clauses.
- Simulate rollback and test for data consistency.
- Use `IS NULL`, partial inserts, and conditional logic.

---

## 📁 **Files Included**

- `task2_data.sql` – SQL script with `INSERT`, `UPDATE`, and `DELETE` statements.
- `task1_schema.sql` *(optional)* – Schema file from Task 1 (if needed for reference).
- `README.md` – This file.

---

## 🧪 **Key SQL Features Demonstrated**

| Feature                | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| `INSERT INTO`          | Adds complete and partial records.                                          |
| `IS NULL`              | Checks and handles missing values.                                          |
| `UPDATE`               | Updates both single and multiple rows.                                      |
| `DELETE`               | Deletes with condition (and via foreign key dependency).                    |
| `INSERT ... SELECT`    | Demonstrates dynamic insertion from existing records.                       |
| `NULL` handling        | Inserts and updates fields with `NULL`, sets default values where needed.   |
| `ROLLBACK` simulation  | Uses transactions to undo unintended deletes.                               |

---

## 🛠️ **Tools Used**

- DB Fiddle / SQLiteStudio / MySQL Workbench *(any one)*
- MySQL RDBMS

---

## 📌 **How to Run**

1. Open your preferred SQL tool.
2. Execute `task1_schema.sql` to create the schema (if not already done).
3. Run `task2_data.sql` to populate and manipulate data.
4. View tables using:
   ```sql
   SELECT * FROM Users;
   SELECT * FROM Books;
   SELECT * FROM Orders;
