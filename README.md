# docker-files-and-compose
This repository contains the docker-compose files for different types of applications start up. Currently the repository containers three composing files.

* Run Teamcity Server for continous integration
* Run Octopus Deploy for continous deployment - Read the documentation on [Medium](https://arpitfs.medium.com/running-containerized-octopus-deploy-with-containerized-sql-server-47f0a5a57ffb)
* Run Web api and sql server under the same network for communication. Check the [Repository](https://github.com/arpitfs/containers-comms)

### To run the containers perform below commands

Go to the path where docker-compose file exists

* Run `docker-compose build` - to build the containers
* Run `docker-compose up` - to build run the containers within a network
