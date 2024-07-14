# Imaginary-Purchase-Order-System-SQL
IMAGINARY PURCHASE ORDER SYSTEM TO CREATE RELATIONSHIP BETWEEN ITEMS, CUSTOMERS, ORDERS, LINE ITEMS.

THE DELIVERABLES OF THE PROJECT IS EXECUTION OF MULTIPLE SQL QUERIES RELATED TO

THIS PURCHASE ORDER SYSTEM.

E,G: DISPLAYING ORDER DATE, APPROXIMATE SHIPPING DATE, AFTER 3 DAYS FROM THE DAY WHEN ORDER HAS BEEN PLACED.

*THE ENTIRE ER DIAGRAM INCLUDING CONSTRAINTS, KEYS, RELATIONSHIPS, META DATA HAS BEEN DESCRIBED IN THE PRJECT EXPLANATION PDF(PROJECT REPORT).

# Imaginary Purchase Order System

This repository contains an SQL-based project for an imaginary Purchase Order System. The project creates relationships between items, customers, orders, and line items. The deliverables include the execution of multiple SQL queries related to the purchase order system.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Setup](#setup)
- [Usage](#usage)
- [SQL Queries](#sql-queries)
- [ER Diagram](#er-diagram)
- [Screenshots](#screenshots)

## Features

- Relationships between items, customers, orders, and line items
- Execution of multiple SQL queries
- Display order date and approximate shipping date (3 days after order date)
- Comprehensive project report including ER diagram, constraints, keys, relationships, and metadata

## Technologies Used

- SQL
- Relational Database Management System (RDBMS)


## Setup

1. Clone the repository:

    bash
    git clone https://github.com/yourusername/ImaginaryPurchaseOrderSystem.git
    cd ImaginaryPurchaseOrderSystem
    

2. Ensure that an RDBMS (e.g., MySQL, PostgreSQL) is installed and running on your machine.

3. Create the necessary database and run the SQL scripts in the sql directory in the following order:
    - create_tables.sql
    - insert_data.sql

## Usage

1. Open your preferred SQL client and connect to your database.

2. Execute the queries in the queries.sql file to interact with the purchase order system.

## SQL Queries

Some example SQL queries included in the project:

- Display order date and approximate shipping date (3 days after order date):

    sql
    SELECT order_id, order_date, order_date + INTERVAL 3 DAY AS approximate_shipping_date
    FROM orders;
    

- Other queries for retrieving and manipulating data related to items, customers, orders, and line items.

## ER Diagram

The ER Diagram including constraints, keys, relationships, and metadata is described in the project explanation PDF (Project_Report.pdf) located in the resources directory.

![ER Diagram](resources/ER_Diagram.png)

## Screenshots

### Example Query Execution

![Query Execution](screenshots/query_execution.png)

---

Feel free to contribute to the project by forking the repository and submitting pull requests. For any issues or feature requests, please open an issue in the repository.

---

Happy Querying!
