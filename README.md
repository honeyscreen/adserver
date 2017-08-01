# adserver
adserver

Create a folder named 'adserver'

```
$ mkdir workspace-adserver
$ cd workspace-adserver
```

Activate virtualenvironment 

```
$ virtualenv env
$ source env/bin/activate
```

Install django and start a project named 'adtech'

```
$ pip install django
$ pip install django-extension
$ django-admin startproject adtech
$ cd adtech
```

<2> 
Migrate DB configure & Create superuser
```
$ python manage.py migrate
$ python manage.py makemigrations adnetwork
$ python manage.py migrate
$ python manage.py createsuperuser
```
Run the server 

``` 
$ python manage.py runserver
```

Check the server that we created with the URL below 

http://localhost:8000/admin/


