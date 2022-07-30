# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

## Docker and Docker Compose
You must install Docker and Docker compose on your machine.

To verify a successful instalation, run:

```sh
# Verify Docker
docker -v

# Verify Docker Compose
docker-compose -v
```

## Run local containers
On your terminal, go to this repository root and run containers: `docker-compose up`

## Verify API is running

* API health check: http://localhost:3000/api/ping 

## Verify Web App is running and register user
The registered user is created on your local database.

* Web App user registration: http://localhost:3001/register