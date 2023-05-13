# StrawDB 2.0
-------
StrawDB 2.0 is the new and improved Database management system. 

This project aims to develop a basic database system with AVL tree storage and SQL parsing capabilities.


Basic Syntax of the database

1. CREATE TABLE

Syntax: 
```
CREATE TABLE table_name (column1 datatype1, column2 datatype2, column3 datatype3, ...);
```

Description:
This command is used to create a new table in the database with specified column names and datatypes.

Example:
```
CREATE TABLE employees (id INT, name VARCHAR(256), age INT, is_employed BOOLEAN);
```

2. INSERT INTO

Syntax:
```
INSERT INTO table_name (column1, column2, column3, ...) VALUES (value1, value2, value3, ...);
```

Description:
This command is used to insert a new row of data into the specified table. The values should be provided in the same order as the columns specified in the table.

Example:
```
INSERT INTO employees (id, name, age, is_employed) VALUES (1, 'John', 32, true);
```

3. SELECT

Syntax:
```
SELECT column1, column2, column3, ... FROM table_name;
```

Description:
This command is used to retrieve data from the specified table. The columns to be retrieved should be listed after the SELECT keyword, and the table name should be specified after the FROM keyword.

Example:
```
SELECT name, age FROM employees;
```

4. UPDATE

Syntax:
```
UPDATE table_name SET column1 = value1, column2 = value2, ... WHERE condition;
```

Description:
This command is used to update existing data in the specified table. The SET keyword is used to specify the columns to be updated and their new values. The WHERE keyword is used to specify the condition for which rows to update.

Example:
```
UPDATE employees SET age = 33 WHERE name = 'John';
```

5. DELETE

Syntax:
```
DELETE FROM table_name WHERE condition;
```

Description:
This command is used to delete data from the specified table. The WHERE keyword is used to specify the condition for which rows to delete.

Example:
```
DELETE FROM employees WHERE age > 30;
```

6. DROP TABLE

Syntax:
```
DROP TABLE table_name;
```

Description:
This command is used to delete the specified table from the database.

Example:
```
DROP TABLE employees;
```
