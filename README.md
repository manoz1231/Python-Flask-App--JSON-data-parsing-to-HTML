# Python-Flask-App--JSON-data-parsing-to-HTML

The basic plan of the project is to create a Python Flask Application and the data for the python flask application provided by the JSON data.
Where in JSON file we will provide all the data as objects (which includes Heading, Paragraphs, Images and URL's..).

These JSON data is called by the HTML file with the JSON object we defined in the flask-app.py file.

Flask is a micro web framework written in Python.
We have used Flask module which is classified as a microframework because it does not require particular tools or libraries. Flask supports extensions that can add application features as if they were implemented in Flask itself. 

We have used render_template module for calling the HTML files within the templates folder in the project folder. Where we using the HTML template for the application.

# Prerequisites for running the application.

You need to install Python on you machine Python version 3.5.

For Windows:
You can download the Python3.5 from the below URL:
  https://www.python.org/downloads/release/python-357/
  
For Linux:
You can follow the steps for the Python installation on Linux environment from below URL:
  https://tecadmin.net/install-python-3-5-on-ubuntu/

We need to install following pip packages for application to run.

>> pip install flask

>> pip install json

>> pip install render_template

# Running the Python application 

Change to the project directory in Windows or Linux environment.

On Linux:
$ git clone 
$ cd ~/Python-Flask-App--JSON-data-parsing-to-HTML/
$ python flask-app.py

On Windows:
> Open RUN and type CMD.exe and hit enter.
> Command window will be opened.
> Now change to the project location where the project is downloded.
> Now run the below command:
    >> python flask-app.py
> You will find the promt as something like below:
     * Serving Flask app "flask-app" (lazy loading)
     * Environment: production
        WARNING: Do not use the development server in a production environment.
         Use a production WSGI server instead.
     * Debug mode: off
     * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
    
# Open your bowrser and go to http://localhost:5000 to access you Python FLask Application.     
    
    
