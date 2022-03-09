## SQL Interview Questions

### What is SQL?
SQL stands for Structured Query Language. It is the standard language for relational database management systems. It is especially useful in handling organized data comprised of entities (variables) and relations between different entities of the data.

### What are the uses of SQL?
1. It helps us to manage the data efficiently.
2. Allows us to create databases.
3. Allows us to update the table by insertions and deletions of data.
4. Provides us with data security and integrity.
5. Compatible with almost all technologies using various packages and plugins.

### What is the difference between SQL and MySQL?
SQL is a standard language for retrieving and manipulating structured databases. On the contrary, MySQL is a relational database management system, like SQL Server, Oracle or IBM DB2, that is used to manage SQL databases.

### What is Database?
A database is an organized collection of data, stored and retrieved digitally from a remote or local computer system. Databases can be vast and complex, and such databases are developed using fixed design and modeling approaches.

### What is DBMS?
DBMS stands for Database Management System. DBMS is a system software responsible for the creation, retrieval, updation, and management of the database. It ensures that our data is consistent, organized, and is easily accessible by serving as an interface between the database and its end-users or application software.

### What is RDBMS? How is it different from DBMS?
RDBMS stands for Relational Database Management System. The key difference here, compared to DBMS, is that RDBMS stores data in the form of a collection of tables, and relations can be defined between the common fields of these tables. Most modern database management systems like MySQL, Microsoft SQL Server, Oracle, IBM DB2, and Amazon Redshift are based on RDBMS.

### What is the full form of ACID property?
The ACID property is integral to all the commercial databases.
ACID stands or Atomicity, Consistency, Isolation and Durability.
When any database follows all these parameters, it becomes fit for any commercial application.

### What is a Query?
A query is any statement we execute using SQL as the language on our database to get the results.
The query helps us to define what data we require. In the case of SQL, we only need to specify what output we require.

### What are Tables and Fields?
A table is an organized collection of data stored in the form of rows and columns. Columns can be categorized as vertical and rows as horizontal. The columns in a table are called fields while the rows can be referred to as records.

### What is the difference between a database and a table?
A database is the collection of various tables consisting of data from various resources.
Whereas a table is a single unit located inside a database which is the primary source of data storage.

### What are Constraints in SQL?
Constraints are used to specify the rules concerning data in the table. It can be applied for single or multiple fields in an SQL table during the creation of the table or after creating using the ALTER TABLE command. The constraints are:
**NOT NULL** - Restricts NULL value from being inserted into a column.
**CHECK** - Verifies that all values in a field satisfy a condition.
**DEFAULT** - Automatically assigns a default value if no value has been specified for the field.
**UNIQUE** - Ensures unique values to be inserted into the field.
**INDEX** - Indexes a field providing faster retrieval of records.
**PRIMARY KEY** - Uniquely identifies each record in a table.
**FOREIGN KEY** - Ensures referential integrity for a record in another table.

### What is a Primary Key?
The PRIMARY KEY constraint uniquely identifies each row in a table. It must contain UNIQUE values and has an implicit NOT NULL constraint.
A table in SQL is strictly restricted to have one and only one primary key, which is comprised of single or multiple fields (columns).
```CREATE TABLE Students (   /* Create table with a single field as primary key */
   ID INT NOT NULL
   Name VARCHAR(255)
   PRIMARY KEY (ID)
);

CREATE TABLE Students (   /* Create table with multiple fields as primary key */
   ID INT NOT NULL
   LastName VARCHAR(255)
   FirstName VARCHAR(255) NOT NULL,
   CONSTRAINT PK_Student
   PRIMARY KEY (ID, FirstName)
);

ALTER TABLE Students   /* Set a column as primary key */
ADD PRIMARY KEY (ID);
ALTER TABLE Students   /* Set multiple columns as primary key */
ADD CONSTRAINT PK_Student   /*Naming a Primary Key*/
PRIMARY KEY (ID, FirstName);```

