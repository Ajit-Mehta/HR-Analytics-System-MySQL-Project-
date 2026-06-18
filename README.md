# HR Analytics System (MySQL Project)
## Project Overview
This project focuses on analyzing HR data using MySQL to understand employee performance, salary distribution, attendance patterns, and promotion eligibility.

The goal is to help HR departments make data-driven decisions using SQL-based insights.

## Tools Used
- MySQL
- SQL (Joins, Group By, Aggregate Functions)
- GitHub

- ## Business Objectives
- Analyze employee salary distribution
- Track attendance performance
- Identify high-performing employees
- Find promotion-eligible employees
- Understand department-wise workforce strength

- ## Tables Used
- employees
- departments
- attendance
- performance_reviews

- ## Key Insights
- Department-wise salary comparison
- Employees with highest performance rating
- Attendance percentage calculation
- Promotion eligible employees list
- Workforce distribution across departments

  ## Sample Query
- ## Department Wise Average Salary
SELECT d.department_name,
AVG(e.salary) AS avg_salary
FROM employees e
JOIN departments d
ON e.department_id = d.department_id
GROUP BY d.department_name;

## Author
Ajit Kumar  
Aspiring Data Analyst  
Skills: SQL | Power BI | Tableau
