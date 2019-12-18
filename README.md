# django-tutorial
This is the django tutorial from; https://docs.djangoproject.com/en/3.0/intro/
To get the server up and running, run the following in the terminal in the root directory (where manage.py is). This will get the database (sqlite) up and running;
1. ```python manage.py migrate```
2. ```python manage.py makemigrations polls```
3. ```python manage.py sqlmigrate polls 0001```
4. ```python manage.py migrate```
These steps are from; https://docs.djangoproject.com/en/3.0/intro/tutorial02/  


Notes from the docs. The order to make a database change is;
* Change your models (in models.py).
* Run ```python manage.py makemigrations``` to create migrations for those changes.
* Run ```python manage.py migrate``` to apply those changes to the database.

After this the database is up and running. New entries can be added either with the admin panel, or from the shell using;
```
$ python manage.py shell
```
