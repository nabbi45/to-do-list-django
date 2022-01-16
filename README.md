# to-do-list-django
A to do list website with CRUD operations and authentication

Steps to run the app:

1. install django (you need python 3 installed on your system to install django) using
pip install django

2. Now clone the project

3. Create a dummy project and copy the secret key from settings.py and replace '#########..' in the settings.py of the project.

4. Now migrate to prepare database using command -
python manage.py makemigrations
python manage.py migrate

5. Now create a superuser using
python manage.py createsuperuser

6. Now run the app using
python manage.py runserver
