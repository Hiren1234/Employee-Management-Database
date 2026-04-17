🗄️ SQL Worker Database Project
📌 Project Overview
This project represents the core SQL concepts using a structured Employee Management Database. It includes tables creation, data insertion, and various rela-world queries used in data analysis and reporting.

The main objective of creating this project is to showcase SQL skills for Data Analyst Roles, including data aggregation, joins, filtering, and advanced querying techniques.

🏗️ Database Structure
Worker Table: Which Stores Employees Details

+ WorkerID (Primary Key Uniquely Identifies Each and Every Record)
+ FirstName
+ LastName
+ Salary
+ JoiningDate
+ Department

2️⃣ Bonus Table

This talbe represents bonus details:

* WorkerReferenceID (Foreign Key)
* BonusAmount
* BonusData

3️⃣ Title Table

This table demonstrates Employee Job Title Details:

- WorkerReferenceID ( Foreign Key)
- WorkerTitle
- AffectedDate

🛠️ Technologies Used
- SQL (MYSQL)
- MYSQL WORKBENCH

📊 Key SQL Concepts Covered

BASIC QUERIES:

- SELECT, WHERE, DISTINCT
- ALIASING
- SORTING (ORDER BY)

🔹 String Functions

 - UPPER() : To convert String into Upper Case
 - LOWER() : To Convert String into Lower Case
 - REPLACE() : To Replace String
 - CONCAT() : To Join Multiple String
 - LENGTH() : To Find the Length of The String

🔹 Filtering Techniques

- Like Operator
- Where and Between 
- IN or NOT IN Operator

🔹 Aggregate Functions

* COUNT()
* MAX()
* MIN()
* SUM()

🔹 Grouping

- GROUP BY : It collapses the rows with same values and apply aggregations on it.
- HAVING   : To find the duplicate values after aggregations.

🔹 Joins & Relationships

- INNER JOIN
- Foreign Key Relationships

🔹 Subqueries

- Nested queries
- Finding the nth highest salary

