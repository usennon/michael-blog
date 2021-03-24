<h1>My Personal Blog Website.</h1>
<ul>
  <li>https://mikhail-blog.herokuapp.com</li>
  <li>An End-to-End application, managed from development through deployment to production.</li>
</ul>
<h1>Functionality</h1>
<ul>
  <li>Users need to register/login in order to comment on posts.</li>
  <li>Passwords are securely encoded with hashing and salting functions of the werkzeug.security package.</li>
  <li>User authentication is done with a flask_login object.</li>
  <li>Only Admin users can create and delete posts.</li>
  <li>Users can get in contact with the the owner(me) by sending a message, which gets transferred via email over a SMTP client session object.</li>
  <li>The App makes use of CKEditor (for creating posts and comments); a WYSIWYG rich text editor which enables writing content directly inside of web pages/online applications.</li>
  <li>(Production) WSGI server is setup with Gunicorn to run the Live Python Application on Heroku. PostgreSQL database is used for production.</li>
  <li>(Development) Development and testing is done locally with a SQLite database.</li>
</ul>
<h1>Topics covered</h1>
Python, HTML, CSS, Heroku, SQL,
Flask Web Framework,
SQL Databases,
Decorators,
OOP,
Functions
<h1>Packages</h1>
See requirements.txt for all packages and dependencies used.
