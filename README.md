# AUTHENTIKIT
Authentication for PHP projects. A good startingpoint for projects that need a secure user authentication
Contains:
-Signup with email confirmation using Sendgrid or Brevo
-Password reset using Sendgrid or Brevo
-Login, signup and reset monitoring using IFTTT and Slack (optional)
-Admin dashboard
-Bootstrap 5 css
-vanilla JS

Requirements:
PHP 8.1
MYSQL

Installation:
Setup an account with Sendgrid or Brevo and copy the necessary api keys
Copy files to server
Set variables in settings file
Create a table 'users' in MYSQL
Create the fields that are in the file 'table.php' in the table 'users'
Fire setup.php and setup admin user
Delete setup.php
Delete table.php
Good to go!

