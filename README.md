# SQL_LOG
HELLO!This is my SQL skillset!
Recording What I learnd about SQL.

## DATABASE
#### CREATE DATABASE
CREATE DATABASE database_name
#### ALTER DATABASE
ALTER DATABASE database_name RENAME TO new_name
#### DEOP DATABASE
DROP DATABASE database_name

## TABLE
#### CREATE TABLE
CREATE TABLE table_name (
    column1 datatype,
    column2 datatype,
    column3 datatype,....);
#### DROP TABLE
DROP TABLE table_name;
#### ALTER TABLE
Add column:ALTER TABLE table_name ADD column_name datatype;<br/>
Drop column:ALTER TABLE table_name DROP COLUMN column_name;<br/>
Rename column: ALTER TABLE table_name RENAME COLUMN old_name To new_name;<br/>
Change column datatype: ALTER TABLE table_name MODIFY COLUMN column_name datatype;<br/>
#### CONSTRAINTS
Constraints can be specified when the table is created with the CREATE TABLE statement, or after the table is created with the ALTER TABLE statement.
<br/>
CREATE TABLE table_name (<br/>
    column1 datatype constraint,<br/>
    column2 datatype constraint,<br/>
    column3 datatype constraint,...);<br/>
<br/>
<br/>
The following constraints are commonly used in SQL:
<br/>
NOT NULL: Ensures that a column cannot have a NULL value<br/>
UNIQUE: Ensures that all values in a column are different<br/>
PRIMARY KEY: A combination of a NOT NULL and UNIQUE. Uniquely identifies each row in a table<br/>
FOREIGN KEY: Prevents actions that would destroy links between tables<br/>
CHECK: Ensures that the values in a column satisfies a specific condition<br/>
DEFAULT: Sets a default value for a column if no value is specified<br/>
#### INSERT VALUE INTO TABLE
INSERT INTO table_name (column1, column2, column3, ...)VALUES (value1, value2, value3, ...);
#### UNDATE TABLE
UPDATE table_name
SET column1 = value1, column2 = value2, ...
WHERE condition;
#### DELETE
DELETE FROM table_name WHERE condition;

## SELECT QUERY COMMANDS
### SELECT
SELECT column1, column2, ...FROM table_name;<br/>
SELECT * FROM table_name;<br/>
SELECT COUNT() FROM table_name;<br/>
SELECT DISTINCT() FROM table_name;<br/>
### SELECT...WHERE
SELECT column1, column2, ...<br/>
FROM table_name <br/>
WHERE condition;
#### WHERE condition:
AND: WHERE condition1 AND condition2 AND condition3 ...;<br/>
OR: WHERE condition1 OR condition2 OR condition3 ...;<br/>
NOT:WHERE NOT condition;<br/>
OTHERS:=,>,<,>=,<=,<>,BETWEEN...AND...,LIKE,IN
### SELECT...ORDER BY...<br/>
SELECT column1, column2, ...<br/>
FROM table_name<br/>
ORDER BY column1, column2, ... ASC|DESC;<br/>

## SQL FUNCTIONS









   






