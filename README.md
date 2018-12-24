# Docker Compose a microservice

   Deploy and run a simple microservice with Flask and MongoDB integration inside a docker container using docker Compose

### Prerequisites

A.) docker (1.6.0 or above)
B.) docker-compose (1.3.1+)
C.) python 2.7 or above
D.) Linux VM


### Installing

Create a parent directory flask_compose_microservice

$ mkdir flask_compose_microservice
$ cd flask_compose_microservice

Files to be created in the directory
├── app.py
├── docker-compose.yml
├── Dockerfile
├── README.md
├── requirements.txt
└── templates


- Build and Run the Service using Docker Compose
- Run the following command to build the docker image flask_compose_microservice from web directory and deploy is as a service

$ docker-compose build
$ docker-compose up

### Accessing the Service

Using a Webbrowser type following url to see the HTMl rendered
```
127.0.0.1:5000.
```
