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

## Creating nav bar and footer
1. create base.html in core/template/core and cut paste all items from index.html
2. use block and extend to use base.html in every file.
3. create a new function in views.py for contact and render it to contact.html
4. create a contact page and add an h1.
5. add url as contact/ in urls.py.
6. create a nav bar in base.html.
7. create a footer in base.html
8. python3 manage.py runserver

## Creating category and items
1. python3 manage.py startapp item
2. In settings.py add item in installed_app
3. python3 manage.py createsuperuser
4. In models.py of item create a table for item and a table for category
5. pip install pillow
6. python3 manage.py makemigrations
7. python3 manage.py migrate
8. in admin.py of item add category and item using register method
9. python3 manage.py runserver
10. go to /admin, write password and username.
11. add items and categories