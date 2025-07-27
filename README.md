# djangoweb
Install Python - Any version ( 3.*)
python -m venv env
source env/Script/activate
pip install -r requirements.txt
django-admin createproject projectname
cd projectname
python manage.py runserver

Manage Models:
python manage.py makemigrations
python manage.py migrate

Create super user
django-admin -> click enter
django-admin createsuperuser -> click enter -> Provide name, email and password

