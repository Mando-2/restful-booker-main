[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

This is a copy of the open source project from Mark Winteringham. I have not modified it in any way
other than to include a Dockerfile and a Docker-Compose.yaml file to handle deployment in Docker.
It is provided as a deployable instance so that you can excute the tests in the accompanying test
project.  For this project I am deploying this site to a docker container with an explicit
networking setup within docker.  This will allow you to bring up this site as it's own running 
instance in Docker in a way that will be needed to execute the test project.  I have also included 
the readme from the original project.

# restful-booker
A simple Node booking form for testing RESTful web services.

# Requirements
- Docker 17.09.0
- Docker Compose 1.16.1

# Installation
1. Ensure mongo is up and running by executing ```mongod``` in your terminal
2. Clone the repo
3. Navigate into the restful-booker root folder
4. Run ```npm install```
5. Run ```npm start```
 
Or you can run this via Docker:
1. Clone the repo
2. Navigate into the restful-booker root folder
3. Run ```docker-compose build```
4. Run ```docker-compose up```
5. APIs are exposed on http://localhost:3001

# API
API details can be found on the [publically deployed version of Restful-Booker](https://restful-booker.herokuapp.com/).
