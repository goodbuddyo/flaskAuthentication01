# flaskAuthentication01

based on Flask 1 Users, Sessions, and Authentication by Mateo Prigl
app.pluralsight.com/library/courses/flask-users-sessions-authentication/description

Note: the exercise files for this are set up in individual example folders (apparently no end final product folder)

Steps
python -m venv .venv
source .venv/bin/activate
(.venv) $ flask --version
  Python 3.8.13
  Flask 2.3.3
  Werkzeug 2.3.7

pip install -r requirements.txt

flask --app app run --debug -h localhost -p 5555
getting error 
__init__.py", line 3, in <module>
    from flask_sqlalchemy import SQLAlchemy
ModuleNotFoundError: No module named 'flask_sqlalchemy'


pip install -U Flask-SQLAlchemy



