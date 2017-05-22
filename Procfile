web: gunicorn config.wsgi:application
worker: celery worker --app=nectr.taskapp --loglevel=info
