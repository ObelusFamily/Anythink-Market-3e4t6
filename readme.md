# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Set up [docker-desktop](https://docs.docker.com/get-docker/)
2. Confirm docker installation in terminal
    - ```docker -v```
    - ```docker-compose -v```
3. From the project root directory in terminal, run:
    - ```sudo docker-compose up```
4. Test backend by going to http://localhost:3000/api/ping in a web browser
5. Test frontend-to-backend connection by going to http://localhost:3001/register in a web browser