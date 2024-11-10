# Persian Blog Project (Django Project)

This project is a simple and functional blog system developed with Django, fully localized in Persian. It uses PostgreSQL as the database and provides features for creating, editing, and managing articles and user comments.

## Features

- **Persian Language Support**: The project is fully localized for Persian-speaking users.
- **Article Management**: Users can create, edit, and delete articles.
- **Comment Management**: Users can post comments on articles and view others' comments.
- **Article Search**: Users can search for articles by title or category.
- **Admin Panel**: Full admin panel for managing users, articles, and comments via Django's built-in admin.
- **PostgreSQL Support**: Uses PostgreSQL for better performance and scalability.

## Prerequisites

To run this project, ensure the following are installed on your system:

- Python 3.x
- PostgreSQL
- pip (Python package manager)
- virtualenv (optional, for creating a virtual environment)

## Database Configurations

In the settings.py file, update the PostgreSQL database settings with your database information as follows:

<pre markdown="1">
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': 'your_database_name',
        'USER': 'your_database_user',
        'PASSWORD': 'your_database_password',
        'HOST': 'localhost',
        'PORT': '5432',
    }
}
</pre>
