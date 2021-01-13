+---------------------+
 CONTENTS OF THIS FILE
+---------------------+
 * Introduction
 * Requirements
 * Prerequisites
 * Steps to execute

------------
Introduction
------------
	The EXAM PORTAL has the four Modules. The system to conduct Exam in the form of multiple choice questions. In this Exam Portal, questions are based on Java and Relational DataBase Management System (MySQL).
 * Home Page :
This is the beginning of the Exam Portal to navigate from Log In page and Registration Form.

 * Registration :
In this section collects information/details from users and stores the Data in the Database (MySQL).
 * Log In :
This section navigates towards the Exam section by validating and verifying the users PRN and password, which is stored in main database.
 * Exam : 
After Log In valid users can attend Exam. The Exam is in the form MCQ’s, user should select the appropriate answers and must attend all questions.
 * Result :
After submitting the Exam valid answers are validated and the final score is displayed in the pop up window.


------------
Requirements
------------
 * Machine Requirements :
Operating System : -  Windows, Ubuntu.

 * Developing Exam portal includes the following requirements:
1.Eclipse IDE :
	Minimum required version Eclipse MARS.
2.WindowBuilder for Swing Designer Application.
3.JDK 1.7 or above.
4.JRE 1.7 or above.
5.RDBMS (MySQL) for backend data manipulation.


-------------
Prerequisites
-------------
1. Install Java:
	Go to Software -> Java folder and run jdk-8u161-windows-x64.exe
2. Install Eclipse IDE:
	Go to Software -> eclipse folder and run eclipse.exe
3. Install MySQL:
	Go to Software -> MySQL folder and run mysql-installer-community-8.0.12.0.msi with username as 'root' and password '123456'


----------------
Steps to execute
----------------
1. Open eclipse and import ExamPortal project.
2. Add JConnector to Build path of the Project from Software -> JConnector folder.
3. Open MySQL 8.0 Command Line Client.
4. Create Users and QA table in Exam_portal database and insert ten questions in QA table.
