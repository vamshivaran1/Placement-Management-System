# Placement-Management-System

This is a Placement Management System written in PHP that allows you to manage the placement process of a college or university.

# Requirements
* PHP 7.4 or higher
* A web server (such as Apache or Nginx)
* A MySQL/MariaDB database
* PHP modules such as PDO, and other modules that you might need depending on your setup.
# Features
* Student registration and login
* Company registration and login
* Student profile management
* Company profile management
* Job posting by companies
* Job application by students
* Interview scheduling and management
* Offer letter generation
* Reports and statistics on placements
* Admin panel to manage all the above features
# Installation
1. Clone the repository to your local machine.
2. Create a new MySQL/MariaDB database and import the provided SQL file to create the necessary tables.
3. Modify the config.php file with your database credentials and other settings as per your requirement.
4. Set up your web server to point to the project's root directory.
5. Access the application by visiting the URL in your web browser.
# Note
* You may need to change the folder permissions to 755 or 777 in order to run the application properly.
* You might also need to change the .htaccess file to match the url structure of your server
* You should also change the salt and pepper values in the config file to add more security to your application
* This script is for educational purpose only, and you should check your company or network security policy before using it in production.
