# Docker Basics

Docker is a platform that simplifies the process of building, packaging, and deploying applications in lightweight, portable containers. In this section, we’ll cover the basics of Docker, its components, and key commands you’ll need to get started.

## Docker Components

There are three key components in the Docker ecosystem:

- **Dockerfile**: A text file containing instructions (commands) to build a Docker image.

- **Docker Image**: A snapshot of a container, created from a Dockerfile. Images are stored in a registry, like Docker Hub, and can be pulled or pushed to the registry.

- **Docker Container**: A running instance of a Docker image.

## Docker Commands

Below are some essential Docker commands you'll use frequently:

```bash
# Download an image from a registry, like Docker Hub.
docker pull <image>
# Build an image from a Dockerfile, where <path> is the directory containing the Dockerfile.
docker build -t <image_name> <path>
# List all images available on your local machine.
docker image ls
# Run a container from an image, mapping host ports to container ports.
docker run -d -p <host_port>:<container_port> --name <container_name> <image>
# List all running containers
docker container ls
# Stop a running container
docker container stop <container>
# Remove a stopped container
docker container rm <container>
# Remove an image from your local machine
docker image rm <image>
```
