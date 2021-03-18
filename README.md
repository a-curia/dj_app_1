# Django project #

- install module that will allow us to create virtual environments
> pip install virtualenv



- create new virtual environment in the current project folder and put this environment into venv folder
> python -m venv venv


- to turn ON our virtual environment
> source venv/Scripts/activate




- if we check what is installed in our venv we should see it's empty
> pip freeze



- then we can install Django
> pip install django




- then inside this folder we can create a new django project
> django-admin.py startproject stocks



- inside the stocks project we will have another project named stocks and manage.py file



- we can start the project from this folder using
> python manage.py runserver


- django web project should work on localhost:8000

- to setup admin database we must do migrate and apply migration
- to migrate we must run
> python manage.py migrate

- next we will create a admin user
> python manage.py createsuperuser
