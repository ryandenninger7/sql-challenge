# sql-challenge
# Employee Database Analysis - Pewlett Hackard 1980s and 1990s

Description:
This project explores the employee database of Pewlett Hackard, focusing on the period of the 1980s and 1990s. This project is divided into three main parts: Data Modeling, Data Engineering, and Data Analysis. The goal is to design a database schema to hold data from six CSV files, import the data into a PostgreSQL database, and then perform various analyses to gain insights into the employees' details and their employment history.

Data Modeling:
For data modeling, an Entity-Relationship Diagram (ERD) was created to illustrate the relationships between the employee, department, salaries, and other relevant tables. Tools like QuickDBD were used to facilitate the design process.

Data Engineering:
The data engineering phase involved creating a table schema for each CSV file, ensuring correct data types, primary keys, foreign keys, and other constraints were applied. The tables were created in a PostgreSQL database using pgAdmin 4, and data from the CSV files was imported accordingly.

Data Analysis:
The analysis portion aimed to answer several key questions about the employees, such as salary details, department managers, employees hired in a specific year, and more. SQL queries were crafted and executed to extract this information from the database.

Analysis:
1.) Employee Details: Listed employee number, last name, first name, sex, and salary. This helped in understanding the salary distribution among different genders.

2.) Hiring Trends: Analyzed employees hired in 1986 to identify hiring trends.

3.) Department Managers: Listed each department's manager, providing insights into leadership structures.

4.) Employee-Department Relations: Showed the department number for each employee, revealing the distribution of employees across departments.

5.) Name Patterns: Focused on employees named Hercules with a last name starting with 'B', demonstrating SQL's pattern matching capabilities.

6.) Sales Department Employees: Identified employees in the Sales department to understand its size and scope.

7.) Cross-Department Analysis: Compared employees in the Sales and Development departments, highlighting the company's focus areas.

8.) Last Name Frequency: Analyzed the frequency of last names, offering a unique perspective on diversity.

Conclusion:
This project showcased the power of SQL in analyzing and extracting meaningful insights from a large dataset. Through careful data modeling, engineering, and analysis, valuable information was able to be uncovered about Pewlett Hackard's employees from the 1980s and 1990s.

Future Work:
Future analyses could include exploring trends over time, such as changes in salary, department sizes, or positions held, to gain deeper insights into the company's evolution.
