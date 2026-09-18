# Reflection

In this laboratory activity, I learned the difference between using a Docker container and installing an operating system on a Virtual Machine. A Docker container can be started faster because it does not need a complete guest operating system. Setting up a container is also lightweight compared to setting up a Virtual Machine.

The -p 8080:80 option is necessary because it maps port 8080 on the host to port 80 inside the Nginx container. This allows me to access the Nginx web server using http://localhost:8080.

When docker rm is used, the container is removed completely. Any data stored only inside the removed container can be lost. This is why persistent storage is important when data needs to be kept.

Containerization can improve collaboration between developers and operations teams because applications can be packaged with their required environment. This helps make the application more consistent when it is developed, tested, and deployed.

My GitHub portfolio is also improving because I am documenting the commands, screenshots, and lessons I learned from this laboratory activity. This shows my experience with Docker and cloud-native technologies.
