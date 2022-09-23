# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

### Requirements

- Docker
- Docker-compose

### Setup

1. Clone this repository `git clone https://www.github.com/ObelusFamily/Anythink-Market-8puzs.git`
2. Cd to the repository directory `cd Anythink-Market-8puzs.git`
3. Run `docker-compose up` to setup the container
4. Visit `http://localhost:3000/api/ping` to check if the backend server is running
5. Visit `http://localhost:3001/` to check if the frontend app is running
