# SQL Query Filtering for Security Analysis

## Project Overview
This project demonstrates my ability to use SQL queries with filtering techniques to investigate potential security issues within an organization's database. As a security professional, I needed to examine login attempts and employee machine data to identify potential security concerns and unauthorized access attempts.

## Scenario
Working as a security professional at a large organization, I was tasked with investigating potential security issues involving login attempts and employee machines. By examining the organization's data in their `employees` and `log_in_attempts` tables, I used SQL filters to retrieve and analyze specific records that could indicate security vulnerabilities or incidents.

## Database Structure

### log_in_attempts Table
This table records all login attempts to the organization's systems with the following columns:
- **event_id**: The identification number assigned to each login event
- **username**: The username of the employee
- **login_date**: The date the login attempt was recorded
- **login_time**: The time the login attempt was recorded
- **country**: The country where the login attempt occurred
- **ip_address**: The IP address of that employee's machine
- **success**: The success of the login attempt; FALSE indicates a failed attempt

### employees Table
This table contains information about the organization's employees with the following columns:
- **employee_id**: The identification number assigned to each employee
- **device_id**: The identification number assigned to each device used by the employee
- **username**: The username of the employee
- **department**: The department the employee is in
- **office**: The office the employee is located in

## Project Components
This project folder contains:

- **SQL_Security_Analysis.pdf**: A comprehensive document showing:
  - The SQL queries used to investigate potential security issues
  - Explanations of the filtering techniques applied (AND, OR, NOT, WHERE, LIKE)
  - Examples of pattern matching using wildcards for flexible data filtering
  - Analysis of the query results and their security implications
  - Screenshots of query execution and results

The document showing database structure and table schemas used for this analysis is available in **Table_Formats.pdf** file under the [reference-documents](./reference-documents) folder. 

## Skills Demonstrated
- Writing SQL queries with complex filtering conditions
- Using logical operators (AND, OR, NOT) to create targeted filters
- Applying the WHERE clause to filter database records based on specific criteria
- Implementing pattern matching with LIKE and % wildcard for flexible text searching
- Analyzing database records for security anomalies
- Identifying potential unauthorized access attempts
- Database security investigation techniques

## Tools Used
- SQL query language
- Logical operators:
  - AND (combining multiple conditions that must all be true)
  - OR (combining alternative conditions where at least one must be true)
  - NOT (negating conditions to exclude specific records)
- Comparison operators (=, >, <, !=, etc.)
- WHERE clause for filtering records based on specific conditions
- Pattern matching:
  - LIKE operator for flexible text matching
  - % wildcard for matching zero or more characters in patterns
- MariaDB database environment

## Key Security Analysis Techniques
- Filtering login attempts based on success/failure status
- Identifying login anomalies based on time patterns and geographic location
- Analyzing employee machines for unmet security patch updates
- Identifying potential security policy violations

This project showcases my ability to leverage SQL as a security tool for investigating potential threats and risks within an organization's data environment.