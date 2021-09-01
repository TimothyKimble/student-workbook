# Welcome to SQL (Day 3)

## In a SQL table, what is the difference between information in a row and information in a column?
The information in a row is based on the data that a certain object has, as opposed to columns which are the available data types that all different objects possess. 
## Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.
CREATE TABLE characters (
  id int NOT NULL primary key AUTO_INCREMENT comment 'primary key',
  name varchar(255) NOT NULL comment 'character name',
  age INT NOT NULL comment 'character age'
  description varchar(255) NOT NULL comment 'character description',
) default charset utf8 comment '';

## What is the difference between the following statements:
The difference between DELETE FROM and DROP TABLE is as follows. DELETE FROM is used when you want to remove the rows from the table you have created. Meanwhile DROP TABLE allows you to remove or delete the whole table from your MySQL Database. 


## Afternoon Challenge A Knight's Tale
https://github.com/TimothyKimble/knightTale