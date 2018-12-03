   # DBA ASSIGNMENT #
                          NAME - YOHANNES FASSIL
                          ID - ATR/4122/08
                          SECTION - 02

                 



***
***TABLES***
***
Tables are the basic unit of data storage in an Oracle database. A table comprises of a number of column objects and contains rows of data. Data is stored in rows and columns.tables are logical structures maintained by the database manager.

***IMPLEMENTATION***

`CREATE TABLE table_name (				
    column1 datatype,
    column2 datatype,
    column3 datatype,
   ....
);`


`CREATE TABLE new_table_name AS
    SELECT column1, column2,...
    FROM existing_table_name
    WHERE ....;`

***EXPLANATION***

In the first one the column parameters specify the names of the columns of the table. The datatype parameter specifies the type of data the column can hold (e.g. varchar, integer, date, etc.).
In the second one its copying the existing table name and gets the same column definitions.The new table will be filled with the existing values from the old table.



***INDEX***
***
An index is a set of one or more keys, each key pointing to a row in a table. The SQL optimizer automatically chooses the most efficient way to access data in tables. The optimizer takes indexes into consideration when determining the fastest access path to data. Indexes are optional structures associated with tables and clusters. You can create indexes on one or more columns of a table to speed SQL statement execution on that table. Just as the index in this manual helps you locate information faster than if there were no index, an Oracle index provides a faster access path to table data. Indexes are the primary means of reducing disk I/O when properly used.Indexes are used to retrieve data from the database very fast. The users cannot see the indexes, they are just used to speed up searches/queries.

***IMPLEMENTAION***
`
CREATE INDEX index_name
ON table_name (column1, column2, ...);
CREATE UNIQUE INDEX index_name
ON table_name (column1, column2, ...);
EXPLANATION
`
The first one creates an index with a name of index_name on the various columns we want, and duplicate values are allowed.


The second one creates an index with a name of index_name on the various columns we want,but on this one duplicate values are not allowed.
***
***View*** 
***
A view is an efficient way of representing data without the need to maintain it. A view is not an actual table and requires no permanent storage. A "virtual table" is created and used. It is also a tailored presentation of the data contained in one or more tables or other views. A view takes the output of a query and treats it as a table. Therefore, a view can be thought of as a stored query or a virtual table. You can use views in most places where a table can be used.They provide an alternative way to look at the data of one or more tables. This virtual table or view derives its values from the evaluation of a query expression in a CREATE VIEW statement. The query expression can reference base tables, other views, aliases, etc. Essentially, a view is a stored SELECT statement, of which you can retrieve the results at a later time by querying the view as though it were a table.

***IMPLEMENTAION***
`
CREATE VIEW view_name AS
SELECT column1, column2, ...
FROM table_name
WHERE condition;
`
Eg:
`
CREATE VIEW [Products Above Average Price] AS
SELECT ProductName, Price
FROM Products
WHERE Price > (SELECT AVG(Price) FROM Products);
`
`
CREATE OR REPLACE VIEW view_name AS
SELECT column1, column2, ...
FROM table_name
WHERE condition;
`
Eg;
`
CREATE OR REPLACE VIEW [Brazil Customers] AS
SELECT CustomerName, ContactName, City
FROM Customers
WHERE Country = "Brazil";
`

***EXPLANATION***

The first one creates a view with a name “view_name” and selects the selected columns from an already created table with a condition that can select a specific portion of the columns.
The second one is the same as the first one but instead of create view we use create or replace view to also create and update
***
***CURSOR***
***
A database cursor is an object used to pinpoint records in a database. Just like a typing cursor is used to alert you where your text will appear, a database cursor also shows you the specific record in a database that is being worked upon.A database cursor can be thought of as a pointer to a specific row within a query result.The pointer can be moved from one row to the next.When a database file is opened, the cursor points to the first record in the file, and using various commands the cursor can move to any location within the file. When designing a database, the developer must take care not to use too many open cursors. Each cursor uses a (admittedly small) amount of memory. However, if cursors are never closed, that is, discarded after completing their work, they can pile up in memory and cause performance problems.

***IMPLEMENTATION AND EXPLANATION***

1,First, you have to declare a cursor by using the DECLARE statement:
* `DECLARE cursor_name CURSOR FOR SELECT_statement`

2,Next, you open the cursor by using the OPEN statement. The OPEN statement initializes the result set for the cursor.
*` OPEN cursor_name;`

