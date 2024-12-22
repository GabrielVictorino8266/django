# Projeto 1 - Curso de Django (Storyline)

This readme presents the storyline of all content related with project 1.

## Section 4
In this section, the teacher covers the following topics:
- starting a project
- configuring a .gitignore file for django projects
- runnning a django development server

### Annotations
The commands below were used to complete this class

> django-admin --help

The command above is used to see all initial commands available in django, when we are starting a project.

> django-admin startproject project_name .

The command above is used to create a Django project. Adding a . (dot) after the project name specifies the current folder as the root directory for the project.

> python manage.py runserver

Start the development server of django project.

## Section 5 - Djnago URLs, View e Templates

> .mypy_cache

This folder contains the cache of mypy, whici is used to autocomplete the code.

> db.sqlite3

This is our database

The folder "projeto", is the python module, which contains a lot of files. Let's see:

> mange.py and settings.py

These files are related, where the manage.py define a environmet variable to locate the settings.py, whre, by the time, has all configs tha django are running currently.

> asgi.py &
> wsgi.py

Both files are used to deployment on production server.

> urls.py

The url that person type, this file will apply the configs for each app created.