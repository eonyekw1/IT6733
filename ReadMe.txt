Project: Integration of Data from MS SQL Server databases using SSIS

Business Problem: ABC is a ficticious company. The data from different MS SQL Server databases need to be integrated with SSIS. 
The following tasks will be executed in this project:

1.	Integration of data from tables in HR and HR_2 databases.
2.	The data from the following fields are required
	Employee_id
	First_name
	Last_name
	Email
	Phone_number
	Hire_date
	Salary
	Job_title
	Department_name
	State
	Country_name

3.	The integrated data should be stored in Employee table of HR_Destination database.
4.	HR_Destination database should be backed up for future data analysis.
5.	ABC would also want to know how much salary each department, state and country earn.
6.	The report should be stored in Employee_Report table of HR_Destination.
7.	Employees table in HR_Destination should be truncated each time the project is executed.
8.	The project should be deployed to MS SQL Server.
