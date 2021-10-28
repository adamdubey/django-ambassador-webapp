# django-ambassador-webapp
---

## Quick Start

```sh
# Start Application Workload Stack
docker-compose up

# In Browser, visit http://127.0.0.1:8000/
# Stop Stack
docker-compose down

---

## Migrations ##

# Localhost:
python3 manage.py makemigrations

# Container:
docker-compose exec backend sh
python manage.py migrate

## User Manager ##
docker-compose exec backend sh
python manage.py createsuperuser --email=dev@dev.com
```

---

## Technologies & Frameworks

- [Django](https://www.djangoproject.com/)
- [Docker](https://www.docker.com/)
- [Python](https://www.python.org/)
