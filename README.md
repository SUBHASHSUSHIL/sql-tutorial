# SQL Tutorial

## Description

This repository provides a comprehensive collection of SQL scripts, stored procedures, and reference documentation for **Microsoft SQL Server** and **MySQL**. It is designed to serve as both a practical quick-reference for developers and database administrators and a structured study guide for those preparing for SQL interviews.

The repository covers DDL operations such as `ALTER` commands, DML-driven CRUD stored procedures, database views, and SQL Server authentication configuration. A fully-realized job portal database project demonstrates schema design, relational integrity, and parameterized search procedures in a real-world application context. A curated set of PDF reference notes supplements the scripts with detailed coverage of foundational DBMS concepts, including keys, constraints, data types, joins, set operations, stored functions, and triggers.

## Topics Covered

- **DDL & ALTER Operations** — renaming databases and tables, adding and dropping columns, modifying data types, resetting identity seeds, and applying `NULL`/`NOT NULL` constraints
- **Stored Procedures** — parameterized CRUD procedures and a unified procedure pattern that dispatches insert, update, delete, and select operations through a single `@Type` parameter
- **Views** — creation and querying of filtered database views
- **Stored Functions** — concepts, syntax, and practical examples of user-defined functions
- **Triggers** — trigger mechanics, event-driven execution, and implementation examples
- **Database Keys** — super key, candidate key, primary key, foreign key, and composite key relationships
- **Constraints & Data Types** — MySQL constraint enforcement and a complete data type reference
- **Joins & Set Operations** — natural joins alongside `UNION`, `INTERSECT`, and `EXCEPT` operations
- **Application Database Design** — a complete job portal schema (`ThakurBaba`) featuring normalized tables, foreign key relationships, and full-text and date-range search procedures
- **SQL Server Security** — enabling and configuring `sa` authentication under mixed-mode security
- **Interview Preparation** — a curated set of SQL interview questions and answers

## Repository Contents

### Scripts & Notes

| File | Description |
| --- | --- |
| `Alter Command.txt` | `ALTER` command reference — renaming databases/tables, adding and dropping columns, changing data types, resetting identity, and managing `NULL`/`NOT NULL` constraints |
| `Store Procedure` | Stored procedure examples for full CRUD operations, plus a unified single-procedure pattern that routes insert/update/delete/select by a `@Type` parameter |
| `Create-View-Procedure` | Example of creating and querying a filtered SQL `VIEW` |
| `SQL Server Login Setup` | Step-by-step guide to enabling `sa` login, setting the password, and restarting SQL Server for mixed-mode authentication |
| `Job Portal Project Query` | A complete job portal database schema (`ThakurBaba`) with tables for companies, jobs, users, admins, and resumes, plus stored procedures for CRUD, text search, and date-range search |

### Reference Materials (`pic and pdf/`)

PDF study notes on core database concepts:

- **Keys in DBMS** — super key, candidate key, primary key, foreign key, and more
- **MySQL Constraints** and **MySQL Data Types**
- **MySQL Views**
- **Natural Join** and **Set Operations in SQL**
- **Stored Procedures** (4 parts) and **Stored Functions** (3 parts)
- **Triggers** (5 parts)
- **SQL Interview Questions**

## How to Use

1. Clone the repository:
   ```sh
   git clone https://github.com/SUBHASHSUSHIL/sql-tutorial.git
   ```
2. Open the `.txt` files in any text editor to view and copy the SQL scripts.
3. Open the PDFs in `pic and pdf/` with a PDF reader for the study notes.

## Contribution

- Create a new branch (`git checkout -b new-sql-scripts`)
- Add your scripts and commit (`git commit -m 'Added new SQL script'`)
- Push to your branch (`git push origin new-sql-scripts`)
- Open a pull request for review
