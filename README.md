# django-ambassador
---

## Quick Start

```sh
# Start Application Server
python3 manage.py runserver

# In Browser, visit http://127.0.0.1:8000/

# With Docker:
docker-compose up
```

---

## QRH Commands

```sh
## Docker & Docker Compose ##

# Build Stack
docker-compose up --build

# Start Stack
docker-compose up

# Stop Stack
docker-compose down

---

## Migrations ##

# Localhost:
python3 manage.py makemigrations

# Container:
docker-compose exec backend sh
python manage.py migrate
```

---

## Technologies & Frameworks

- [Django](https://www.djangoproject.com/)
- [Docker](https://www.docker.com/)
- [Python](https://www.python.org/)
