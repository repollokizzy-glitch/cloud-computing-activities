# Laboratory 06 - Cloud Deployment Engineer

## Mission Overview

This mission focuses on deploying a multi-container cloud application using Docker Compose. The project uses Nextcloud as the application tier and MariaDB as the database tier.

## Objectives

- Understand two-tier architecture.
- Create a Docker Compose YAML configuration.
- Deploy multiple containers using Docker Compose.
- Connect Nextcloud with MariaDB.
- Access a containerized application through a browser.
- Practice Infrastructure as Code (IaC).
- Document and maintain a cloud deployment project.

## Commands Executed

```bash
mkdir nextcloud-deployment
cd nextcloud-deployment
nano docker-compose.yml
docker-compose up -d
docker-compose ps
docker-compose down
