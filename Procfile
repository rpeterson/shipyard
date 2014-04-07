web: gunicorn shipyard.wsgi:application
worker: celery worker --beat --app shipyard --loglevel info