
pgsql:
required psycopg2: pip install psycopg2-binary
open server -> postgres (user)
set password -> \password postgres
input pw ->
create db -> CREATE DATABASE portfoliodb;

for .env:
pip install django-environ
in settings import environ

searches django project searching for static dirs and adds to collective static dir:
python manage.py collectstatic