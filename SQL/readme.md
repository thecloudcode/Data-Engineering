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
- `Clustered Index` : _Defines the physical order of records_ of a db table, and perform data searching based on the key values. A table can have only one clustered index
- `Non-clustered Index` : _Keeps the order of the table records that don't match the physical order of the actual data_ on the disk. A table can have multiple non-clustered indexes

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

17. **Character Manipulation Functions** : `CONCAT`, `SUBSTR` etc.

18. **SELECT query : Appearance Order** : SELECT - FROM - JOIN - ON - WHERE - GROUP BY - HAVING - ORDER BY - LIMIT

19. **SELECT query : Interpreter Execution Order** : FROM - JOIN - ON - WHERE - GROUP BY - HAVING - SELECT - ORDER BY - LIMIT

20. **View** : Virtual table containing a subset of data retrieved from one or more database tables (or other views), gets invalid if the original table is deleted

21. **BOOLEAN** : TRUE, FALSE or NULL

22. **DELETE vs TRUNCATE** : _DELETE_ is reversible, works slower than truncate and is specified using WHERE clause where as _TRUNCATE_ is irreversible and works faster and cannot be applied on a foreign key

23. **HAVING vs WHERE** : _HAVING_ works on grouped data whereas _WHERE_ works on each row individually. ORDER : `WHERE - GROUP BY - HAVING`

24. **nth highest value** : `OFFSET` Clause

25. **Selecting Random Rows from a Table** : SELECT \* FROM table_name ORDER BY RAND() LIMIT 5;

## Additional Resources

- [datacamp.com](https://www.datacamp.com/blog/top-sql-interview-questions-and-answers-for-beginners-and-intermediate-practitioners)
- [Basics](https://chatgpt.com/share/678cfbcc-a45c-8007-8a11-84825981dd2f)
