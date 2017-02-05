web: gunicorn config.wsgi:application
worker: celery worker --app=portfolio.taskapp --loglevel=info
