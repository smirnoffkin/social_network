# Social network prototype

## Features

* OAuth2 🔐
* Create, update, delete articles 🖼️
* React with 👍👎 reactions
* Role model (superadmin, admin, user) 👪
* Data caching in Redis ⚡

## TODO

* Add endpoint to get all users who liked your post
* Add and configure logger
* Add more unit-tests for 100% coverage
* Add a frontend to get a Fullstack app
* And add many, many, many different useful features 👨‍💻

## Run
### Production

1. `make env`
2. `make up-prod`

### Development

1. `make env`
2. `make dev`
3. `make up-dev`
4. `make migrate`
5. `make run`

Go to `http://localhost:8080/docs` to see open api docs

## Project technology stack

* FastAPI, asyncio, SQLAlchemy, PostgreSQL, Redis, Celery, pytest, alembic, Docker

#### P.S. A detailed description of the task can be found in [task.txt](./task.txt). ####
