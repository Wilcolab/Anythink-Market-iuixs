# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## Verify that Docker is running

Verify docker is ready by running the following commands in your terminal: `docker -v and docker-compose -v`.

## Verify the backend is running

If Docker is working correctly, the backend should be running and able to connect to your local database.

You can test to see if Docker is working correctly by pointing your browser to http://localhost:3000/api/ping

## Verify the frontend is connected to the backend

Now it's time to make sure the frontend is connected to the backend.

If everything is working properly, you’ll be able to create a new user on http://localhost:3001/register

If everything there checks out, then your environment is ready! 😀
