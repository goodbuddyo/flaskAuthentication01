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
# note needed to remove this requirement line - see course discussion
# pkg-resources==0.0.0
# also in requirements, change to WTForms==3.0.0
# w/ v 2.3.1 could not - from wtforms.fields import EmailField

flask run -p 5555  --debugger



Internal Server Error
The server encountered an internal error and was unable to complete your request. Either the server is overloaded or there is an error in the application.

20231128
going to pause this project to see if Django offers a simpler email/authentication option
