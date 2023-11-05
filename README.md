# miniproject4JI
Advanced Python class project 4

## Project Comments in miniproject4JI directory under __init__.py and here
    # INF601 - Advanced Programming in Python
    # Jasmine Irvin
    # Mini Project 4

## Description
This project will be using Django to create a simple application for this project module. 
It makes use of Python, Django, and Bootstrap CSS. 

## Pip Install Instructions
It is essential you run this command so all the required installs are imported to your computer.
```
pip install -r requirements.txt
```

## Database
For the database you need to run: 
```
python manage.py makemigrations
```
Then:
```
python manage.py migrate
```
Finally:
```
python manage.py createsuperuser
```

This will create any SQL entries that need to go into the database, apply the migrations, and finally create an 
administrator login for the admin side of the project