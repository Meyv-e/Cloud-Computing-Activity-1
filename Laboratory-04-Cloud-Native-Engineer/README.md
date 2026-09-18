# Laboratory 04 - Cloud-Native Engineer

## Mission Overview

In this laboratory activity, I learned about cloud-native technologies, especially Docker and containers. I compared Virtual Machines and containers and used KillerCoda to run Docker commands. I also deployed an Nginx web server using a Docker container.

## Objectives

- Differentiate Virtual Machines and Containers.
- Access a Docker-enabled cloud environment using KillerCoda.
- Execute fundamental Docker CLI commands.
- Pull, run, manage, and terminate an Nginx container.
- Create technical documentation using Markdown.

## Docker Commands Executed

### Checkpoint 3 - Docker Verification
```bash
docker --version
docker info
```

### Checkpoint 4 - Nginx Deployment
```bash
docker pull nginx
docker run -d -p 8080:80 --name nginx-server nginx
curl http://localhost:8080
```

### Checkpoint 5 - Container Lifecycle
```bash
docker ps
docker stop nginx-server
docker ps
docker rm nginx-server
```

## Skills Learned

I learned how to use basic Docker commands. I learned how to pull an image, run a container, and test a web server. I also learned how to list, stop, and remove a container. I learned how port mapping connects a container to the host.

## Challenges Encountered

One challenge I encountered was learning the correct Docker commands and their order. I also needed to understand how containers work and how port mapping works. After following the steps, I was able to run and test the Nginx web server successfully.
