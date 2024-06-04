web: gunicorn hpr.wsgi:application --log-file - --workers 12 --timeout 1000
release: python manage.py migrate
