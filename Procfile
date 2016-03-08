web: gunicorn config.wsgi:application
worker: newrelic-admin run-program celery worker --app=darktalker.taskapp --loglevel=info
