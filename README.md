# SQL-Review
code snippets reminding me of sql syntax.

```sql
-- This is a single-line comment
/* This is 
   a multi-line comment */
SELECT * FROM employees LIMIT 10;
```
# Select
```sql
SELECT <COLUMNS> FROM TABLE_1 WHERE <predicate> ;
```
# Distinct
returns unique rows
# Count
counts the number of rows
```sql
SELECT COUNT(DISTINCT customer_id) AS unique_customers
FROM orders;
```
# Limit
limits the number of rows
# Order By: Sort

```sql
SELECT column1, column2, ...
FROM table_name
ORDER BY column1 [ASC|DESC], column2 [ASC|DESC], ...;
```
