# Basic CRUD App with Flask and PostgreSQL

## Overview
This application demonstrates basic CRUD (Create, Read, Update, Delete) operations using Flask, SQLAlchemy, and PostgreSQL. It includes endpoints to manage Users, Posts, and Comments.

## Features
- Perform CRUD operations on Users, Posts, and Comments.
- Postman collection available to test APIs.
- Docker containers for backend and database.
- Communication between Docker containers ensured via Docker Compose.

## APIs Documentation
Explore the API endpoints using [Postman Documentation](https://documenter.getpostman.com/view/16598383/2sA3e1A9jA).

To run this application locally, follow these steps:
- `docker-compose build`
- `docker-compose up -d`

- `docker-compose exec web flask db init`
- `docker-compose exec web flask db migrate`
- `docker-compose exec web flask db upgrade`

To check logs
- `docker-compose logs web`
