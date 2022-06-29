release: python manage.py makemigrations --noinput
release: ./manage.py makemigrations core --noinput
release: ./manage.py makemigrations --noinput
release: ./manage.py migrate auth --noinput
release: python manage.py migrate --noinput --run-syncdb
release: python manage.py collectstatic  --noinput
web: gunicorn app.wsgi
