# Flask-basic-auth

### Dependencies
- Flask is a simple, easy-to-use microframework for Python that helps you build scalable and secure web applications.
- Flask-Login provides user session management for Flask. It handles the common tasks of logging in, logging out, and remembering your users’ sessions over extended periods of time.
- Flask-Bcrypt is a Flask extension that provides bcrypt hashing utilities for your application.
- Flask-WTF is a simple integration of Flask and WTForms that helps you create forms in Flask.
- Flask-Migrate is an extension that handles SQLAlchemy database migrations for Flask applications using Alembic. The database operations are made available through the Flask command-line interface.
- Flask-SQLAlchemy is an extension for Flask that adds support for SQLAlchemy to your application. It helps you simplify things using SQLAlchemy with Flask by giving you useful defaults and extra helpers that make it easier to perform common tasks.
- Flask-Testing extension provides unit testing utilities for Flask.
- Python Decouple helps you use environment variables in your Python project.

### Get Started
1. We are going to create a virtual environment using venv. Python now ships with a pre-installed venv library. 
- `python -m venv env`

2. Now, we need to activate the environment using this command:
- `source env/bin/activate`

3. To install the above-mentioned libraries:
- `pip install Flask Flask-Login Flask-Bcrypt Flask-WTF FLask-Migrate Flask-SQLAlchemy Flask-Testing python-decouple`

4. To initialize the database (create a migration repository), use the command:
`flask db init`

5. To migrate the database changes, use the command:
`flask db migrate`

6. To apply the migrations, use the command:
`flask db upgrade`

7. To run your application using the command:
`python manage.py run`

8. you can run all the tests using the command:
`python manage.py test`

9. To create an Admin user:
`python manage.py create_admin`