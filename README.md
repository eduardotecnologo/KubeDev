# KubeDev
KubeDev - Docker/Kubernete


## Setup
▶ docker container run hello-world
Unable to find image 'hello-world:latest' locally

▶ docker container ls -a
CONTAINER ID   IMAGE         COMMAND    CREATED         STATUS                     PORTS     NAMES
f5c678c3a2dd   hello-world   "/hello"   2 minutes ago   Exited (0) 2 minutes ago             romantic_galileo

▶ docker container rm f5c678c3a2dd

▶ docker container run -it ubuntu /bin/bash
Unable to find image 'ubuntu:latest' locally

▶ docker container run -d -p 27017:27017 -e MONGO_INITDB_ROOT_USERNAME=mongouser -e MONGO_INITDB_ROOT_PASSWORD=mongopwd mongo
Unable to find image 'mongo:latest' locally

