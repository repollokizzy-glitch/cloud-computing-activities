# MinIO Deployment

## Overview

This document contains the technical steps used to deploy the MinIO object storage server using Docker.

## Docker Command

The required deployment command is:

```bash
docker run -d -p 9000:9000 -p 9001:9001 --name minio-server \
-e "MINIO_ROOT_USER=cloudadmin" \
-e "MINIO_ROOT_PASSWORD=CloudNova2026!" \
minio/minio server /data --console-address ":9001"
```

## Ports

* Port 9000 - MinIO API
* Port 9001 - MinIO Web Console

The Web Console is accessed through port **9001**.

## Bucket

The required bucket name is:

`client-photos`

## Environment Variables

The `-e` flags define environment variables inside the Docker container.

`MINIO_ROOT_USER=cloudadmin` sets the MinIO administrator username.

`MINIO_ROOT_PASSWORD=CloudNova2026!` sets the administrator password.

## Verification

The MinIO container will be verified using:

```bash
docker ps
```

Docker logs can also be checked using:

```bash
docker logs minio-server
```

## Bucket Upload

After accessing the MinIO Web Console, the `client-photos` bucket will be created and a sample file will be uploaded.
