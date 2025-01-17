# Property Renovation Database Project

## Overview

This project involves the design, implementation, and querying of a **relational database** to efficiently manage the renovation of residential properties in Southern Italy. The database was created to streamline operations, track renovation progress, manage contractors and vendors, and monitor costs.

The project demonstrates skills in **database design**, **SQL development**, and **Python integration**, with an emphasis on **real-world application** for property management.

---

## Features

- **Property and Apartment Management:** Tracks properties, apartments, and rooms, including statuses and dimensions.
- **Work Item Tracking:** Manages tasks assigned to contractors, including scheduling and cost estimation.
- **Inventory Management:** Handles material categories, unit costs, minimum order quantities, and lead times.
- **Vendor Management:** Stores vendor details, payment terms, and delivery conditions.
- **Invoice Processing:** Manages payments to contractors and vendors for materials and services.
- **Advanced Querying:** Enables complex queries for reporting and insights.

---

## Technical Details

- **Database Management System (DBMS):** SQLite
- **Programming Language:** Python
- **ER Diagram Tool:** Mermaid
- **Database Schema:** Designed with normalization to **3NF** to ensure data integrity.

---

## SQL Highlights

The database includes the following schema and operations:

### Tables
- **`Properties`**
- **`Apartments`**
- **`Rooms`**
- **`Work_Items`**
- **`Materials`**
- **`Vendors`**
- **`Material_Orders`**
- **`Invoices`**

### Key SQL Queries
1. **Total Area of Rooms per Apartment**
2. **Number of Rooms per Apartment**
3. **Materials with Unit Cost Above Average**

## Python Integration

A Python script is included to:

- **Connect to SQLite** using the `sqlite3` module.
- **Execute SQL Queries** to extract data (e.g., materials with unit cost above average).

- ## Lessons Learned

- The limitations of SQLite for user management.
- The benefits of PostgreSQL for **role-based access control (RBAC)**.
- Practical challenges in integrating database theory into real-world applications.

## Future Enhancements

- Migrate to **PostgreSQL** for advanced security features.
- Implement **role-based access control** for stakeholders.
- Develop a user-friendly **web interface** for managing the database.
