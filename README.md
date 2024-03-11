# Dockerizing Django Application

This repository contains a Dockerfile and docker-compose.yml file to Dockerize a Django application.

## Prerequisites

Before you begin, ensure you have the following installed on your local machine:

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Getting Started

### 1. Clone the Repository:

```bash
git clone https://github.com/TuanFaiedAhamadh/django-backend.git
cd django-backend
```

Create a .env file in the project root and set necessary environment variables. You can use .env.example as a reference.

### 2. Build the Docker containers:
```bash
docker-compose build
```

### 3. Run the migrations:
```bash
docker-compose run web python manage.py migrate
```
## Usage
Development
To start the development server, run:
```bash
docker-compose up
```
Access the Django development server at http://localhost:8000.








