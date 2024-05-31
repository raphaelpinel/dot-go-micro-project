# dot go project
Part of the `Microservices with Go` at the dot conf repos

This is a helper folder that contains a docker file
Note that it will only work if the folder where you have installed the broker service is named `broker`

## Branches
There are no start branches for this repo, only solutions
- In `step1-docker-compose-for-broker-solution` you can connect to the broker
- In `step2-docker-compose-for-authentication-solution` we add the authentication service

## How to run docker-compose
To run the broker service in docker, enter in Terminal:
`docker-compose up -d`
(-d means: run in the background)

To list the containers running:
`docker ps`

To stop the container:
`docker-compose down`
