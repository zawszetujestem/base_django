# Django base

## Commends
- django-admin - check if django works fine
- django-admin startproject 'name' - create folder with project name and some base staff inside
- python manage.py runserver (in base project package) - run project
    - gives us two pages: 127.0.0.1:8000 and /admin
- python manage.py startapp 'name' - create 'name' package with base file structure


## Base set up files for project
- manage.py - never touch this file
- wsgi.py - web server django set up
- urls.py - url system file
    - list of urls path
- settings.py - main configuration of file
    - database set up
    - installed apps list
    
## Base set up files for app
- admin.py - admin panel
- apps.py - 
- models.py - build database with database class objects
- tests.py - 
- views.py - functions/ classes to represents pages of our app

## Create app
- create urls.py in app package
- create function in views.py
- put paths to functions in app/urls.py
    - path('exact url path', path to function),
- need to use include fn in base urls.py
