# SQL Library Management System: Schema Design & Data Analysis

This project demonstrates the creation of a **Library Management System** using MySQL. It covers database schema design with strict constraints, table relationships, and complex data retrieval queries.

## Project Overview
The objective is to manage library operations efficiently by ensuring data integrity through Primary Keys, Foreign Keys, and Check constraints.

## Database Schema
The database `library_query_lab` consists of three tables:
- **MEMBER:** Stores member details with age validation (Age >= 12).
- **BOOK:** Tracks inventory, pricing, and availability status.
- **BORROW:** Manages the relationship between members and borrowed books.

## Key SQL Features Applied
- **Constraints:** `PRIMARY KEY`, `FOREIGN KEY`, `NOT NULL`, `UNIQUE`, `CHECK`, and `DEFAULT`.
- **Querying:** Pattern matching (`LIKE`), Range filtering (`BETWEEN`), and Set membership (`IN`).
- **Analytics:** Data aggregation (`COUNT`, `AVG`, `MIN/MAX`) and data grouping (`GROUP BY`).

---

## 📸 Implementation & Screenshots

### 1. Database & Table Creation
Defined the schema with all required constraints to ensure data reliability.
![Table Creation](table1.png).
![Table Creation](table2.png).
![Table Creation](table3.png).

### 2. Data Insert
Inserted 8 members, 8 books, and 10 borrow records to simulate a real-world dataset.
![Data Insertion](insertdata.png)

### 3. Data Retrieval & Analysis
Execution of various business logic queries including sorting, filtering, and counting.

![Query Result 1]()
![Query Result 2](Screenshot%202026-04-11%20060449.png)

#### Pattern Matching & Logical Filters:
![Query Result 3](Screenshot%202026-04-11%20060513.png)
![Query Result 4](Screenshot%202026-04-11%20060538.png)

#### Statistical Analysis & Aggregation:
![Query Result 5](Screenshot%202026-04-11%20061052.png)
![Query Result 6](Screenshot%202026-04-11%20061553.png)

#### Inventory and Member Activity Tracking:
![Query Result 7](Screenshot%202026-04-11%20062527.png)
![Query Result 8](Screenshot%202026-04-11%20062643.png)

---

