# django_simple_api
Simple API using Django

# Goals
- Understand how Django works and how to create a simple api using Django
- Create CI/CD using GitHub Actions
- Set up a production ready app in Django and deploy it to Kubernetes _(still to decide)_

# How to run

### Install poetry
    curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py | python -

### Install dependencies
    poetry install

### Run all the migration
    python manage.py makemigrations

### Run the app
    python manage.py runserver
    
## Or instead just run docker compose
    docker-compose up

The app will be running on you local 8000 port: http://0.0.0.0:8000/
