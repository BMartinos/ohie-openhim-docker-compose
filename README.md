# ohie-openhim-docker-compose

Prerequisites
===============================
Docker needs to be installed to build and run the containers
https://docs.docker.com/install/

Docker compose needs to be installed to execte the build command
https://docs.docker.com/compose/install/

Setup
===============================
From within this directory you will need to execute the below command to build and run the OpenHIM containers:
`docker-compose up -d`

Access
===============================
Navigate to http://localhost:9000 to access the OpenHIM console

username: `root@openhim.org`
password: `openhim-password`

Upon successfull login, you will be requested to change the default root password.

NB! the OpenHIM uses a self signed certificate by default, and this will need to be trusted by your browser before you will be able to communicate with the API
