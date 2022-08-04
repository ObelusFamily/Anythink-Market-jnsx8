# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

### Install Docker

- Follow the [Docker setup docs](https://docs.docker.com/get-docker/).
- Verify docker is ready with `docker -v` and `docker-compose -v`

### Run locally

Run `docker-compose up`.

Default ports are:
- `3000` for the backend
- `3001` for the frontend

You can check these are running with:
- [http://localhost:3000/api/ping](http://localhost:3000/api/ping)
- [http://localhost:3001/register](http://localhost:3001/register)