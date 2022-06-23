# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_
Step 1: Install Docker or Docker Desktop
Step 2: Install Docker Compose
Step 3: Run `docker-compose up` in the directory of the repo
Step 4: Run `docker-compose ps` to see if the containers are running
Step 5: Go to the link http://localhost:3000/api/ping to see if the API is working.If everything is working, you should see a 200 response.
Step 6: Now go to the http://localhost:3001/register and register a new user.
