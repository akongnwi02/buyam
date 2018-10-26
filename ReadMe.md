## E-commerce website

### Forked off [laravel 5 boilerplate project](https://github.com/rappasoft/laravel-5-boilerplate)

## Deployment Guide

## I Clone the project and checkout develop branch

## II. Installing Docker and Docker-compose

Do these steps if you don't have docker and docker-compose installed
1. `sh install-docker.sh`
2. log out
3. log back in

## III. Building the Project

Run the following command on project's root directory
1. `make build` -> This will create the project's images
2. `make up` -> This will start up the containers from the images
3. `make begin` -> This will bootstrap the application
4. Open browser and type `http://localhost:8080`

### The following commands are helpful
* `make login` to log into the application container
* `make down` to take down containers