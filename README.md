# Contact Form
<h2>Languages</h2>
<ul>
	<li><b>HTML</b></li>
	<li><b>PHP</b></li>
	<li><b>MySQL</b></li>
	<li><b>CSS</b></li
</ul>
<h2>Files</h2>
<b>contact.php</b>: It is the main file with html form and php form validation.<br>
<b>dbconfig.php</b>: This file contains database connection.<br>
<b>contact_form.sql</b>: This sql file contains the details of creation of table in the database.<br>
<b>style1.css</b>: Contains styling of this project.

<h2>Database Name: database</h2>
<h2>Table Name: contact_form 
<h2>Installation</h2>

1. Install XAMPP.

2. Open XAMPP Control panel and start [apache] and [mysql] .

3. Download project from github(https://github.com/K-aqsa/ContactForm.git). Download it as a zip file.
    
4. Extract files in C:\\xampp\htdocs\.

5. Open link localhost/phpmyadmin

6. Click on new at side navbar.

7. Give a database name as (database) hit on create button.

8. After creating database name click on import.

9. Browse the file in directory[ContactForm-main/contact_form.sql].

10. After importing successfully, Open any browser and type http://localhost/ContactForm-main/contact.php

11. When all the fields are validated correctly then the data will be saved in the database and the mail will be sent.

12. If email is sent succesfully, then it will give 'Send Successfully' message.

