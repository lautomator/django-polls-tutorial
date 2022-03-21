# Django Tutorial

This tutorial is written for Django 4.0, which supports Python 3.8 and later. If the Django version doesn’t match, you can refer to the tutorial for your version of Django by using the version switcher at the bottom right corner of this page, or update Django to the newest version. If you’re using an older version of Python, check [What Python version can I use with Django?](https://docs.djangoproject.com/en/4.0/faq/install/#faq-python-version-support) to find a compatible version of Django.

## Polls App

[Full tutorial](https://docs.djangoproject.com/en/4.0/)

## Commands

get all of the manage.py commanes:
    `python manage.py help`

start a project: 
    `django-admin startproject <project_name>`

run the server: 
    `python manage.py runserver`

create an app: 
    `python manage.py startapp <app_name>`

after creating or editing models:
    `python manage.py makemigrations <app_name>`
    
    `python manage.py migrate`
    
use the shell:
    `python manage.py shell`

admin create a superuser:
    `python manage.py createsuperuser`
