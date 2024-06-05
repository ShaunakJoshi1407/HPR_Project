web: gunicorn hpr.wsgi:application --log-file - --workers 2 --timeout 1200
release: python manage.py migrate
