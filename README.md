# Polls App

A simple polls app built with [django](https://www.djangoproject.com/start/).

## Tech

* [Python 3.11.0](https://www.python.org/)  
* [Django-4.2.1](https://www.djangoproject.com/)  
* [SQLite3](https://sqlite.org/index.html)
* [Bootstrap5](https://pypi.org/project/django-bootstrap5/)
  * [GitHub](https://github.com/zostera/django-bootstrap5)
  * [Website](https://getbootstrap.com/docs/5.3/getting-started/introduction/)
* [Python-Dotenv](https://github.com/theskumar/python-dotenv)

## Useful Commands

`py manage.py runserver` // run server  
`python manage.py test polls` // run tests  
`python -m pip install &#60;dependency&#62;` // install [dependencies](https://djangopackages.org/)  

`python manage.py makemigrations &#60;app_name&#62;` // create migrations  
`python manage.py migrate` // apply changes  
`python manage.py sqlmigrate &#60;app_name&#62; &#60;number&#62;` // view migration  
`python manage.py check` // check for issues  
`py manage.py check --deploy` // check for security issues
`python manage.py shell` // open python shell (exit() to close)  

## Environment Variables

Set them in .env or like so:
`set "SECRET_KEY=<key>" && set IS_PRODUCTION_ENVIRONMENT=true` (Windows) ||  
`export SECRET_KEY='<key>' IS_PRODUCTION_ENVIRONMENT=true` (Linux)
