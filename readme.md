# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Steps to initial setup:
1. Clone the repo 
2. Change directory into the root of your working copy
3. Ensure `docker` and `docker-compose` are installed correctly
```
$  docker -v
Docker version 20.10.17, build 100c70
$ docker-compose -v
docker-compose version 1.29.2, build 5becea4c
```
_Your version numbers may differ_
4. (Windows & Mac) Ensure Docker desktop is running on your machine
5. Run the back and front-end servers: `docker-compose up`

Step 4 is crucial. You will receive inexplicable error messages if docker desktop is NOT running.

