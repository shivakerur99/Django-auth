# django-auth-project
first make create virtualenv in django app 
creation command virtualenv authenv
then activate the env
using command authenv\Scripts\activate

then install all the packages from requirements.txt in authenv 
check pip freeze
and select which needs be installed

# run this commands

python manage.py makemigrations

python manage.py migrate

python manage.py runserver

finally run and go to this api

API=http://127.0.0.1:8000/auth/register/
