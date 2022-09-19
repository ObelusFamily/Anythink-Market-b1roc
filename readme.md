# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Clone the project.
2. Install docker if not already installed.
3. Run `docker -v` and `docker-compose -v` in the terminal to see that everything is installed.
4. From the root of the project, run `docker-compose up` to get the backend and frontend installed.
5. The first time you do this, it will take a little while as docket needs to build both containers.