3,Then, you use the FETCH statement to retrieve the next row pointed by the cursor and move the cursor to the next row in the result set.
* `FETCH cursor_name INTO variables list`

4, Finally, you call the CLOSE statement to deactivate the cursor and release the memory associated with it as follows:
* `CLOSE cursor_name;`

5, When working with MySQL cursor, you must also declare a NOT FOUND handler to handle the situation when the cursor could not find any row.
* `DECLARE CONTINUE HANDLER FOR NOT FOUND SET finished = 1;`
***
***RECORD***
***
A record is composed of fields and contains all the data about one particular person, company, or item in a database. Records are composed of fields, each of which contains one item of information.A record is a set of data stored in a table, e.g., a customer record. A record in a database is an object that can contain one more values. Groups of records are then saved in a table; the table defines the data that each record may contain. In a given database, there are multiple tables, each containing multiple records.Records are composed of a group of fields, similar to the columns in a row. The ***%ROWTYPE*** attribute lets you declare a PL/SQL record that represents a row in a database table, without listing all the columns.

***IMPLEMENTATION***

`dept_rec1 departments%ROWTYPE;`

***EXPLANATION***

Assigning values to a record with a %rowtype declaration


***
***PACKAGE***
***
A package is a schema object that groups logically related PL/SQL types, variables, constants, subprograms, cursors, and exceptions. A package is compiled and stored in the database, where many applications can share its contents.A package always has a specification, which declares the public items that can be referenced from outside the package.A package specification declares public items. The scope of a public item is the schema of the package. A public item is visible everywhere in the schema. To reference a public item that is in scope but not visible, qualify it with the package name. (For information about scope, visibility, and qualification.

***IMPLEMENTATION and EXPLANATION***

 1 A simple package specification without a body
`CREATE PACKAGE trans_data AS -- body less package
‘
‘
    BEGIN
	‘
	‘
	‘
    END trans_data;`
This creates a package with no body because it doesnt declare cursors or subprograms
***
***PROCEDURE***
***
A stored procedure is a prepared SQL code that you can save, so the code can be reused over and over again.So if you have an SQL query that you write over and over again, save it as a stored procedure, and then just call it to execute it.You can also pass parameters to a stored procedure, so that the stored procedure can act based on the parameter value(s) that is passed.Stored Procedures are pre-compiled objects which are compiled for the first time and its compiled format is saved, which executes (compiled code) whenever it is called. For more about stored procedure.

***IMPLEMENTATION***
`
CREATE PROCEDURE procedure_name
AS
sql_statement
GO;
EXEC procedure_name;
`
`
Eg:
CREATE PROCEDURE SelectAllCustomers
AS
SELECT * FROM Customers
GO;
`
`
CREATE PROCEDURE procedure_name @column  
AS
sql_statement condition
GO;
EXEC procedure_name @column;
`
`
Eg:
CREATE PROCEDURE SelectAllCustomers @City nvarchar(30)
AS
SELECT * FROM Customers WHERE City = @City
GO;
EXEC SelectAllCustomers City = "London";
`

***EXPLANATION***

The first SQL statement creates a stored procedure named "SelectAllCustomers" that selects all records from a "Customers" table.
The second SQL statement creates a stored procedure that selects procedure_name

***

***FUNCTION***
***
A function is compiled and executed every time whenever it is called. A function must return a value and cannot modify the data received as parameters. Function must return a value, it can have only input parameters.A stored function (also called a user function or user-defined function) is a set of PL/SQL statements you can call by name. Stored functions are very similar to procedures, except that a function returns a value to the environment in which it is called. User functions can be used as part of a SQL expression.

***IMPLEMENTATION***
`
CREATE FUNCTION function_name(item_row IN item_type) 
  ‘
  ‘
  BEGIN
	‘
	‘
  END;
  `

***EXPLANATION***

The first one creates the function function_name on a created table and the function uses a select statement to select the data column from the row item_row.
***
***Clusters***
***
A cluster is a schema object that contains data from one or more tables, all of which have one or more columns in common. Oracle Database stores together all the rows from all the tables that share the same cluster key.

***IMPLEMENTATION***

1,`CREATE CLUSTER personnel
   (department NUMBER(4))
   SIZE 512 
   STORAGE (initial 100K next 50K);`


2, `REATE INDEX idx_personnel ON CLUSTER personnel;`


***EXPLANATION***

The first statement creates a cluster named personnel with the cluster key colunn department, a cluster size of 512 bytes, and storage parameter values.

***
***DBLINK***
***
A database link is a connection between two physical database servers that allows a client to access them as one logical database.A database link is a pointer that defines a one-way communication path from an Oracle Database server to another database server.A database link connection allows local users to access data on a remote database. For this connection to occur, each database in the distributed system must have a unique global database name in the network domain.

***IMPLEMENTATION ***

1, `REATE PUBLIC DATABASE LINK remote 
USING 'remote';`

2,`CREATE DATABASE LINK local 
   CONNECT TO hr IDENTIFIED BY hr
   USING 'local';`

***EXPLANATION***

Use the CREATE DATABASE LINK statement to create a database link.
The first statement defines a shared public database link named remote that refers to the database specified by the service name remote.
The second statement, user hr on the remote database defines a fixed-user database link named local to the hr schema on the local database:
***
***SEQUENCE***
***
A sequence is a database object that allows the automatic generation of values, such as check numbers. Sequences are ideally suited to the task of generating unique key values. Applications can use sequences to avoid possible concurrency and performance problems resulting from column values used to track numbers. The advantage that sequences have over numbers created outside the database is that the database server keeps track of the numbers generated. A crash and restart will not cause duplicate numbers from being generated The sequence generator provides a sequential series of numbers. The sequence generator is especially useful in multi-user environments for generating unique sequential numbers without the overhead of disk I/O or transaction locking.The sequence is a feature by some database products which just creates unique values. It just increments a value and returns it. The special thing about it is: there is no transaction isolation, so several transactions can not get the same value, the incrimination is also not rolled back. Without a database sequence it is very hard to generate unique incriminating numbers.


***IMPLEMENTATION and EXPLANATION***

Sequences are created by use of the CREATE SEQUENCE command.
Where sequence_name. The name you want the sequence to have. This may include the user name if created from an account with DBA privilege.
***
***TRIGGER***
***
A trigger defines a set of actions that are performed in response to an insert, update, or delete operation on a specified table. When such an SQL operation is executed, the trigger is said to have been activated. Triggers are optional and are defined using the CREATE TRIGGER statement.A trigger can include SQL and PL/SQL statements to execute as a unit and can invoke stored procedures. However, procedures and triggers differ in the way that they are invoked.

***IMPLEMENTATION and EXPLANATION***

`REATE [OR REPLACE ] TRIGGER trigger_name`- Creates or replaces an existing trigger with the trigger_name.
***
***CONSTRAINTS***
***
Constraints are used to limit the type of data that can go into a table. This ensures the accuracy and reliability of the data in the table.Within any business, data must often adhere to certain restrictions or rules. For example, an employee number must be unique. The database manager provides constraints as a way to enforce such rules.

***NOT NULL*** Constraint - his enforces a field to always contain a value,which means that you cannot insert a new record, 						                    or update a record without adding a value to this field.

***Implementation*** - `CREATE TABLE Persons (		
    				    ID int NOT NULL);`
	
***Explanation*** -  this ensures id will not accept null values when the persons table is created.

***UNIQUE*** Constraint - the UNIQUE constraint provides a guarantee for uniqueness for a column or set of columns.

***Implementation*** - `CREATE TABLE Persons (
    					ID int NOT NULL UNIQUE);`

***Explanation*** - The following SQL creates a UNIQUE constraint on the "ID" column when the "Persons" table is created.

***PRIMARY KEY****** - The PRIMARY KEY constraint uniquely identifies each record in a table.

***Implementation*** -` CREATE TABLE Persons (
    					ID int NOT NULL PRIMARY KEY);`

***Explanation ***- The following SQL creates a PRIMARY KEY on the "ID" column when the "Persons" table is created.

***FOREIGN KEY*** - A FOREIGN KEY is a key used to link two tables together.A FOREIGN KEY is a field (or collection of fields)
                    in one table that refers to the PRIMARY KEY in another table.

***Implementation*** - `CREATE TABLE Persons (
    					PersonID int FOREIGN KEY REFERENCES Persons(PersonID));`***

***Explanation*** - The following SQL creates a FOREIGN KEY on the "PersonID" column when the "Orders" table is 
                    created.

***CHECK*** - The CHECK constraint is used to limit the value range that can be placed in a column.If you define a 
              CHECKconstraint on a table it can limit the values in certain columns based on values in other columns in the row.

***Implementation*** - `CREATE TABLE Persons (
Age int CHECK (Age>=18));`

***Explanation*** - The following SQL creates a CHECK constraint on the "Age"column when the "Persons" table is created. The 				                CHECK constraint ensures that you can not have any person below 18 years.
