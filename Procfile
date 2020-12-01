release: pip install djangorestframework
release: python apka/manage.py makemigrations --no-input
release: python apka/manage.py migrate --no-input


web: python apka/manage.py runserver 0.0.0.0:5000