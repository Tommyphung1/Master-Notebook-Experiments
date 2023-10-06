# Master-Notebook-Experiments

SQL
How to begin:
1. Setup connection: 
2. Execute Command using Clause
3. Close Connction when finished with database

| Data Type | Desctription |
| :-----: | :------: |
| **INTEGER** |-2147483648 to +2147483647 (Why?) |
| **REAL** | Floating numbers with a **max** of 6 decimal places |
| **TEXT** | a string of any size |
| **CHAR** | single character |
| **DATE** | date format MM/DD/YYYY |
| **BLOB** | A large file... |

## CREATE Clause
**Function:** Create a table for a database. <br>
**Requirement:** A connection to a database is needed. SQL library will create the database if the connection fails to be made.


## DELETE FROM 
**Function:** Delete from a table based on a column if given.

## SELECT Command
**Function**: Select columns from a table to obtain from the database. 
**Requirement:** Must contain in the table that was called from the FROM clause
**Additions** 
Distint: Only select rows that are unique from the column selected. 
\* : Used to select all the columns without typing each of the column names.
AS: Can be added after selected columnd to rename the column. 

## WHERE Command
**Function:** Uses to filter the data with a **logical statement** or **condition**.
**Requirement**: Must be used before GROUP BY if used. HAVING will be used instead if so. 
