#### Advanced SQL Queries – Commercial Database

### Project Overview
This project focuses on practicing **advanced SQL querying techniques** using a predefined commercial database schema.  
The database models real‑world business data involving customers, orders, employees, suppliers, products, and categories.

The goal is to demonstrate proficiency in:
- Complex filtering
- Joins and subqueries
- Aggregation and grouping
- Conditional logic (CASE)
- Date and time manipulation



### Database Schema
The database contains the following tables:

- **CATEGORIES** (CATEGORY_CODE, CATEGORY_NAME, DESCRIPTION)
- **CUSTOMERS** (CUSTOMER_CODE, COMPANY, ADDRESS, CITY, POSTAL_CODE, COUNTRY, PHONE, FAX)
- **ORDERS** (ORDER_NUMBER, CUSTOMER_CODE, EMPLOYEE_NUMBER, ORDER_DATE, SHIP_DATE, SHIPPING_COST)
- **ORDER_DETAILS** (ORDER_NUMBER, PRODUCT_REF, UNIT_PRICE, QUANTITY, DISCOUNT)
- **EMPLOYEES** (EMPLOYEE_NUMBER, REPORTS_TO, LAST_NAME, FIRST_NAME, POSITION, TITLE, BIRTH_DATE, HIRE_DATE, SALARY, COMMISSION)
- **SUPPLIERS** (SUPPLIER_NUMBER, COMPANY, ADDRESS, CITY, POSTAL_CODE, COUNTRY, PHONE, FAX)
- **PRODUCTS** (PRODUCT_REF, PRODUCT_NAME, SUPPLIER_NUMBER, CATEGORY_CODE, QUANTITY, UNIT_PRICE, UNITS_IN_STOCK, UNITS_ON_ORDER, UNAVAILABLE)



### Technologies Used
- SQL (T‑SQL compatible)
- Relational Database Concepts
- Aggregate & Analytical Queries



### Files in This Repository
- `commercial.sql` → Database creation & data population script
- `advanced_queries.sql` → Solutions to all required SQL queries
- `README.md` → Project documentation



###  Key Learning Outcomes
- Writing advanced SELECT queries
- Using JOINs and nested subqueries
- Applying GROUP BY and HAVING clauses
- Handling NULL values correctly
- Working with dates and conditional logic



## Author
**Blark Tina**
