# Es Teh Manis Solo — Database Design

## Overview

This project focuses on designing a relational database for Es Teh Manis Solo, a beverage business. The database is designed to organize operational data, including staff, branches, beverage menus, inventory, payments, and transactions.

The project demonstrates the application of database design concepts and SQL queries to support structured data management and sales reporting.

## Objectives

- Design a relational database based on business requirements.
- Define relationships between entities using primary keys and foreign keys.
- Organize menu, inventory, payment, and transaction records.
- Retrieve and summarize business information using SQL queries.

## Database Schema

The database consists of seven main tables:

| Table | Description |
|---|---|
| `Staff` | Stores staff information |
| `Menu` | Stores beverage menu items, categories, and prices |
| `Cabang` | Stores branch information and status |
| `Stok` | Stores ingredient and inventory information |
| `Bahan_Menu` | Connects menu items with their ingredients |
| `Pembayaran` | Stores payment dates, methods, and staff references |
| `Transaksi` | Stores ordered menu items, quantities, and subtotals |

## SQL Concepts Demonstrated

- **DDL:** Creating domains and tables.
- **DML:** Inserting, updating, deleting, and retrieving records.
- **Constraints:** Primary keys, foreign keys, and check constraints.
- **JOIN:** Combining related data across tables.
- **Aggregation:** Using `SUM()`, `AVG()`, and `COUNT()`.
- **Grouping and filtering:** Using `GROUP BY` and `HAVING`.
- **Subqueries:** Retrieving data based on other query results.
- **Views:** Creating a daily transaction report view.
- **CASE expressions:** Categorizing menu prices.
- **Sequences and bind variables:** Exploring Oracle SQL features.

## Tools and Technologies

- Oracle SQL
- SQL Developer
- Draw.io for Entity Relationship Diagram (ERD)

## Repository Structure

- `sql/` — SQL scripts for schema creation, sample data, and queries.
- `erd/` — Database relationship diagram.
- `docs/` — Project documentation.

## Project Scope

This is an academic database design project. The database uses sample records to demonstrate relational database design and SQL operations.

## Author's Contribution

This project was developed as part of a Database System course in a team setting. My portfolio version will document the database design and SQL work, with individual contributions identified accurately.

## Future Improvements

- Improve data validation and consistency.
- Refine transaction and inventory relationships.
- Develop additional queries for sales summaries and inventory monitoring.
- Add reproducible setup instructions and sample query outputs.
