release: python manage.py makemigrations --no-input
release: python manage.py migrate --no-input
release: pip3 install djangorestframework

web: gunicorn apka.wsgi