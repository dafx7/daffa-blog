# My Personal Blog Website.
* https://daffa-blog.up.railway.app/
* An End-to-End application, managed from development through deployment to production.


## Functionality
* Users need to register/login in order to comment on posts.
* Passwords are securely encoded with hashing and salting functions of the werkzeug.security package.
* User authentication is done with a flask_login object
* Only Admin users can create and delete posts.
* Users can get in contact with the the owner(me) by sending a message, which gets transferred via email over a SMTP client session object.
* The App makes use of CKEditor (for creating posts and comments); a WYSIWYG rich text editor which enables writing content directly inside of web pages/online applications.
* (Production) WSGI server is setup with Gunicorn to run the Live Python Application on Railway. PostgreSQL database is used for production.
* (Development) Development and testing is done locally with a SQLite database.

## Topics covered

* Python, HTML, CSS, Railway, SQL
* Flask Web Framework 
* SQL Databases
* Decorators
* OOP
* Functions

## Packages
* See requirements.txt for all packages and dependencies used.
