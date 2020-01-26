# Flask [Boilerplate Code](https://appseed.us/boilerplate-code)

Playground boilerplate code used by the AppSeed community for simple web apps coded in Flask.

<br />

## Features

- UI-Ready, MIT License
- SQLite database
- SQLAlchemy ORM
- Session-Based authentication flow (login, register)

<br/>

## Sample Apps

A short-list with web apps that use this simple boilerplate:

- [Flask Material Kit](https://github.com/app-generator/flask-material-kit)
- [Flask Paper Kit](https://github.com/app-generator/flask-paper-kit)
- [Flask NowUI Kit](https://github.com/app-generator/flask-now-ui-kit)

<br />

## New Features

- How to submit a feature request

The new features, will be opened as issues labeled as enhancements and voted by the community.

- How to test a new feature

Fork the project, create a new branch and code the new module / feature  

<br />

## Help & Support

- Via eMail < [support @ appseed.us](https://appseed.us/support) > and **Github** issues tracker 
- LIVE Support via [Discord](https://discord.gg/fZC6hup)

## Build from sources

```bash
$ # Clone the sources
$ git clone https://github.com/app-generator/boilerplate-code-flask.git
$ cd boilerplate-code-flask
$
$ # Virtualenv modules installation (Unix based systems)
$ virtualenv --no-site-packages env
$ source env/bin/activate
$
$ # Virtualenv modules installation (Windows based systems)
$ # virtualenv --no-site-packages env
$ # .\env\Scripts\activate
$ 
$ # Install requirements
$ pip3 install -r requirements.txt
$
$ # Set the FLASK_APP environment variable
$ (Unix/Mac) export FLASK_APP=run.py
$ (Windows) set FLASK_APP=run.py
$ (Powershell) $env:FLASK_APP = ".\run.py"
$
$ # Set up the DEBUG environment
$ # (Unix/Mac) export FLASK_ENV=development
$ # (Windows) set FLASK_ENV=development
$ # (Powershell) $env:FLASK_ENV = "development"
$
$ # Run the application
$ # --host=0.0.0.0 - expose the app on all network interfaces (default 127.0.0.1)
$ # --port=5000    - specify the app port (default 5000)  
$ flask run --host=0.0.0.0 --port=5000
$
$ # Access the app in browser: http://127.0.0.1:5000/
```
If all goes well, we should see the app running in the browser. 
> Note: to pass the login, and unlock the private pages, please create a new user (via register page) and after, authenticate using the login page. 

![Flask Material Kit - Open-Source Web App.](https://raw.githubusercontent.com/app-generator/static/master/products/flask-material-kit-screen.png)

<br />

---
Flask [Boilerplate Code](https://appseed.us/boilerplate-code) - Provided by **AppSeed - [Web App Generator](https://appseed.us/app-generator)**. 