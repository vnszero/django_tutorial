
# Quick Start

- Make sure you already have python and pip installed
$ mkdir env

# Virtual Enviroment (optional)

$ pip install virtualenv

$ virtualenv env/mysite

Tip: 'mysite' is the name chosen for this project

# install Django
$ pip install django

## To activate the enviroment (if using Virtual Enviroment)

$ source env/mysite/bin/activate

Tip to finish the service: $ deactive

# New Project
$ django-admin startproject mysite

# Let's Run and Test
$ cd mysite

$ python manage.py runserver
- search for the localhost:8000 on you web browser
Tip to stop service: Ctrl + c

# Creating an App
$ python manage.py startapp main

Tip: 'main' is the chosen name for this app