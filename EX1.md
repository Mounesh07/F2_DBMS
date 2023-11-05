# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

## AIM:
To create a student database and execute DDL queries using SQL.


## DDL (Data Definition Language)
<div align="justify">
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
</div>
 
## List of DDL commands: 
<div align="justify">
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
DROP: This command is used to delete objects from the database.
ALTER: This is used to alter the structure of the database.
TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
RENAME: This is used to rename an object existing in the database.
</div>

## Query:
### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.

### SQL QUERY: 
create table student(rollno char(5), name varchar(20), age char(5), address varchar(100), phoneno char(15));

### OUTPUT:
![271910266-6ba921dc-a3e5-4bcf-8e35-d6fc0831922b](https://github.com/Aravindsamy04/F2_DBMS/assets/113497037/5cf8c268-8ae9-4b26-94d1-61fdc5daab53)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 

ALTER TABLE student
ADD department varchar(30);
### OUTPUT:
![271910336-e62e635f-3c55-4a18-babb-a7bb6e78dcf2](https://github.com/Aravindsamy04/F2_DBMS/assets/113497037/2235c3ea-53fe-4af5-a672-70e886c6ba42)


### 3) Drop the student table
 
### SQL QUERY: 

drop table student;
### OUTPUT:
![271910378-01dbd2bd-e9ab-4d9a-8be9-b8157330924b](https://github.com/Aravindsamy04/F2_DBMS/assets/113497037/54c111e9-99bf-456e-ae9f-49abd21c08d1)


### 4) Delete the student table using truncate keyword

### SQL QUERY: 
truncate table student;

### OUTPUT:
![271910572-a4b3b48a-f720-4eed-a776-2b47f024ca91](https://github.com/Aravindsamy04/F2_DBMS/assets/113497037/2b9fdaec-1cdf-4abd-9cc3-8f3b9ca2ba97)



### 5) Rename the student table to mystudent

### SQL QUERY: 
alter table student
rename to mystudent;

### OUTPUT:
![271910625-e2f4e148-4f54-401b-89c7-4c192eb48a49](https://github.com/Aravindsamy04/F2_DBMS/assets/113497037/dab9328b-8f37-4936-8f63-75ea6260b1c1)
### RESULT:
Hence successfully created a student database and execute DDL queries using SQL.
