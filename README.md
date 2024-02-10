# blog-app_django
This is a blog app that is built with Django. For reference.

## Initial Setup
Run these
```bash
    % python3 -m venv .venv
    % source .venv/bin/activate
    (.venv) % python3 -m pip install django~=4.0.0
    (.venv) % django-admin startproject django_project .
    (.venv) % python3 manage.py startapp blog
    (.venv) % python3 manage.py migrate
```