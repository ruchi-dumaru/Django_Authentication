# Django Setup Notes

This file is a reminder of how I connected everything in my Django project.

1. Install Django  
   ```bash
   pip install django

2. Start new app
   python manage.py startapp auth_app

3. Add App to Project
   Go to settings.py inside the main project (auth_project) and add the app name:
   INSTALLED_APPS = [
    ...,
    'auth_app',
]


4. auth_app/
  ├── templates/
  │     ├── auth/
  │     │    └── register.html      # registration page
  │     └── layouts/
  │           └── app.html          # base layout
  ├── urls.py                       # app-level urls


5. Database Setup
   Make migration
     python manage.py makemigrations


6. Apply migrations
     python manage.py migrate




