# Sql-Challenge Overview
The EmployeeESL folder houses a data folder containing all CSV files used for analysis, the data modeling file, the data engineering file and the data analysis file. 
# Background 
It’s been two weeks since you were hired as a new data engineer at Pewlett Hackard (a fictional company). Your first major task is to do a research project about people whom the company employed during the 1980s and 1990s. All that remains of the employee database from that period are six CSV files.

For this project, you’ll design the tables to hold the data from the CSV files, import the CSV files into a SQL database, and then answer questions about the data. That is, you’ll perform data modeling, data engineering, and data analysis, respectively.

# Instructions
This Challenge is divided into three parts: data modeling, data engineering, and data analysis.

# Data Modeling
The file labeled "sql-challenge_DataModeling.png" contains the Entity Relationship Diagram of the tables for the 6 CSV files provided for this challenge.

# Data Engineering
The file labeled "sql-challenge_DataEngineering.sql" contains the table schema. Once the schema was created in PgAdmin, all 6 CSV's were imported into its corresponding table with in the employeesql database. 

# Data Analysis
The file labeled "sql-challenge_DataAnalysis.sql" contains the data analysis portion of this challenge. The following questions were answered:
1. List the employee number, last name, first name, sex, and salary of each employee.
2. List the first name, last name, and hire date for the employees who were hired in 1986.
3. List the manager of each department along with their department number, department name, employee number, last name, and first name.
4. List the department number for each employee along with that employee’s employee number, last name, first name, and department name.
5. List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.
6. List each employee in the Sales department, including their employee number, last name, and first name.
7. List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.
8. List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).

# Resources Used
Chat GPT, Stack Overflow and previous assignments were used to help me troubleshoot problems associated with importing tables and structuring syntax appropriately. 
