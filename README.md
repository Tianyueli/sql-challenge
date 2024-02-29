# sql-challenge Overview

The Pewlett Hackard (a fictional company)researched company workers employed during the 1980s and 1990s. The employee database consists of six CSV files, detailing employee and department information during the above period.
    For this project, i designed tables to hold the employee data, imported the CSV files into a SQL database, and then analyzzed the employee data attributes and their corresponding relations with each other.
In a nutshell, data modeling, data engineering, and data analysis were performed in this project.
    


## Research Questions
As shown in the dataset, we are trying to look at various attributes  associated wi

    1. List the employee number, last name, first name, sex, and salary of each employee.
    2. List the first name, last name, and hire date for the employees who were hired in 1986.

    3. List the manager of each department along with their department number, department name, employee number, last name, and first name.

    4. List the department number for each employee along with that employee’s employee number, last name, first name, and department name.

    5. List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.

    6. List each employee in the Sales department, including their employee number, last name, and first name.

    7. List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.

    8. List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).


## Analysis & Findings
* The Pewlett Hackard dataset contains demographic information and employee history of individuals, including birthdate, gender, name, hire date, salary, department info and additional details. 
* The six tables contains interconnected relations: 
    * For example, employees table contains the source of employee number, which serves as the reference point for the salaries, department manager and department employee tables. 
    * Similarly, in order to access department information for an employee, the department tables have to be joined where applicable to bring light to the granular deparment number or name.

## Sources and References

* Used pgAdmin4 for data modeling, engineering and analysis



