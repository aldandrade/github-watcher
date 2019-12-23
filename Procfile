web: gunicorn github_aldant.wsgi --chdir backend --limit-request-line 8188 --log-file -
worker: celery worker --workdir backend --app=github_aldant --loglevel=info
