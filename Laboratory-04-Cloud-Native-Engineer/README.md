# Laboratory 04 - Cloud-Native Engineer

## Mission Overview

In this laboratory activity, I learned about cloud-native technologies, especially Docker and containers. I compared Virtual Machines and containers and used KillerCoda to run Docker commands. I also deployed an Nginx web server using a Docker container.

## Objectives

- Differentiate Virtual Machines and Containers.
- Access a Docker-enabled environment using KillerCoda.
- Execute basic Docker commands.
- Pull, run, manage, and remove an Nginx container.
- Create technical documentation using Markdown.

## Docker Commands Executed

```bash
docker --version
docker info
docker pull nginx
docker run -d -p 8080:80 --name nginx-server nginx
curl http://localhost:8080
docker ps
docker stop nginx-server
docker ps
docker rm nginx-server
