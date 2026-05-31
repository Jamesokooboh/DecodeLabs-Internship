# Project 4 - Containerization with Docker

## Objective

Containerize an application using Docker to ensure consistent execution across different environments.

## Project Components

### Dockerfile

Defines the container blueprint using:

* FROM
* WORKDIR
* COPY
* CMD

### .dockerignore

Optimizes build performance by excluding unnecessary files from the build context.

## Build Process

Build the image:

```bash
docker build -t my-app:1.0 .
```

## Run Process

Launch the container:

```bash
docker run -d -p 8080:80 --name my-container my-app:1.0
```

## Verification

Access the application:

```text
http://localhost:8080
```

## Concepts Demonstrated

* Docker Images
* Docker Containers
* Layer Caching
* Port Mapping
* Detached Mode
* Container Networking
* Container Lifecycle Management

## Technologies Used

* Docker
* Nginx
* Alpine Linux
