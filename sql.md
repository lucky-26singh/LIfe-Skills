# Introduction to SQL

SQL (Structured Query Language) is a standard programming language used for managing and manipulating relational databases. It allows users to interact with data stored in tables by performing various operations such as querying, updating, and deleting data.

### Key Features of SQL:

* **Data Retrieval:** Use the SELECT statement to query and retrieve specific data from a database.

* **Data Manipulation:** Perform operations like INSERT, UPDATE, and DELETE to manage data.

* **Data Definition:** Create and modify database structures using CREATE, ALTER, and DROP commands.

* **Data Control:** Manage access and permissions with GRANT and REVOKE commands.

### Common SQL Statements:

* **SELECT:** Retrieve data from one or more tables.

     Example : SELECT * FROM employees;


* **INSERT:** Add new records to a table.

  Example: INSERT INTO employees (name, position) VALUES ('John Doe', 'Manager');

* **UPDATE:** Modify existing records in a table.

   Example: UPDATE employees SET position = 'Senior Manager' WHERE name = 'John Doe';
* **DELETE:** Remove records from a table.

   Example: DELETE FROM employees WHERE name = 'John Doe';

###   Type of SQL language :

  1. *Data Query Language (DQL)*
  2. *Data Manipulation Language (DML)*
  3. *Data Definition Language (DDL)*
  4. *Data Control Language (DCL)*
  5. *Transaction Control Language (TCL)*

**Data Constraints :**
   Ensure data integrity with constraints like PRIMARY KEY,FOREIGN KEY, UNIQUE, NOT NULL, and CHECK.
  

 **Joins :**

    Combine data from multiple tables based on related columns.
    Examples:

    SELECT orders.id, customers.name 
    FROM orders 
    INNER JOIN customers ON orders.customer_id = customers.id;

 **Aggregate Functions :**

    Perform calculations on data, like sums or averages.
    
  ### Advantages of SQL:

  1.  **Ease of Use:** Simple syntax for managing complex queries.

  2. **Standardized:** Widely adopted across relational database 
    systems (e.g., MySQL, PostgreSQL, SQLite, Oracle DB, Microsoft SQL Server).

  3. **Powerful:** Handles complex data retrieval and 
    transformation efficiently.

  4. **Flexibility:** Can work with large datasets and supports advanced analytics.


**Refrences**
     https://youtu.be/hlGoQC332VM?si=iIrAkmm69y25LrpU
     
