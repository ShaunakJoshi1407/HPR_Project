web: gunicorn hpr.wsgi:application --log-file - --workers 6 --timeout 1000
release: python manage.py migrate
