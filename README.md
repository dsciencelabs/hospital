# PHP-MySQL-CRUD-Web-Application

This repository is about CRUD Operations Example using Object Oriented PHP & MySQL Database.

# Setting-up Database Tables 

* Open XAMPP Control Panel
* Next to the Apache module click Start
* Next to the MySQL module click Start
* Navigate to http://localhost/phpmyadmin/
* Click Databases at the top
* Under Create database input phpcrud and select utf8_general_ci as the collation
* Click Create
* Select the newly created database
* Click the SQL tab and execute the below SQL:
  -	hospital_db.sql

# Creater API (UI and Sever)

We now need to start our web server and create the files and directories we’re going to use for our login system.

* Navigate to XAMPPs installation folder (C:/)
* Open the htdocs folder
* Create the following folders and files:

```
\-- hospital
    \-- api
    	\-- config
		|-- database.php
	\-- doctor
		|-- create.php
	    	|-- delete.php
	    	|-- read.php
	    	|-- read_single.php
            	|-- update.php
        \-- objects
            	|-- doctor.php
    \-- bower_components
	|-- copy all components here 
    \-- dist
	|-- copy all components here 
    \-- doctor
    	|-- opy all components here 
    \-- hospital_db.sql
    \-- master.php
```

# Open your Web-Application

http://localhost/hospital/doctor/

