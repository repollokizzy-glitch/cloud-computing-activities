# Laboratory 04 – Cloud-Native Engineer

## Mission Overview

This laboratory introduces cloud-native concepts through virtualization, containers, and Docker. The main activity is to compare Virtual Machines and containers and deploy an Nginx web server using Docker.

## Objectives

* Understand the differences between Virtual Machines and containers.
* Verify that Docker is installed and running in a Linux environment.
* Pull an official Docker image from Docker Hub.
* Deploy an Nginx web server using Docker.
* Map a host port to a container port.
* Test the web server using curl.
* Manage the Docker container lifecycle.
* Document technical procedures using Markdown.
* Organize laboratory evidence in a GitHub repository.

## Docker Commands Executed

### Docker Verification

```bash
docker --version
docker info
```

### Nginx Deployment

```bash
docker pull nginx
docker run -d --name nginx-server -p 8080:80 nginx
curl http://localhost:8080
```

### Container Lifecycle

```bash
docker ps
docker stop nginx-server
docker ps
docker rm nginx-server
```

## Skills Learned

* Virtual Machine and container comparison
* Docker CLI
* Docker image management
* Container deployment
* Port mapping
* Nginx deployment
* Container lifecycle management
* Linux terminal usage
* Markdown documentation
* GitHub repository organization

## Challenges Encountered

One challenge was becoming familiar with Docker commands and understanding the difference between a Docker image and a running container. Another challenge was understanding port mapping and how port 8080 on the host connects to port 80 inside the Nginx container. I also learned that a stopped container must be removed separately using `docker rm`. Overall, the activity helped me become more comfortable with Docker and cloud-native deployment concepts.

## Screenshots

The screenshots for this laboratory are located in the `screenshots` folder.

* `docker-version.png` – Docker installation and environment verification
* `nginx-running.png` – Successful Nginx web server test
* `container-lifecycle.png` – Container lifecycle commands
