# SQL Queries

### Question:
Query all columns for all American cities in the `CITY` table with populations larger than 100,000. The `CountryCode` for America is `USA`.

### SQL Query:
```sql
SELECT * FROM CITY WHERE CountryCode = 'USA' AND Population > 100000;
