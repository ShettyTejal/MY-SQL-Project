# MY-SQL-Project
**E-commerce Online Store Project**

Project Overview

This project is focused on creating an E-commerce Online Store database using MySQL. Given the increasing trend in online shopping, I have designed and implemented a relational database that manages key entities involved in the online store process. The database includes 5 main tables: Employees, Customers, Orders, Products, and Sales. These tables are interconnected through foreign key relationships, ensuring data integrity and enabling easy access to relevant information.

**The Key Relationships:**

The Orders table connects to both Employees (salesperson) and Customers (buyers) via foreign keys.

The Sales table is connected to the Products table, helping track which products are being sold and in what quantity.

This project demonstrates the use of SQL commands, constraints, aggregate functions, joins, and subqueries to manage and retrieve data from the database.

**Tables in the Database**
The Online_Store database consists of the following 5 tables:

**Employees:** Stores employee details.
**Columns:** Employee_Id, EmpName, Email, Department, Hire_date

**Customers:** Stores customer information.
**Columns:** Customer_id, Name, Email, Address, Contact_number

**Orders:** Stores order information, linking customers to employees (salespersons).
**Columns:** Order_id, Customer_id, Employee_id, Order_date, Status

**Products:** Stores product information available in the store.
**Columns:** Product_id, Name, Description, Price

**Sales:** Tracks sales transactions, linking products to the sales made.
**Columns:** Sale_id, Product_id, Quantity, Sale_date

This project demonstrates the use of various SQL operations, Basic Queries,Aggregate Functions,Joins,Subqueries.

**Conclusion**
This Online_Store project demonstrates how to create and manage a relational database for an e-commerce system using MySQL. The use of multiple tables, foreign keys, and SQL functions ensures the efficient handling of data, providing a seamless shopping experience. This project can be further extended by implementing features such as user authentication, inventory management, and advanced reporting.

