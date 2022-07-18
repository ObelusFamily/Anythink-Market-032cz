# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

The first thing after cloned the repo is installing [Docker](https://docs.docker.com/get-docker/).
To test if Docker is up and running you can run inside a terminal those commands:
```bash
docker -v
docker-compose -v
```

If all commands are ok you can start the project with the command

```bash
docker-compose up
```
After the container is up you can point the browser to [http://localhost:3000/api/ping](http://localhost:3000/api/ping) to test it it's ok
and then create the first user for the application to this url [http://localhost:3001/register](http://localhost:3001/register)



**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_
