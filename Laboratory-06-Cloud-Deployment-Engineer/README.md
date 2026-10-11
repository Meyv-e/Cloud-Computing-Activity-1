# Mission 6: The Cloud Deployment Engineer

## Mission Overview

This laboratory activity focuses on deploying a multi-tier private cloud storage application using Docker Compose. The application uses Nextcloud as the web application and MariaDB as the database.

## Objectives

- Understand the concept of a two-tier architecture.
- Create a docker-compose.yml configuration file.
- Deploy Nextcloud and MariaDB using Docker Compose.
- Access the Nextcloud web interface through port 8080.
- Document the deployment process using Markdown.
- Practice Infrastructure as Code (IaC).

## Commands Executed
```bash
mkdir nextcloud-deployment
cd nextcloud-deployment
nano docker-compose.yml
docker-compose up -d
docker-compose ps
docker-compose down

## Skills Learned

- Understanding multi-tier application architecture.
- Writing YAML configuration files.
- Using the nano text editor.
- Deploying and managing multiple containers with Docker Compose.
- Accessing a web application through a forwarded port.
- Documenting cloud deployment procedures using Markdown.
