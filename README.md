# HumanResourcesProject
**You are asked to write a program that shows the salaries and working hours of a company's employees. It will also increase the number of employees by one for each new employee added.
Class	employee: abstract 

Features	baseSalary: final (default:3000)
baseWorkingHours: final (default:30)
employeeCount (default:0)
position


Methods	work() : will give position information
calculateSalary () : abstract
calculateWorkingHours () : abstract


The following classes will be written that inherit from the employee class;
•	Boss
•	Manager
•	Programmer
•	Test Engineer
•	Database Admin
•	Salesperson

For Boss class;
The boss's salary will be 20 times the main salary. Working hours will be the same as main working hours. Since there is only one boss, it is desired to define the Boss class as Final.
##For Manager class;
The director's salary will be 15 times the main salary. Working hours will be 10 hours longer than the main working hours.
##For Programmer class;
The programmer's salary will be 14 times the main salary. Working hours will be 5 hours longer than the main working hours.
##For Test Engineer class;
The Test Engineer's salary will be 1000 liras less than 14 times the main salary. Working hours will be 8 hours longer than the main working hours. 
##For Salesperson class;
The marketer's salary will be 500 liras more than 13 times the main salary. Working hours will be 8 hours longer than the main working hours.
##For Database Admin class;
Database admin salary will be 500 liras more than 14 times the main salary. Working hours will be 8 hours longer than the main working hours.

The user will be asked which position he wants to get information about. After the user selects this, he will be asked whether he wants to get information about overtime or salary. The Program will repeat after providing information about the option the user has chosen. It will continue until the user enters -1. Sample output is as follows.
**
