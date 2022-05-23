## Setting up Docker on Windows
[Docker Desktop](https://www.docker.com/products/docker-desktop/)

## Windows Sub-system for Linux


## MINGW Terminal

## Windows Terminal

## Docker Basics

---
## Hands-on 

### Pulling docker images from docker hub

### Building a new image based on the base image

### Creating a sample pipeline image to showcase use of Docker

## Setting up Postgres SQL Docker Image Locally

`docker run -it -e POSTGRES_USER="root" -e POSTGRES_PASSWORD="root" -e  POSTGRES_DB="ny_taxi" -v D:\Learning\Learning-DE-Zoomcamp\postgres_db:/var/lib/postgresql/data  -p 5432:5432  postgres:13`

using PGCLI

`pgcli -h localhost -p 5432 -u root -d ny_taxi`

### Configuring pgadmin for POSTGRES SQL

`docker run -it -e PGADMIN_DEFAULT_EMAIL="admin@admin.com" -e PGADMIN_DEFAULT_PASSWORD="root" -p 8080:80 dpage/pgadmin4`

### 