# Data Engineer Interview

## Databases
1. What is an index?
<br>Is a data structure that improves the speed of data retrieval operations on a database table at the cost of additional writes and storage space to maintain the index data structure.

2. What kind of joins exist?
- Inner join
- Left join
- Right join
- Full outer join

3. Differences between OLTP and OLAP?
- OLTP: Online Transaction Processing. This system captures and maintains transaction in a database. Each transaction involves individual database records made up of multiple fields or columns. In OLTP the emphasis is on fast processing, because OLTP databases are read, and updated frequently.
- OLAP: Online Analytical Processing. Applies complex queries to large amounts of historical data, aggregated from OLTP databases and other sources, for data mining, analytics and business intelligence projects. The emphasis is on response time to these complex queries.

4. What is a stored procedure and difference with functions?
- Stored procedure: A stored procedure is a prepared SQL code that you can save, so the code can be reused over and over again. You can pass parameters to a stored procedure, so that stored procedure can act based on the parameter values that are passed.
- A function must return a value but in stored procedure it is optional. Even a procedure can return zero values o n values. Functions can have only input parameters for it whereas procedures can have input or output parameters. Functions can be called from procedure whereas procedures cannot be called from a function.

5. Differences between DML and DDL?
- DDL: Data definition language which is used to define data structures. Create table, alter table. It is used to create database schema and can be used to define some constraints as well. Does not use clause WHERE in its statement.
- DML: Data Manipulation Language which is used to manipulate data itself. Insert, Update, delete. It is used to add, retrieve or update the data.

6. What is the difference between truncate and delete?
<br>Delete is a DML and truncate is a DDL. We can roll back a delete but we can't roll back a truncate. Truncate is fast than delete statement because doesn't use WHERE clause.

7. What is the difference between window functions and aggregate functions?
- Aggregate functions: Use group by to define a set of columns. Collapses individual rows into one summary row.
- Window functions: Use over() to define a set of rows. Keeps individual rows and adds a summary column.

8. What are the advantages of CTEs?
- Code maintainability
- It will not store the definition in metadata.
- Allows write recursive queries because can reference itself.

9. What is a transaction?
<br>Is a sequence of SQL statements that are commited or roll back as a unit.

10. What does ACID mean in databases?
- Atomicity: guarantees that each transaction is treated as a single unit, which either succeeds completely, or fails completely.
- Consistency: Ensures that a transaction can only bring the database from one valid state to another, maintaining database invariant. Ant data written to the database must be valid according to all defined rules, including constraints, cascades, triggers, and any combination thereof.
- Isolation: The intermediate state of a transaction is invisible to other transactions. As a result, transactions that run concurrently appear to be serialized.
- Durability: Guarantees that once a transaction has been commited, it will remain commited even in the case of a system failure.


## Python and OOP

1. What is the difference between a list and a tuple?
- A list is a mutable data structure while a tuple is an inmutable one. A mutable object in Python has the ability to change its values.
- Lists are dynamic: you can add items to them or override and remove existing ones.
- Tuples are fixed-size: they don't have an append or an extend method. You cannot remove items from them either.

2. What is the difference between a class method and a static method?
- A static method is a method that knows nothing about the class and just deals with the parameters. A static method can be either called on the class or any of its instances.
- A class method works with the class since its parameter is always the class itself.

3. What is the difference between *args and **kwargs?
<br>We use *args and **kwargs as an argument in a function when we are unsure about the number of arguments to pass in the functions. It allows function to take variable length argument.
- *args: passes variable number of non-keyworded arguments and on which operation of the tuple can be performed.
- **kwargs: passes variable number of keyword arguments dictionary to function on which operation of a dictionary can be performed.

4. What is a comprehension list?
<br>Offers a shorter syntax when you want to create a new list based on the values of an existing list.

5. What is a lambda function?
<br>It is an anonymous function or a function having no name. It is a small and restricted function having no more than one line. Just like a normal function, a Lambda function can have multiple arguments with one expression.

6. Why Python is so popular?
- Easy to use
- Interpreted language
- Dynamically typed
- Free and open source
- Extensive support for libraries

7. What is the difference between Python Arrays and lists?
<br>Arrays and lists, in Python, have the same way of storing data. But, arrays can hold only a single data type elements whereas lists can hold any data type elements.

8. What is inheritance?
<br>Inheritance allows One class to gain all the members of another class. Inheritance provides code reusability, makes it easier to create and maintain an application. The class from which we are inheriting is called super-class and the class that is inherited is called a derived/child class.

9. 

## Data Engineering

1. Data Lake vs Data Warehouse

2. What are the 



## Dataops




## Cloud (AWS)



## Orchestation (Airflow)
