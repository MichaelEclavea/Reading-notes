# Database Normalization

Database normalization is a process that organizes a database into tables and columns.
To maintain database excessive modifications it needs to stick to a focused topic or purpose.

3 Reasons for database normalization.

1. minimize duplicate data
2. avoid data modification issues
3. simplify queries.

Type of Form
BCNF -   Boyce-Codd normal form
1. First Normal Form – The information is stored in a relational table with each column containing atomic values. There are no repeating groups of columns.
2. Second Normal Form – The table is in first normal form and all the columns depend on the table’s primary key.
3. Third Normal Form – the table is in second normal form and all of its columns are not transitively dependent on the primary key
