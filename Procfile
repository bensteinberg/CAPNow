web: gunicorn firmament.wsgi --log-file -
worker: celery -A firmament worker --loglevel=info -B
