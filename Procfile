web: daphne test_task.asgi:application --port $PORT --bind 0.0.0.0 -v2
worker: python manage.py runworker channels --test_task.settings -v2