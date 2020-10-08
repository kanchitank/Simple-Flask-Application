# FLASK

## What is Flask?

<img src = "https://miro.medium.com/max/4096/1*tJbEjxx-ne6uUzCbqueIWg.png" width="70%">

### [Flask](https://flask.palletsprojects.com/en/1.1.x/) is a web application framework written in Python.
This means flask provides you with **tools, libraries and technologies** that allow you **to build a web application**. <br>
This web application can be some web pages, a blog, a wiki or go as big as a web-based calendar application or a commercial website. <br>

Flask is part of the categories of the micro-framework. Micro-framework are normally framework with little to no dependencies to external libraries. This has pros and cons. Pros would be that the framework is light, there are little dependency to update and watch for security bugs, cons is that some time you will have to do more work by yourself or increase yourself the list of dependencies by adding plugins. In the case of Flask, its dependencies are:

- **Werkzeug** a WSGI utility library
- **Jinja2** which is its template engine

### WSGI
**[WSGI](https://werkzeug.palletsprojects.com/en/1.0.x/)** stands for **"Web Server Gateway Interface"**. It is used to forward requests from a web server (such as Apache or NGINX) to a backend Python web application or framework. From there, responses are then passed back to the webserver to reply to the requestor.
<br><br><br>
<img src = "https://lwstatic-a.akamaihd.net/kb/wp-content/uploads/2019/09/WSGI.png" width="50%">
<br>

### Jinja2
**[Jinja](https://jinja.palletsprojects.com/en/2.11.x/)** is a modern and designer-friendly templating language for Python, modelled after Django’s templates. It is fast, widely used and secure with the optional sandboxed template execution environment.

<br><br>

## Prerequisites for the better understanding of Flask
- **Python**
- **HTML**

<br><br>

## Installation of FLASK

### A simple application in flask
We are going to perform a very basic application with flask.
<br><br>

## Step 1: Install latest version of [Python](https://www.python.org/downloads/windows/) 
<br>

## Step 2: Creation of a directory and virtual environment
Type the following commands in the command prompt.
<br>

<img src = "https://user-images.githubusercontent.com/65490196/95449893-08ec4600-0983-11eb-84da-a70230d4ad13.png" width="50%">

The above command **"py -3 -m venv venv"** is for virtual environment creation.
<br><br>

## Step 3: Activation
Now type the following command in the command prompt to activate the virtual environment.
<br>

<img src = "https://user-images.githubusercontent.com/65490196/95450216-992a8b00-0983-11eb-892f-28245fb0ca46.png" width="50%">

<br>

## Step 4: Install FLASK
<br>

<img src = "https://user-images.githubusercontent.com/65490196/95450720-5321f700-0984-11eb-844f-d95a642101f8.png" width="100%">

<br>

## Step 5: Creation of the application using a text editor
After completing the installation, let’s get our hands on the code.
<br>

<img src = "https://user-images.githubusercontent.com/65490196/95452767-66829180-0987-11eb-97b6-28a65a3c5d93.png" width="70%">

<br>

## Step 6: Create a HTML login page
Below is source code of the file.
<br>

<img src = "https://user-images.githubusercontent.com/65490196/95453188-06401f80-0988-11eb-93c7-811dd9e52938.png" width="70%">

<br>

## Step 7: Set FLASK_APP and run the flask
<br>

<img src = "https://user-images.githubusercontent.com/65490196/95452916-a2b5f200-0987-11eb-85d6-7f0a0c2b2389.png" width="70%">

<br>

## Step 8: Open login.html in the browser
After the development server starts running, open login.html in the browser, **enter Name** in the text field and **click Submit** button. <br>
<br>

![image](https://user-images.githubusercontent.com/65490196/95446723-4ef2db00-097e-11eb-8f87-a4dd8ea1379f.png)

<br>

### The output would be the following:
<br>

![image](https://user-images.githubusercontent.com/65490196/95446780-64680500-097e-11eb-8443-02bbc8ac3524.png)

### And we're done! We've successfully created a simple application in FLASK!
