METHODOLOGY<br>
This methodology provides a detailed step-by-step guide for creating a basic To-Do List application using PHP, including front-end, back-end, and database components. We'll be using the following files: (style.css, jquery.js, add.php, check.php, remove.php, to_do_list.sql, db_conn.php, and index.php.)<br>

1.	Setting Up the Environment<br>
Before creating the application, ensure you have a development environment set up. You can use XAMPP, WAMP, or MAMP for local development.
<br>•	Install XAMPP/WAMP/MAMP:
Download and install the appropriate environment for your operating system.
Start the Apache and MySQL services.
<br>•	Set Up a Virtual Host (Optional):
Configure a virtual host to access your application via a custom domain on your local machine.
Modify the hosts file to include your custom domain, and adjust the Apache configuration accordingly.

![XAMPP](https://github.com/CodeLover2002/PHP/blob/main/screenshots/xampp.png)
<br>
2.	Create the Database<br>
 Create the database and tables necessary for the To-Do List application.
<br>•	Design the Database Schema:
You need one main table to store the to-do list items.
The table will have columns for id, task, is_done, created_at, and updated_at.
<br>•	SQL Script for Creating the Database (to_do_list.sql):
•	Execute the SQL Script:
Use a MySQL client (e.g., phpMyAdmin or MySQL Workbench) to execute the SQL script and create the database and table.
<br>
![SQL](https://github.com/CodeLover2002/PHP/blob/main/screenshots/sql.png)
<br>
<br>
3.  Create a Database Connection File (db_conn.php):
This file is used to establish a connection to the MySQL database
<br>
<br>
![SS1](https://github.com/CodeLover2002/PHP/blob/main/screenshots/scs1.png)
<br>
<br>
4.	Create the Front-End Interface (index.php)
This file serves as the main interface for the application, displaying the list of tasks and providing options to add, mark as complete, or delete tasks.
<br>
<br>
![SS2](https://github.com/CodeLover2002/PHP/blob/main/screenshots/scs2.png)
![SS3](https://github.com/CodeLover2002/PHP/blob/main/screenshots/scs3.png)
![SS4](https://github.com/CodeLover2002/PHP/blob/main/screenshots/scs4.png)
![SS5](https://github.com/CodeLover2002/PHP/blob/main/screenshots/scs5.png)
![SS6](https://github.com/CodeLover2002/PHP/blob/main/screenshots/scs6.png)
<br>
<br>
5.	JavaScript for Interactivity (jquery.js):
This script handles AJAX requests for adding, marking tasks as done, and removing tasks.
<br>
<br>
![SS7](https://github.com/CodeLover2002/PHP/blob/main/screenshots/scs7.png)
![SS8](https://github.com/CodeLover2002/PHP/blob/main/screenshots/scs8.png)
<br>
<br>
6.	CSS for Styling (style.css):
<br>
<br>
![SS9](https://github.com/CodeLover2002/PHP/blob/main/screenshots/scs9.png)
![SS10](https://github.com/CodeLover2002/PHP/blob/main/screenshots/scs10.png)
![SS11](https://github.com/CodeLover2002/PHP/blob/main/screenshots/scs11.png)
![SS12](https://github.com/CodeLover2002/PHP/blob/main/screenshots/scs12.png)
![SS13](https://github.com/CodeLover2002/PHP/blob/main/screenshots/scs13.png)
![SS14](https://github.com/CodeLover2002/PHP/blob/main/screenshots/scs14.png)
<br>
<br>
7.	Implement Back-End Logic for CRUD Operations
Now let's create the PHP scripts for adding, marking as complete, and removing tasks.
<br>•	Add a New Task (add.php):
<br>
![SS15](https://github.com/CodeLover2002/PHP/blob/main/screenshots/scs15.png)
<br>
•	Mark Task as Complete (check.php):
<br>
![SS16](https://github.com/CodeLover2002/PHP/blob/main/screenshots/scs16.png)
<br>
•	Remove Task (remove.php):
<br>
![SS17](https://github.com/CodeLover2002/PHP/blob/main/screenshots/scs17.png)
<br>
<br>
8.	Step 6: Test the Application
•	Once all the files are in place, test the application to ensure it works as expected.
•	Run the Application:
•	Open a web browser and go to the URL where your application is hosted.
•	Test the core functionalities: adding tasks, checking tasks as complete, and removing tasks.
•	Troubleshooting:
•	If the application doesn't work as expected, check the PHP error logs and console logs in your browser's developer tools.
•	Make sure the database connection is correctly set up in db_conn.php.
<br>
<br>
![SS18](https://github.com/CodeLover2002/PHP/blob/main/screenshots/scs18.png)
<br>
![SS19](https://github.com/CodeLover2002/PHP/blob/main/screenshots/scs19.png)
