Recently, I completed a guided project on data cleaning with MySQL. 
It was a hands-on, practical approach that gave me deeper insights into how databases work and, most importantly, how to clean messy datasets using MySQL queries.
Data cleaning is an essential skill in data analytics. It is the process of maintaining data consistency or correcting or eliminating inaccurate, corrupted, or incomplete data from a dataset.
Cleaning your data ensures the analysis you perform is accurate and reliable. For me, learning how to use MySQL for this process has been interesting, and I hope to use it soon to organize large real-world datasets efficiently.
Here are a few key takeaways from my learning experience so far:

Data import: I learned how to import CSV files into MySQL databases and export cleaned data back into files. This is vital when you’re working with real-world data from various sources.
SQL statements: I learned how to use SQL statements like the SELECT, FROM, DISTINCT, COUNT, MIN, MAX, AVG, HAVING, WHERE, LIKE, AND, OR, NULL, NOT NULL, GROUP BY, ORDER BY, LIMIT, AS, etc.
Joins and Unions: I learned how to join tables in MySQL using the different kinds of joins, such as inner joins, outer joins (right and left), and self joins. Also learned how to combine rows together using ‘UNION’.
String functions: I practiced working with strings in different ways by using built-in string functions in MySQL, such as length, upper, lower, trim, substring, replace, locate, and concatenation.
Case Statements: Using case statements to add logic in SELECT statements was also one of the things I learned and got to practice with in my course. It works like an if/else statement for those familiar with it in development.
Subqueries and CTEs: Basically involved creating query inside a query or queries inside a query. It can be used in the WHERE, FROM, and SELECT statements. CTEs work kind of similar to subqueries.
Other things I learned include window functions, temp tables, stored procedures, and triggers & events.
The Data Cleaning Project
In the project, I worked on cleaning a dataset that had issues like duplicate entries, missing values, and inconsistent formats. These were the steps I followed:
Loaded the dataset: Imported the raw data into the MySQL workbench from a CSV file.
Removed duplicates: One of the first steps in cleaning data is identifying and removing duplicate entries. I used the DISTINCT keyword and DELETE statements to clean up the dataset.
Standardized data formats: Performed some operations, like eliminating whitespace, trimming a column, and updating the column to replace the previous column, grouping common column categories into one group, and reformatted a wrong column datatype. I did this in order to format the data into a consistent structure.
Handled missing or null values: I used MySQL functions and queries to identify missing or null values and learned when to either fill in or delete missing or null values based on the analysis requirements.
Remove unnecessary columns and rows: Removed an unnecessary row and some columns with no values.
Created a clean dataset: Exported the cleaned dataset, ready for further analysis.
