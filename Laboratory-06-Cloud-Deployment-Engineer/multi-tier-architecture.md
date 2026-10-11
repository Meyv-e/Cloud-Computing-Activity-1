# Two-Tier Architecture

## The Web/Application Tier

The Web/Application Tier is responsible for serving the user interface and handling HTTP requests from users. In this project, Nextcloud acts as the web application where users can access the private cloud storage system.

## The Database Tier

The Database Tier is responsible for storing persistent data, including user accounts and file metadata. In this project, MariaDB serves as the database that stores the information needed by Nextcloud.

## Why Separate Them?

Separating the web application and database into two containers makes the system easier to manage and maintain. Each container has its own responsibility, making it easier to update or troubleshoot one service without directly modifying the other. This architecture also allows the services to be configured and managed independently.

