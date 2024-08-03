

# 🛒 Imaginary Purchase Order System

This repository features an SQL-based project for managing an imaginary Purchase Order System. It establishes relationships between items, customers, orders, and line items. The project delivers various SQL queries to efficiently handle data related to the purchase order system.

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

- 🔗 Establish relationships between items, customers, orders, and line items
- 📝 Execute multiple SQL queries for data manipulation
- 📅 Display order date and calculate approximate shipping date (3 days after order date)
- 📈 Comprehensive project report including ER diagram, constraints, keys, relationships, and metadata

## Technologies Used

- SQL
- Relational Database Management System (RDBMS)

## Project Structure

```
ImaginaryPurchaseOrderSystem/
├── sql/
│   ├── create_tables.sql
│   ├── insert_data.sql
│   └── queries.sql
├── resources/
│   └── Project_Report.pdf
├── screenshots/
│   └── query_execution.png
└── README.md
```

## Setup

1. **Clone the repository:**

    ```bash
    git clone https://github.com/Soumita-2018/Imaginary-Purchase-Order-System-SQL.git
    cd ImaginaryPurchaseOrderSystem
    ```

2. **Ensure that an RDBMS (e.g., MySQL, PostgreSQL) is installed and running on your machine.**

3. **Create the necessary database and run the SQL scripts in the `sql` directory in the following order:**

    - `create_tables.sql`
    - `insert_data.sql`

## Usage

1. Open your preferred SQL client and connect to your database.

2. Execute the queries in the `queries.sql` file to interact with the purchase order system.

## SQL Queries

Here are some example SQL queries included in the project:

- **Display order date and approximate shipping date (3 days after order date):**

    ```sql
    SELECT order_id, order_date, order_date + INTERVAL 3 DAY AS approximate_shipping_date
    FROM orders;
    ```

- Other queries for retrieving and manipulating data related to items, customers, orders, and line items.

## ER Diagram

The ER Diagram, including constraints, keys, relationships, and metadata, is detailed in the project report (Project_Report.pdf) located in the resources directory.

![ER Diagram](resources/ER_Diagram.png)

## Screenshots

### Example Query Execution

![Query Execution](screenshots/query_execution.png)

---

Feel free to contribute to the project by forking the repository and submitting pull requests. For any issues or feature requests, please open an issue in the repository.

---

Happy Querying! 🚀
