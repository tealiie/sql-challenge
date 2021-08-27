# Employee Database: A Mystery in Two Parts

![sql](https://user-images.githubusercontent.com/19372031/131056090-3dee6551-9864-4e65-b118-94279bef286d.png)

## Instructions
You are presented with 6 CSV files from Pewlett Hackard containing employee data from 1980s ad 1990s. In this project you will need to design the tables to hold data in the CSVs, import the CSVs into a SQL database, and answer questions about the data

## Data Engineering
* Use the information you have to create a table schema for each of the six CSV files. Remember to specify data types, primary keys, foreign keys, and other constraints.
  * For the primary keys check to see if the column is unique, otherwise create a composite key. Which takes to primary keys in order to uniquely identify a row.
  * Be sure to create tables in the correct order to handle foreign keys.

<img width="1005" alt="Database_QuickDBD" src="https://user-images.githubusercontent.com/19372031/131057444-3216c77d-7aca-4104-a60e-3299b519e4da.png">

* Import each CSV file into the corresponding SQL table. Note be sure to import the data in the same order that the tables were created and account for the headers when importing to avoid errors.

## Data Analysis
* List the following details of each employee: employee number, last name, first name, sex, and salary.
* List first name, last name, and hire date for employees who were hired in 1986.
* List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name.
* List the department of each employee with the following information: employee number, last name, first name, and department name.
* List first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B."
* List all employees in the Sales department, including their employee number, last name, first name, and department name.
* List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.
* In descending order, list the frequency count of employee last names, i.e., how many employees share each last name.
