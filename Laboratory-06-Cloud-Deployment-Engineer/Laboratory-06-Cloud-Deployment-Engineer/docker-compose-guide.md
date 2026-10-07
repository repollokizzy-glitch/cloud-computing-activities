# Docker Compose Guide

## What Does the `services:` Block Do?

The `services:` block defines the containers that Docker Compose will create and manage. In this project, there are two services: `database` for MariaDB and `app` for Nextcloud.

## Database Service

The database service uses the MariaDB 10.6 image:

```yaml
database:
  image: mariadb:10.6
