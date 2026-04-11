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
Execution of various queries including sorting, filtering, and counting.

![Query Result 1](queryresult1.png)
![Query Result 1](queryresult1(2).png)
![Query Result 1](queryresult1(3).png)
![Query Result 2](queryresult2.png)
![Query Result 3](queryresult3.png)
![Query Result 4](queryresult4.png)
![Query Result 5](queryresult5.png)
![Query Result 6](queryresult6.png)
![Query Result 7](queryresult7.png)
![Query Result 8](queryresult8.png)
![Query Result 9](queryresult9.png)
![Query Result 10](queryresult10.png)
![Query Result 11](queryresult11.png)
![Query Result 12](queryresult12.png)
![Query Result 13](queryresult13.png)
![Query Result 14](queryresult14.png)
![Query Result 15](queryresult15.png)

---

