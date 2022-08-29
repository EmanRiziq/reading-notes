# SQL
### What is SQL database
Structured Query Language, is a language designed to allow both technical and non-technical users query, manipulate, and transform data from a relational database.

### Lesson 1 : SELECT queries 101
Select spicific column/s from mytable
```
SELECT column, another_column, …etc
FROM mytable;
```

Select all columns from mytable
```
SELECT *
FROM mytable;  
### Lesson 2 : Queries with constraints (Pt. 1)
```
Select query with constraints
```
SELECT column, another_column, …
FROM mytable
WHERE condition
    AND/OR another_condition
    AND/OR …;
Condition Table
```

### Lesson 3 : Queries with constraints (Pt. 2)
Condition Table

### Lesson 4 : Filtering and sorting Query results
*DISTINCT* keyword will blindly remove duplicate rows.
```
SELECT DISTINCT column, another_column, …
FROM mytable
WHERE condition(s);
```
```
SELECT column, another_column, …
FROM mytable
WHERE condition(s)
ORDER BY column ASC/DESC
LIMIT num_limit OFFSET num_offset;
```
### Lesson 5 : Simple SELECT Queries (review)

### Lesson 6 : Multi-table queries with JOINs
```
SELECT column, another_table_column, …
FROM mytable
INNER JOIN another_table 
    ON mytable.id = another_table.id
WHERE condition(s)
ORDER BY column, … ASC/DESC
LIMIT num_limit OFFSET num_offset;
```

### Lesson 7: OUTER JOINs
```
SELECT column, another_column, …
FROM mytable
INNER/LEFT/RIGHT/FULL JOIN another_table 
    ON mytable.id = another_table.matching_id
WHERE condition(s)
ORDER BY column, … ASC/DESC
LIMIT num_limit OFFSET num_offset;
```

### Lesson 8: A short note on NULLs
```
SELECT column, another_column, …
FROM mytable
WHERE column IS/IS NOT NULL
AND/OR another_condition
AND/OR …;
```
