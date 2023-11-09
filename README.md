# AUTHENTIKIT --coming soon!--
Authentication for PHP projects. A good starting point for projects that need a secure user authentication with reliable email delivery.  

Demo: https://demo.oicolev.com/authentikit  
License: GPLv3


Contains:  
-Signup with email confirmation using Sendgrid or Brevo  
-Password reset using email confirmation using Sendgrid or Brevo  
-Login, signup and reset monitoring using IFTTT and Slack (optional)  
-Admin dashboard  
-Bootstrap 5 css  
-vanilla JS  

Requirements:  
PHP 8.1  
MYSQL  

Installation:
1. Setup an account with Sendgrid or Brevo and copy the necessary api keys  
2. Copy files to server  
3. Set variables in settings file  
4. Create a table 'users' in MYSQL  
5. Create the fields that are in the file 'table.php' in the table 'users'  
6. Fire setup.php and setup admin user  
7. Delete setup.php  
8. Delete table.php  
9. Good to go!

Login, signup and password reset monitoring through Slack can be setup by following the below steps:

