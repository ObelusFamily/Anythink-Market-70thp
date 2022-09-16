# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

## Docker
- install <a  href="https://docs.docker.com/get-docker/">Docker</a>
- verify that docker is installed and ready by running `docker -v` and `docker-compose -v` in your terminal 
- go to the root of the repo and run `docker-compose up` to start the app
- go to `localhost:3000` to see the app running
