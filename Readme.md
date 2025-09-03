# Django Setup Notes

This file is a reminder of how I connected everything in my Django project.

1. Install Django  
   ```bash
   pip install django

2. Start new app
    ```bash
     python manage.py startapp auth_app

3. Add App to Project
   Go to settings.py inside the main project (auth_project) and add the app name..
   


1. auth_app/
   1. templates/
      1. auth/
         1. register.html
   2. layouts/
      1. app.html
   3. urls.py
          


5. Database Setup
   Make migration
   ```bash
     python manage.py makemigrations


7. Apply migrations
8. ```bash
     python manage.py migrate




