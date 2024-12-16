# Library Management System Database Project

This project is a comprehensive database solution designed to manage the operations of a library, including book inventory, member management, loan tracking, and overdue fine calculations. The system is built using SQL and relational database principles to ensure data consistency, efficiency, and scalability.

## Features

### 1. Database Design
- **Entity-Relationship Diagram (ERD)**: Models key entities such as:
  - **Books**: Stores information like ISBN, title, author, publisher, and availability.
  - **Members**: Tracks member details such as name, contact info, and membership date.
  - **Loans**: Records borrowing details like loan date, due date, and return status.
  - **Staff**: Manages administrative access for library operations.
- **Normalization**: Data is structured in 3rd Normal Form (3NF) to avoid redundancy and maintain data integrity.

### 2. Core Functionalities
- **Inventory Management**:
  - Add, update, and remove books.
  - Search books by title, author, or category.
- **Member Management**:
  - Register new members and update their details.
  - Retrieve borrowing history for individual members.
- **Loan Processing**:
  - Issue and return books.
  - Calculate and track overdue fines.
- **Reporting**:
  - Generate reports for:
    - Most borrowed books.
    - Overdue loans.
    - Active and inactive members.

### 3. Technical Implementation
- **SQL Features Used**:
  - Tables, Primary Keys, and Foreign Keys for relational mapping.
  - Joins, Subqueries, and Aggregates for complex queries.
  - Stored Procedures and Triggers for automation.
- **Performance Optimization**:
  - Indexing frequently queried fields.
  - Efficient query design for large datasets.


