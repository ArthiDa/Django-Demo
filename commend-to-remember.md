Here are some commonly used Django commands and their purposes:

1. `django-admin startproject <project_name>`:
   This command creates a new Django project with the specified name. It will generate the necessary directory structure and files for the project.

2. `python manage.py runserver`:
   This command starts the development server, allowing you to run your Django project locally. It will listen for incoming requests and serve your application.

3. `python manage.py startapp <app_name>`:
   This command creates a new Django app within your project. An app is a self-contained module that encapsulates a specific functionality of your project.

4. `python manage.py makemigrations <app_name>`:
   By running makemigrations, you’re telling Django that you’ve made some changes to your models (in this case, you’ve made new ones) and that you’d like the changes to be stored as a migration.

5. `python manage.py sqlmigrate <app_name> 0001`:
   The sqlmigrate command doesn’t actually run the migration on your database - instead, it prints it to the screen so that you can see what SQL Django thinks is required. It’s useful for checking what Django is going to do or if you have database administrators who require SQL scripts for changes.

6. `python manage.py migrate`:
   This command applies any pending database migrations to your project. Migrations are used to manage changes to your database schema.

7. `python manage.py createsuperuser`:
   This command creates a superuser account for the Django admin interface. Superusers have full access to the admin site and can perform administrative tasks.

8. `python manage.py shell`:
   This command opens up a Python shell with the Django environment loaded. It allows you to interactively work with your Django models and perform database operations.

9. `python -m pip install django-debug-toolbar`:
   Installing Django Debug Toolbar

Remember to replace `<project_name>` and `<app_name>` with the actual names you want to use.
