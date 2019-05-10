#   F l a s k - M y S Q L  by RoBz 2019

# Install Python 3.7.xx

# Install IDE
Install any IDE you like as longest you can edit files with it it will work......

# Install Flask
* pip install Flask
* python -m pip install --upgrade pip

# Install PyMysql
pip install pymysql

# Create a project folder
Create a new project folder for storing files for this project.....

# Create a python file adn edit
* vi app.py
from flask import Flask
app = Flask(__name__)
@app.route('/test')
def test():
    return 'Flask is working'

#Just to verify that Flask is working
* cd dir_for_py_files_on_your_computer_for_this_purpose

* python -m flask run

* Flask-MySQL> python -m flask run
  Environment: production
  WARNING: Do not use the development server in a production environment.
   Use a production WSGI server instead.
   Debug mode: off
   Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)

# Open a webbrowser and surf to http://127.0.0.1:5000/test
