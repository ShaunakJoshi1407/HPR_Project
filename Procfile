web: gunicorn hpr.wsgi:application --log-file - --workers 5 --timeout 300
release: python manage.py migrate
