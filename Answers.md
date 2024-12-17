


---

1. State and Explain the components of a DBMS (Database Management System)
A DBMS has the following key components:

Hardware: The physical devices (e.g., servers, storage, and computers) used to store and run the database system.

Software: The DBMS software that allows users to define, create, manipulate, and control the database.

Data: Raw facts and figures that are processed and stored in the database to provide meaningful information.

Database Schema: The logical structure or blueprint of the database that defines how data is organized (tables, relationships, etc.).

Query Processor: Translates user queries into low-level instructions that the database engine can execute.

Database Engine: The core component that manages data storage, retrieval, and optimization of performance.

Users: Individuals or applications that interact with the database (e.g., database administrators, developers, and end users).



---

2. What is a relational database? Give 4 examples.
A relational database is a type of database that organizes data into tables (relations) consisting of rows and columns. Each row represents a record, and columns represent attributes. Relationships between tables are established using keys.

Examples:

1. MySQL


2. PostgreSQL


3. Oracle Database


4. Microsoft SQL Server




---

3. State and Explain three classifications of SQL
SQL is classified into three main categories:

DDL (Data Definition Language): Used to define or modify database structures. Examples include CREATE, ALTER, DROP, and TRUNCATE.

DML (Data Manipulation Language): Used to manipulate data in the database. Examples include INSERT, UPDATE, DELETE, and SELECT.

DCL (Data Control Language): Used to control access to the database. Examples include GRANT and REVOKE.



---

4. What is the difference between a Primary Key and a Foreign Key?

Primary Key: A column (or combination of columns) in a table that uniquely identifies each record. It does not allow NULL values.

Foreign Key: A column in one table that establishes a relationship with the primary key of another table. It ensures referential integrity between tables.


Example:

In a Students table, StudentID can be the Primary Key.

In a Grades table, StudentID can be the Foreign Key referencing Students.StudentID.



---

5. What is an Entity-Relationship Diagram (ERD)?
An ERD is a graphical representation of entities (objects), their attributes, and the relationships between them in a database system. It helps to design and visualize the database structure.

Components of ERD:

Entities: Represented as rectangles (e.g., "Customer", "Order").

Attributes: Represented as ovals (e.g., "CustomerID", "Name").

Relationships: Represented as diamonds showing associations between entities.



---

6. What are the advantages of relational databases?
Relational databases offer the following advantages:

1. Data Integrity: Enforces data accuracy and consistency using constraints like Primary Keys and Foreign Keys.


2. Flexibility: Data can be updated, added, or removed without disrupting the system.


3. Scalability: Can handle large volumes of data and support growth.


4. Security: Provides access control and authentication mechanisms.


5. Query Optimization: Supports SQL queries to efficiently retrieve data.


6. Data Relationships: Supports complex relationships between tables.




---

7. State four types of data types used to store data in tables.

1. INT: Used to store integer (whole number) values.


2. VARCHAR: Used to store variable-length strings or text.


3. DATE: Used to store date values (e.g., YYYY-MM-DD).


4. DECIMAL/NUMERIC: Used to store fixed-point numbers (e.g., prices).




---

8. What is the purpose of a database management system (DBMS)?
The purpose of a DBMS is to:

Store, retrieve, and manage data efficiently.

Provide data security and ensure authorized access.

Ensure data integrity by enforcing rules and relationships.

Allow concurrent data access while maintaining consistency.

Facilitate data organization, querying, and reporting.

Support data backup and recovery mechanisms.



---


