release: python manage.py makemigrations base_app
release: python manage.py migrate

web: gunicorn todo_proj.wsgi
