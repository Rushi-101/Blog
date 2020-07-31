web: gunicorn django_web.wsgi --log-file - --log-level debug
python manage.py collectstatic --noinput
manage.py migrate