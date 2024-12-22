# Projeto 1 - Curso de Django (Storyline)

This readme presents the storyline of all content related with project 1. if you are searching for the documentation of the current project such as use case, sequence diagrams, take a look at: 

> docs > main

## Section 4
In this section, the teacher covers the following topics:
- starting a project
- configuring a .gitignore file for django projects
- runnning a django development server

<details>
    <summary>Annotations in deep</summary>
    Annotations
    The commands below were used to complete this class

> django-admin --help

    The command above is used to see all initial commands available in django, when we are starting a project.

> django-admin startproject project_name .

    The command above is used to create a Django project. Adding a . (dot) after the project name specifies the current folder as the root directory for the project.

> python manage.py runserver

    Start the development server of django project.

</details>


## Section 5 - Djnago URLs, View e Templates

[description of the class]

<details>
    <summary>Annotations in deep</summary>

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

Creating a page in django and working with paths

```python
from django.contrib import admin
from django.urls import path

def my_view(request):
    """
    This is not the best method to define a function, the best way is to apply it in an app. But here, all function related with path (declared inside urlpatterns), they require an argument, which is "request"

    Also, these function need to return a http response
    """
    pass

urlpatterns = [
    path('admin/', admin.site.urls),
    path('about/', my_view) # The path function receives a string for the path and a function (which return a httpresponse)
]
```
</details>