# SQL

`The bread and butter of a Data Professional`

---

## Interview Questions

1. **What are SQL Dialects?**

- MSQL Server, PostgreSQL, MySQL, SQLite, T-SQL, Oracle, and MongoDB

2. **What are the different types of SQL Commands?**

- Data Definition Language (DDL)
  - to define and modify the structure of db
  - `CREATE`, `ALTER TABLE`, `DROP`, `TRUNCATE`, `ADD COLUMN`
- Data Manipulation Language (DML)
  - to access, manipulate, and modify data in a db
  - `UPDATE`, `DELETE`, `INSERT`
- Data Control Language (DCL)
  - to control user access to the data in db, and give or revoke privileges to a specific user
  - `GRANT`, `REVOKE`
- Transaction Control Language (TCL)
  - to control transactions in a db
  - `COMMIT`, `SET TRANSACTON`, `ROLLBACK`, `SAVEPOINT`
- Data Query Language (DQL)
  - to perform queries on the data in a db to retrieve necessary info from it
  - `SELECT`

3. **What is DBMS, and what are their types?**

- Software package used to perform various operations on the data stored in a db. `Relational`, `Hierarchical`, `Network`, `Graph`, `Object-Oriented`

4. **RDBMS examples** : MySQL, PostgreSQL, Oracle, MariaDB

5. **Types of SQL Queries** : Select, Action

6. **What are the types of SQL Subqueries?**

- `Single-row`, `Multi-row`, `Multi-column`, `Correlated`, `Nested`

7. **SQL Constraints** : `DEFAULT`, `UNIQUE`, `NOT NULL`, `PRIMARY KEY`, `FOREIGN KEY`

8. **Note : unique key can allow multiple `NULL` values**

9. **Types of Indexes**

- `Unique Index` :
- `Clustered Index` : Defines the physical order of records of a db table, and perform data searching based on the key values. A table can have only one clustered index
- `Non-clustered Index` : Keeps the order of the table records that don't match the physical order of the actual data on the disk. A table can have multiple non-clustered indexes

10. **Schema** : Collection of db structural elements such as tables, stored procedures, indexes, functions and triggers

11. **SQL Comments** : `--` or `/**/`

12. **Operators** :

- Arithmetic : `+`, `-`
- Comparison : `>`, `<`
- Compound : `+=`, `-=`
- Logical : `AND`, `OR`
- String : `%`, `+`
- Set : `UNION`, `UNION ALL`, `INTERSECT`, `MINUS (OR EXCEPT)`

13. **Clause** : `WHERE`, `LIMIT`, `HAVING`, `LIKE`, `AND`

14. **What are Entities and Relationships?**

- An entity is a real-world object, creature, place or phenomenon for which the data can be gathered, and stored in a db whereas,
- Relationships are the collections and correlations between entities

15. **What are SQL Functions?**

- Aggregate Functions : works on group records to return a single value
  - `AVG`, `SUM`, `MIN`, `MAX`, `COUNT`, `FIRST`, `LAST`
- Scalar Functions : works on each individual value to return a single value
  - `LEN`, `UCASE`, `LCASE`, `INITCAP`, `MID`, `ROUND`, `NOW`

16. **Case Manipulation Functions** : `UCASE`, `LCASE`, `INITCAP`

## Additional Resources

- [datacamp.com](https://www.datacamp.com/blog/top-sql-interview-questions-and-answers-for-beginners-and-intermediate-practitioners)
