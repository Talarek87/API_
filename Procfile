release: python apka/manage.py makemigrations --no-input
release: python apka/manage.py migrate --no-input

web: gunicorn apka.wsgi