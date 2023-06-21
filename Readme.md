# Django: Getting Started
## Section 2: Starting a Django Project
* python -m pip install django
* django-admin startproject my-project-name
* cd my-project-name
* python manage.py runserver
## Section 3: Creating a Simple Web Page
* Creating a Django App
* python manage.py startapp website
* Adding a Page
## Section 4: Setting up a Data Model
* Running Initial Migrations 
* python manage.py showmigrations
* python manage.py migrate
* python manage.py dbshell
* sqlite> .tables
* sqlite> select * from django_migrations;
* sqlite> .exit
* python manage.py startapp meetings
* Creating a Model Class