Lab and course project related files.

projektni_zadatak.zip contains both the inventory main folder and an SQL databse with users and components. It is the final project ready for grading. Written in VSCode and relies on XAMPP for MySQL and Apache servers. To run extract the .zip folder into
xampp/htdocs then open phpMyAdmin and impoert the existing database. In browser (your favorite one) type url: http://localhost/inventory, it will redirect you to login page. 
Username:'admin', Password: 'password' or
Username:'user',  Password: 'password' 
Database uses hashed passwords so if you use phpMyAdmin you need to add an admin and remeber the password then login with the admin you created.


In short, the web app is intended to be used as electrical component inventory for faculty and students, admin adds
other users and admins. No direct user registration since the inventory is not ment to be publicly available. 
Project is written using php, html and CSS for styling with a bit of JavaScript for disapearing popup messages.
Database uses 2 tables, one for inventory and one for users.


