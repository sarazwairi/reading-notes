# Django Custom User

## Setup:

```
$ mkdir django-custom-user-model && cd django-custom-user-model
$ python3 -m venv env
$ source env/bin/activate

(env)$ pip install Django==3.2.2
(env)$ django-admin startproject hello_django .
(env)$ python manage.py startapp users
```


* AbstractUser: Use this option if you are happy with the existing fields on the User model and just want to remove the username field.

* AbstractBaseUser: Use this option if you want to start from scratch by creating your own, completely new User model.

## Superuser

```
$ python manage.py createsuperuser
```
