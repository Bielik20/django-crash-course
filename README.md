# Django Crash Course

Based on https://www.youtube.com/watch?v=e1IyzVyrLSU

## Setup

If no pipenv:
```
pip install pipenv
```

To setup project:
```
pipenv install
pipenv shell
python manage.py migrate # database migrations
python manage.py createsuperuser # create admin account
```

## Start dev server

To start server:
```
pipenv shell # ensure you are in pipenv shell
python manage.py runserver
```
