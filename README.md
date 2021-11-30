# django-ambassador-webapp
---

## Quick Start

```sh
# Start Application Stack
docker-compose up

# In Browser, visit http://127.0.0.1:8000/
```

---

## QRH Commands

```sh
## Docker & Docker Compose ##

## Build Stack ##
docker-compose up --build

## Start Stack ##
docker-compose up

## Stop Stack ##
docker-compose down


## Migrations ##
docker-compose exec backend sh
python manage.py makemigrations
python manage.py migrate


## User Manager ##
python manage.py createsuperuser --email=dev@dev.com


## Administrator Manager ##
python manage.py startapp administrator
python manage.py startapp common
python manage.py startapp ambassador

## Faker User Data Generation##
python manage.py populate_ambassadors
```

---

## Technologies & Frameworks

- [Django](https://www.djangoproject.com/)
- [Docker](https://www.docker.com/)
- [Python](https://www.python.org/)
- [React.js](https://reactjs.org/)
- [Redis](https://redis.io/)
