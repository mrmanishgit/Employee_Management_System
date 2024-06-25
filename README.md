# Employee_Management_System
![logo](https://github.com/mrmanishgit/Employee_Management_System/assets/157808382/bd966491-5385-4b27-a183-5f6f72192edf)

Installation & Step by Step Process

An employee management system is a software, that helps your employees to give their best efforts every day to achieve the goals of your organization. It guides and manages employees efforts in the right direction. It also securely stores and manages personal and other work-related details for your employees.
Installing / Getting started
Developing
Built With
Eclipse IDE
jdk-18.0.2.1
mysql-connector.jar
xampp-windows-x64-8.0.9-0-VS16
mysql
Prerequisites
What is needed to set up the dev environment. For instance, global dependencies or any other tools. include download links.

https://www.eclipse.org/downloads/
https://www.eclipse.org/downloads/
https://www.apachefriends.org/download.html
Setting up Dev
Here's a brief intro about what a developer must do in order to start developing the project further:

gh repo clone manishgit/Employee-Management-System
cd Employee-Management-System/
Step 1: Deployee Database

goto Xampp Control panel , open Apache and mysql server
goto Crome and serach : http://localhost/oraclemyadmin/
create new data base name project3
goto import navigater
choose your Database file "project3" and upload there and click to Go
Step 2: Install JDK & Eclipse step by step

no need Additional features
Step 3 : open Project Folder in Eclipse

Building
Now, you need to change some line as per your connecton :

JDBC Connecter
open .classpath file and change
	<classpathentry kind="lib" path="D:/College/Employee_Project/Employee-Management-System/mysql-connecter/mysql-connector.jar"/>
		<!-- path="D:/College/Employee_Project/Employee-Management-System/mysql-connecter/mysql-connector.jar"  --> 
		<!-- set the path of where your mysql connecter location. like my current location
		D:\College\Employee_Project\Employee-Management-System\mysql-connecter -->
	<classpathentry kind="output" path="bin"/>

JDK connecter
open conn.java file and change
	<classpathentry kind="lib" path="D:/College/Employee_Project/Employee-Management-System/mysql-connecter/mysql-connector.jar"/>
		<!-- path="D:/College/Employee_Project/Employee-Management-System/mysql-connecter/mysql-connector.jar"  --> 
		<!-- set the path of where your mysql connecter location. like my current location
		D:\College\Employee_Project\Employee-Management-System\mysql-connecter -->
	<classpathentry kind="output" path="bin"/>

you can change you code as per your Requirement.

Deploying / Publishing
Goto Front_Page.java and simple run file simple like normal java file.
Style guide / Testing
Run Step by Step As per your Requirements. We have provided Output images for you Understanding See in Output_images Folder.
How to work Our Application .
------------- ---------------- ------------- -- -- -- - - - -- - - - -- - --  -- - -- - -- - - -- - - - -- - - - - -- - - -- - - -
Welcome page
Signup & Forgot password
Home page
Employee

![Welcome](https://github.com/mrmanishgit/Employee_Management_System/assets/157808382/99dc8f67-e957-4147-8e3a-be6f716ec92c)
![Homeicone](https://github.com/mrmanishgit/Employee_Management_System/assets/157808382/0c061d1a-33ba-460a-a6c0-ec1fe2b72b77)
![Aboutus](https://github.com/mrmanishgit/Employee_Management_System/assets/157808382/217bfecf-e14c-46e0-97ff-bef144900b38)
About US
Employee Panel
Add Employee
Update Employee
![Attendance](https://github.com/mrmanishgit/Employee_Management_System/assets/157808382/f3944e67-59d4-4768-a9bb-7512bee133d4)
Salary
Attendance
![Employeedetail](https://github.com/mrmanishgit/Employee_Management_System/assets/157808382/420d6ae0-68e2-4e0a-bc17-037dbae88139)
![Removeemployee](https://github.com/mrmanishgit/Employee_Management_System/assets/157808382/b09e2766-5b7c-4ea7-b086-cbfb86c50464)
![Upadatesalary](https://github.com/mrmanishgit/Employee_Management_System/assets/157808382/0647e798-c383-4041-bbca-c5288af63564)
Login page
login with Username & Id
![login](https://github.com/mrmanishgit/Employee_Management_System/assets/157808382/591bc7c1-6472-4ba3-b3b5-0043bcd237f9)
View Employee
Remove Employee
Attendance Panel
Fill Attendance
View Attendance
![Attendance](https://github.com/mrmanishgit/Employee_Management_System/assets/157808382/27ec0e09-31e0-4f12-aa1e-86887bf5d11c)
salary Panel
Add Salary
Update Salary
Generate Payment slips
About US Panel
![Aboutus](https://github.com/mrmanishgit/Employee_Management_System/assets/157808382/d1017531-d94f-42cc-a681-66d43d070570)

Database
Goto Xampp Control panel , open Apache and mysql server
Goto Crome and serach : http://localhost/phpmyadmin/
Create new data base name project3
Goto import navigater
Choose your Database file "project3" and upload there and click to Go.
