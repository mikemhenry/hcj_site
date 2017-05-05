web: gunicorn config.wsgi:application
worker: celery worker --app=handycodejob.taskapp --loglevel=info
