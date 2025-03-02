1) show database => to get all existing databases

2) create database database_name => to create a new database

3) use database_name => to select a database to work with

Share the SQL file to create Database

4) show tables => to view all existing tables in a database

5) select * from table_name => to view all data from a database

6) select column_name, column_name from table_name => to view data only from a required column from a table. Column names can have any order

7) select column_name, column_name + 10 from table_name => this will only good to use with column consists of number values. This is only for view purpose and this won't affect original values of the column

8) select column_name, column_name + 10 as new_column_name from table_name => we can change the column name and this is only for viewing and this won't change column name in table

We can use Mathemetical operators +(addition), -(subtraction), *(multiplication), /(division), %(modulus). Also follow the operater precedence used in Mathematics.

9) select column_name, 
    column_name + 10 as new_column_name
    from table_name => breaking a query to multiple lines will help to easily maintain
that query when it is getting complex

10) -- select * from table_name => two hyphen before a query will turn it into a comment, which cannot be executed

11) select column_name, column_name + 10 as 'new column name' from table_name => if we need a column name with space, give that column name in quatations

12) select distinct column_name from table_name => distinct omits the duplicate value for the selected column


Give a task

Comparison operater

> Greater than
< Lesser than
>= Greater than or equalto
<= Lesser than or equalto
= Equalto 
!= Not equalto
<> Not equalto

13) select * from table_name where column_name > value => used to filter data based on a value of column

Logical operater: and or not

14) select * from table_name where column_name > value and column_name = value => used to filter data based on a value of multiple column

Format of date and all logical operator execution


Give a task


Membership operater (in and not in)

15) select * from table_name where column_name in (value1, value2) => to filter with multiple value matches from a single column

Between Operator

16) select * from table_name where column_name between value1 and value2 => used to get result within a range in a column

Like operator

17) select * from table_name where column_name like 'characters%' => to find the value of the column starts with that characters

18) select * from table_name where column_name like '%characters' => to find the value of the column ends with that characters

19) select * from table_name where column_name like '%characters%' => to find the value of the column contains that characters

20) select * from table_name where column_name like 'character%characters' => to find the value of the column that stars and ends with selected characters

21) select * from table_name where column_name like '_character__Character__' => to find the value of the column the has exact character count with specific character at specific place







