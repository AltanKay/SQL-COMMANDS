📊 SQL: Working with Multiple Tables

This document summarizes key concepts learned about relationships between tables in relational databases and how to query data across them using SQL.

🧩 Key Concepts

🔗 JOIN

Combines rows from two or more tables based on a related column (join condition).

Only returns rows where the condition is true.


↪️ LEFT JOIN

Returns all rows from the left table.

Fills in with NULL for rows in the right table that don't meet the join condition.


🆔 Primary Key

A column that uniquely identifies each row in a table.

Must contain unique and non-null values.


🔑 Foreign Key

A column that refers to the primary key of another table.

Used to establish a relationship between tables.


✖️ CROSS JOIN

Produces the Cartesian product of two tables.

Combines every row of the first table with every row of the second.


📚 UNION

Combines results from two or more SELECT statements.

Removes duplicate rows by default.

Use UNION ALL to include duplicates.


🧾 WITH (Common Table Expressions - CTEs)

Lets you define temporary named result sets.

Can make complex queries easier to read and modular.
---
✅ This knowledge helps in querying and organizing data effectively when dealing with normalized databases that separate data across multiple tables.
