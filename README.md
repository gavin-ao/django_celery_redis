# django_celery_redis
dynamic modify scheduler in celery with django and redis

create admin user

```python
python manage.py createsuperuser --username=yetship --email=liqianglau@outlook.com
```

run worker:

```python
celery -A proj worker -l info
```

run server:

```python
python manage.py runserver 0.0.0.0:8000
```
