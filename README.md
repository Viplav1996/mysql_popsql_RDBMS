# mysql_popsql_RDBMS

This repo is for steps reagrding installing and using popsql together for managing Database Management System DBMS.

Introduction:
Collections of realted information forms DBMS.


Example: Contacts in phonebook, Shopping List, To-do list etc.


Requirement:
Need of DBMS arise when the quantity of handling data exceeds, eg amazon.

Types of Database:
1. Relational-DBMS
2. Non-Relational-DBMS

1. Relational-DBMS: Table has colums and rows. Eg Excel Spreadsheet. Normally, they are written using SQL(Structured Query Language). SQL may vary from one software to another but the task perfromed is mostly similar. Few more examples of RDBMS are MySQL(mostly used), Oracle, postgreSQL, mariaDB etc. SQL is used to perfrom CRUD operations so SQL is a hybrid language, few thaks which can be accomplished by it are: a.) Query b.) Defination(define schema) c.) Control d.) Data Maipulation 

2. Non-Relational-DBMS: The data consists of unique id's which could be in any format. E.g. key-value, documents(JSON, XML), Graphs, Flexible Tables etc. SOme of the popular NRDBMS are MongoDB, DynamoDB etc

Query: When a request is made for specific data/information, that's called a query.

### Relational Database Management System

RDMS consists of two major components:
1. Tables(Columns- single attribute and Rows- Indiviual Entry)  2. Keys(Relationship between tables)

There are various types of keys depending upon the relationship to be established between diferent tables:
1. Primary Key(Not Null + Unique): Only one and unique value in each row. E.g id, email etc
  a)Natural Key: resembelance to the real world
  b)Surrage Key: no resembelance to the real world
2. Foreign Key: It is key which stores the primary key value in another table(used to define relation between tables).
3. Composite Key: Key which is made of 2 columns combined together.
