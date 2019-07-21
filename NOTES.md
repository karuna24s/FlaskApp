# Creating a Web App From Scratch Using Python Flask and MySQL
1. Setup Flask in app.py
2. Create a homepage using Bootstrap and import render_template in app.py.
3. Create a signup homepage
   - Setting up the database using MySQL
    1. Create Database
    2. Create Table
    3. Create Stored Procedure
   - Create a signup interface
    1. Create signup.html file
    2. Create a css file
    3. Add showSignUp method to render the signup page once a request comes to
       /showSignUp in app.py.
   -  Implement a Signup method
    1. Implement a signUp method in app.py for the UI to interact with the MySQL
       database, using jQuery AJAX to post our signup data to the signUp method,
       and import request from Flask.
    2. Import json from Flask, since we want to return json data.
