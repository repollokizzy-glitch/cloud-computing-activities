# Docker Deployment

## Docker Commands

The following commands were used to verify Docker, deploy an Nginx web server, and manage the container lifecycle.

### 1. Check Docker Version

```bash
docker --version
```

This command displays the installed Docker version.

### 2. Check Docker Status

```bash
docker info
```

This command displays information about the current Docker environment and confirms that the Docker daemon is running.

## Deploying Nginx

### Pull the Nginx Image

```bash
docker pull nginx
```

This command downloads the official Nginx image from Docker Hub.

### Run the Nginx Container

```bash
docker run -d --name nginx-server -p 8080:80 nginx
```

This command runs an Nginx container in detached mode and maps host port 8080 to container port 80.

### Test the Web Server

```bash
curl http://localhost:8080
```

This command sends an HTTP request to the Nginx web server through port 8080.

## Container Lifecycle

### List Running Containers

```bash
docker ps
```

This command lists the containers that are currently running.

### Stop the Container

```bash
docker stop nginx-server
```

This command stops the running Nginx container.

### Verify the Container Is Stopped

```bash
docker ps
```

This command verifies that the Nginx container is no longer running.

### Remove the Container

```bash
docker rm nginx-server
```

This command permanently removes the stopped Nginx container.
