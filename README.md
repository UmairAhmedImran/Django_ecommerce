# Django_ecommerce
Creating an e-commerce website with django and tailwindcss

PREREQUISITE
Python should be installed

## creating a virtual environment and starting project
1. python3 -m venv env 
2. source env/bin/activate
3. pip install django
4. django-admin startproject puddle
5. python3 manage.py runserver

## Creating a core app
1. python manage.py startapp core
2. add the app core to installed apps in setting.py in puddle
3. in views.py create an index function which render core/index.html
4. create templates directory in core
5. in templates make core directory and create index.html
6. add basic html and tailwindcss cdn script
7. add the url in puddle urls.py with index function.
8. python3 manage.py runserver