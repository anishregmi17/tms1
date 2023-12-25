# tms

This is complete PHP project,
Here you can find CRUD operation, Role Management, file Uploading in detail.

1. Install and set up wampp or xampp server
2. Run the wampp or xampp
3. create a project inside server
   if xampp
   xampp/htdocs/project_name
   if wampp
   wampp/www/project_name
4. run the project
   go to brower and type : localhostt/project_name

5. Create database
   go to brower and type: localhost/phpmyadmin (MYSQL)
   and create databse and tables

6. Create folders and files inside your created project

   tms (folder)
   assets (folder)
   css (folder)
   style.css
   js(folder)
   min.js
   img(folder)
   files(folder)
   videos(folder)

   connection (folder) : inside this folder we write the database and project connection code
   config.php (connect prject and database)

   inc (folder) : inside this folder we keep the repeated codes
   header.php
   navbar.php
   sidebar.php
   footer.php

   loginprocess (folder) : inside this folder, we write the login process code
   login.php
   logout.php

   uploads (folder) : inside this folder we store the dynamic images

   users (folder) : we need to create same folder and files for other process
   create.php : form
   index.php : table
   edit.php : form
   view.php : form
   delete.php : only code

   index.php : contain login UI
   home.php
   register.php
   profile.php

   database (folder)
   database_name.sql

PHP syntax:

<?php
    // write codes
 ?>

Variable declare in PHP
$x-10;

Print in PHP
echo "Hello World"; : prefer
print ("Hello");

Some common functions
mysqli(); : connect project and database
mysqli_fetch_array(); : feth all data from the database
mysqli_fetch_assoc(); : fetch a single row data from the database
mysqli_query(): : Connect queries and database
mysqli_close(): close the database

GLOBAL VARIABLE
$_POST[];
$\_GET[];
$_FILES[];
$-SESSION[];

Database:
Relational database:
MYSQLI

data types
INT
LONGINT
VARCHAR
DATE
TIMESTAMP

CREATE TABLES
tms
users
fields: id | name | phone | email | password | status | created_at | updated_at
Data type: INT | VARCHAR length(255)| VARCHAR length(255) | VARCHAR length(255) | VARCHAR length(255) | INT DEFAULT(1) | TIMESTAMP DEFAULT(CURRECT_TIMESAMP) | TIMESTAMP DEFAULT(CURRECT_TIMESAMP)

    filemanagers
    id | title | description | img_link | status | created_at | updated_at

    sliders
    id | title | sub_title | img | number | num_title | status | created_at | updated_at

SQL : Structure Query Language
DDL | DML | DCL | WHERE

        CRUD SQL Ma
        Create: INSERT INTO table_name (name,phone,email,password) VALUES('variable' ....)
        Read: SELECT *FFROM 'db_name' WHERE id=1
        Read: SELECT 'name' *FFROM 'db_name' WHERE id=1
        SELECT fieeld_name FROM table_name
        SELECT fieeld_name FROM table_name WHERE condition

        Update:
        UPDATE tablename SET field_name='$variable',phone='...' WHERE id=2;

        DElete:
        DELETE FROM tablename WHERE condition;

Complete File structure of the frontend and backend development

merojob
assets
css
style.css
js
min.js
img
videos
files
inc
header.php
navbar.php
footer.php
index.php
about.php
services.php
gallery.php

    admin
        assets
            css
                style.css
            js
                min.js
            img
            files
            videos

        connection              : inside this folder we write the database and project connection code
            config.php          (connect prject and database)

        inc                     : inside this folder we keep the repeated codes
            header.php
            navbar.php
            sidebar.php
            footer.php

        loginprocess            : inside this folder, we write the login process code
            login.php
            logout.php

        uploads                 : inside this folder we store the dynamic images

        users                   : we need to create same folder and files for other process
            create.php
            index.php
            edit.php
            view.php
            delete.php

        index.php               : contain login UI
        home.php
        register.php
        profile.php
