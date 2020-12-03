release: pip install djangorestframework
release: python apka/manage.py makemigrations --no-input
release: python apka/manage.py migrate --no-input


web: gunicorn api_basic.wsgi