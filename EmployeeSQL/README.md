# Employee Database - SQL Challenge 

Employee dtatbase design the tables to hold data in the CSVs, imported the CSVs into a SQL database, and answer questions about the data. In other words, performed:
*Data Modeling Inspected the CSVs and sketch out an ERD of the tables.
*Data Engineering:Created a table schema for each CSV files and imported each CSV file into the corresponding SQL table.


* [Background](#background)
* [SQL Qeries](#trends)
* [Jupyter Notebook](#nb)
* [Technologies Used](#technologies)

##  <a name="background"></a>Background

For this project, Created a database in Postgresql from Given CSV files.
The csv file being analyzed is located [here](./EmployeeSQL/data).
The schema file is located [here](./EmployeeSQL/tables.sql).
The query file is located [here](./EmployeeSQL/queries.sql).


## <a name="Queries"></a>SQL queries and answers 

Data Analysis Solved the following quetions:

* List the following details of each employee: employee number, last name, first name, gender, and salary.

* List employees who were hired in 1986.

* List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name, and start and end employment dates.

* List the department of each employee with the following information: employee number, last name, first name, and department name.

* List all employees whose first name is "Hercules" and last names begin with "B."

* List all employees in the Sales department, including their employee number, last name, first name, and department name.

* List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.

* In descending order, list the frequency count of employee last names, i.e., how many employees share each last name.
  
Bonus SQL Queries and Data Visualization:
* Imported the SQL database into Pandas.

* Created a histogram to visualize the most common salary ranges for employees.

* Created a bar chart of average salary by title.

 ##  <a name="nb"></a>Jupyter Notebook

For this project, I used jupyter notebook to render and display the results of this analysis. You can view the notebook here:

<https://github.com/PunamSonawane/sql-challenge/blob/master/EmployeeSQL/Bonus.ipynb>
The notebook is also available inside this repository [here](./EmployeeSQL/Bonus.ipynb).

##  <a name="technologies"></a>Technologies Used

* Python
* PostgreSQL 
* Pandas library
* Matplotlib library
* Jupyter Notebook