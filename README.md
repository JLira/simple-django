# simple-django
Example of a simple project with Django

## How execute the project

* Clone this repositoy
* Create a vitualenv with Python 3.
* Activate the virtualenv
* Install the dependencies
* Run the migrations

```
git clone git@github.com:JLira/simple-django.git
cd simple-django
python3 - m venv .venv
source .venv/bin/activate
pip install -U pip && pip install django dj-database-url python-decouple django-extensions
pip freeze > requirements.txt
pip install -r requirements.txt
python contrib/env_gen.py
python manage.py migrate
```
