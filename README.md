# Social media app
Expense Tracker is a web application built with Django to post user media, like and comment content.
## Features
- User authentication and authorization
- Add, edit, and delete posts
- Like and comment functional
## Installation
## Prerequisites
- Python 3.8+
- PostgreSQL database
- Docker (optional, for containerized deployment)
## Steps 
1. Clone the repository:
 ```
gh repo clone anton0498/SocialMediaApp
cd social-proj
```
2. Activate a virtual environment:
   ```
   source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```
3. Configure the database settings in settings.py:
   ```
   DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql_psycopg2',
        'NAME': 'railway',
        'USER': 'postgres',
        'PASSWORD': 'LcNdWkGVvbkbkexsnuvkUsctcmyVJuLa',
        'HOST': 'roundhouse.proxy.rlwy.net',
        'PORT': '18946'
    }
   }

   ```
4. Apply the migrations:
   ``` python manage.py migrate ```
5. Create a superuser to access the admin panel:
   ```python manage.py createsuperuser```
6. Run the development server:
   ``` python manage.py runserver ```
   
