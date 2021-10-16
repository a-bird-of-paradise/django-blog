# django-blog

To create this I did the following:

* Copied the `.gitignore` from the previous repo
* Used `pipenv` to install `django~=3.1.0`, `'environs[django]~=8.0.0'`, and `psycopg` (think I need `gunicorn` but later)
* Entered the `pipenv shell` and did `django-admin startapp config .`
* Copied `.env` from a previous project, regenerated a secret key
* Created a new DB in postgres and put that in the `.env` too 
* Amended `settings.py` to grab stuff from the environment
* `python manage.py startapp blog`
* and then `migrate`
* and then `runserver`

and it worked! 
