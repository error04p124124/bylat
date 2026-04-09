web: python manage.py migrate --noinput && python manage.py collectstatic --noinput && gunicorn tehsnab_warehouse.wsgi:application --bind 0.0.0.0:$PORT
