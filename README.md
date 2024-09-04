# Quick Build Autogen Studio Container
This is a quick build Dockerfile to create a container for the Autogen Studio.
The container is based on the Python3.10 image and installs the necessary dependencies to run the Autogen Studio.
The container is built using the Dockerfile in this repository.

# Prerequisites
To build the container, you need to have Docker installed on your machine.

# How to build the container
To build the container, run the following command in the terminal:

```bash
docker build -t autogen-studio .
```

This command will build the container and tag it with the name `autogen-studio`.

# How to run the container
To run the container, you need to have Docker installed on your machine.
To run the container, run the following command in the terminal:

```bash
docker run -d autogen-studio -p 8081:8081
```

This command will run the container in detached mode and map the port 8081 of the container to the port 8081 of the host machine.
So you can access the Autogen Studio by opening a web browser and navigating to `http://localhost:8081`.