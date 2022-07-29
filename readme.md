# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Clone repository by running `git clone https://github.com/ObelusFamily/Anythink-Market-fafe4.git`
2. Install docker by following the instructions found at https://docs.docker.com/get-docker/
3. Verify that docker is installed by running `docker -v` and `docker-compose -v`
4. Set up the container by running `docker-compose up`
5. Test if Anythink is running by browsing to http://localhost:3000/api/ping
