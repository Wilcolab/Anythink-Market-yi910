# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Install Docker
2. Check installation was successful by running `docker -v` and `docker-compose -v`
3. Run `docker-compose up` from the root of the project
4. Test backend by accessing `http://localhost:3000/api/ping`
5. Test frontend by accessing `http://localhost:3001/register` and creating a new user
