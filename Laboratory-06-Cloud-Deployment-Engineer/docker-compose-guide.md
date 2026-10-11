# Docker Compose Guide

## What Does the services: Block Do?

The services: block defines the containers that will run in the application. In this project, it contains two services: database and app. The database service uses MariaDB, while the app service uses Nextcloud.

## How Does Nextcloud Find the Database Container?

Nextcloud finds the database container through the MYSQL_HOST environment variable. In the Compose file, MYSQL_HOST=database tells Nextcloud to connect to the service named database, which runs MariaDB.

## Difference Between docker run and docker-compose up -d

The docker run command is used to create and run an individual container using a command in the terminal. In contrast, docker-compose up -d uses a Compose YAML file to configure and start multiple connected services in the background. This makes it easier to manage a multi-container application such as Nextcloud and MariaDB.
