# Client Portal

## Design Goals
- ### Create a web portal application for clients to control their docker container applications.
- Create a simple interface hosted within docker
- Modular design to make expansion easy for both features and size of the application

## Current Design Ideas
- Create an application from node.js using the docker api to locally control the docker images
- Application needs to be able to log into different servers based on the client:
    - Server URL
    - Username
    - Password
- Application needs to start, stop, and create docker containers from templates
- Application needs to have some file access for clients to update tokens themselves
