# Profiles REST API - Django

Profiles REST API course code.

# To setup vagrant
```
vagrant init
vagrant up
vagrant ssh
```

# Install requirements inside vagrant shell
```
pip install -r requirements.txt
```

# Setup django application
startproject is the argument passed to django-admin and profiles_project is the name of the application.
```
django-admin.py startproject profiles_project .
python manage.py startapp profiles_api
```

# To check changes, run the following execute_from_command_line
```
python manage.py runserver --noreload 0.0.0.0:8000
```
