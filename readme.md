1. Virtual Environment  :  {environment name, venv here} a folder is created
`python -m venv {environment name}`

2. Activate Environment : (venv) appears on the command line after activation
`venv\scripts\activate`

3. Install Django :  installs the latest version of Django
`pip install django` 

4. Create Project 
`django-admin startproject {project name}`

5. Change directory to project
`cd {project name}`

6. Create an app url.py : creates new folder {appname} in flipkart
`python manage.py startapp {appname}`

7. Run server : opens live server
`python manage.py runserver` 

8. Migrations
`python manage.py makemigrations` - file+ id column
`python manage.py migrate` - database enter

9. Create superuser
`python manage.py createsuperuser`

