# Packages

Django==5.0.6
djangorestframework==3.15.1
python-dotenv
python-dotenv==1.0.1
pytest==8.2.2
pytest-django==4.8.0
black==24.4.2
flake8==7.0.0
django-mptt==0.16.0
rf-spectacular==0.27.2

# Commands

django-admin startproject pharmacy

./manage.py runserver

from django.core.management.utils import get_random_secret_key

./manage.py spectacular --file schema.yml

# Added 'rest_framework' to the installed_app in base.py

# Pytest
pytest -h # prints options _and_ config file settings