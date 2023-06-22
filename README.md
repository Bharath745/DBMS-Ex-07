# Exp 20 Aggregate function in SQL.
## AIM:
To write a sql query to perform Aggregate function in SQL.
## PROCEDURE:
### STEP 1:
create database AGGREGATE_FUNCTION.
### STEP 2:
create table DETAILS with ID and value.
### STEP 3:
Insert Value to the table DETAILS.
### STEP 4:
Perform Aggregate functions like SUM(),COUNT(),AVG().
## PROGRAM:
```sql
CREATE DATABASE AGGREGATE_FUNCTION;
USE AGGREGATE_FUNCTION;
CREATE TABLE DETAILS (
  ID INT PRIMARY KEY,
  Value INT
);
INSERT INTO DETAILS (ID, Value) VALUES
(1, 10),
(2, 20),
(3, 30),
(4, 40),
(5, 50);
SELECT * FROM DETAILS;
SELECT SUM(Value) FROM DETAILS;
SELECT COUNT(*) FROM DETAILS;
SELECT AVG(Value) FROM DETAILS;
```
## OUTPUT:
![image](https://github.com/Bharath745/DBMS-Ex-07/assets/94508354/c408572e-a9f1-4559-9403-7f767635b8b3)

![image](https://github.com/Bharath745/DBMS-Ex-07/assets/94508354/cdfe29ef-f9d5-4083-94a0-7037f4fccaaa)

![image](https://github.com/Bharath745/DBMS-Ex-07/assets/94508354/f1c336cc-9055-4136-ade6-4fc0f6f71348)

![image](https://github.com/Bharath745/DBMS-Ex-07/assets/94508354/e32dc46f-043a-4c93-a164-5a140fbfeb61)


## RESULT:
A sql query to perform Aggregate function in SQL has been executed.
