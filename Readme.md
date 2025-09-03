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
   


4. auth_app/
    -templates/
      - auth/
         -register.html    
     -layouts/
         -app.html          
       -urls.py             


5. Database Setup
   Make migration
   ```bash
     python manage.py makemigrations


7. Apply migrations
     python manage.py migrate




