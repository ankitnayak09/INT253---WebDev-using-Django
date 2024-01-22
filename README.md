### Create a Project
```
django-admin startproject projectname
```

A Project can contain many different applications inside it.
To create an app inside project.

### Create Apps in Project
```
cd projectname
python manage.py startapp appname
```

### Running a Server
```
python manage.py runserver
```

### Running Migration => Create the databases for all the installed apps
```
python manage.py migrate
```

### 3 Step Guide to Make Changes in Model
1. Change Your Models(models.py)
2. run ```python manage.py makemigrations``` => to create migrations for those changes
3. ```python manage.py migrate``` => to apply those changes to the database