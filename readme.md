## Project Brief
#### Name Of Employee : Narayan Krishna
#### Employee Id : 3155150
#### Name of Project : School Data Simple Query System
#### Type : NAGP Java Core Assignment
#### Date of submission : 23 March 2022

## How to run project
	1. Open eclipse ide
	2. Go to File menu and select import
	3. Select Existing Project From Workspace
	4. Click on Select archive file
	5. Browse to the attatched project
	6. Go to ./src/com.nagarro.application
	7. Run Runner.java as Java application

## Note 
 - Default Password : Test
 - Password : ./resources/passwords.txt
 - Db : ./resources/db.txt	

## Project Content

> The access to the system is password protected. The password will be stored in a file on the Desktop. When user starts the application, it will ask user to enter the password and the application will only go ahead if the password is correct, i.e, it matches the password stored in the password file on the desktop. If the password entered is incorrect, it shows the message of incorrect password with several attempts left. In total a user gets 4 attempts to enter the correct password after which the system exits. After a user enters correct password, he is shown with the following Menu.

	1. Add Student Details - Add the details of a new student
	2. Remove Student Details - Remove a student from records
	3. Add Teacher Details - Add the details of a new teacher
	4. Remove Teacher Details- Remove a teacher from records
	5. Query Data- Ask user to enter a query and show the results
	6. Exit

> The Query will be in the format below.
 - SELECT * from Person
 - Select * from Teacher

#### Table Name can be any of the following:
- Person : Show results across Students and Teachers
- Student : Show results from Student table only
- Teacher : Show results from teachers table only

#### Take care of below points: -

- Please Validate the query String input by the user. : Done
- Use exception handling wherever applicable. : Done
- Code Completeness and Correctness : Done
- Use of Java Collections : Done
- Usage of OO Principles, package/class structure, class/function/variable names : Done
- Code in running condition : Done
- Usage of Java 8 new features : Done

#### Tables

**Person Table Data**
 - FirstName 
 - MiddleName 
 - LastName
 - ContactNumber 
 - Address

**Student Table Data**
- Persons data (Student extends Person)
- RollNumber
- Marks

**Teacher Table Data**
- Persons data (Teacher extends Person)
- employeeId
- Salary
- Bonus