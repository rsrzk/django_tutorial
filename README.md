This repository is for following Dave Gray's Django tutorial on Youtube https://www.youtube.com/watch?v=Rp5vd34d-z4

Stopped at 2.52.00

Resources for the tutorial can be found here https://github.com/gitdagray/django-course

How to for venv:

- to create venv: `py -m venv .venv`
- to activate venv: `source .venv/Scripts/activate`
- to deactivate venv: `deactivate`

How to for Django

- to install Django `py -m pip install Django`
- to create new project `django-admin startproject myproject`
- to run Django `py manage.py runserver`
- to quit the server `CTRL + c`
- to create new app `py manage.py startapp <name>` e.g. new app named posts `py manage.py startapp posts`
- to migrate database `py manage.py migrate`
- for new migration, need to first make migration `py manage.py makemigrations`
- get list of commands `py manage.py`
- to access application shell `py manage.py shell`
- to exit shell `exit()`
- create super user `py manage.py createsuperuser`
- super user credentials (user: rais, pass: raistest)