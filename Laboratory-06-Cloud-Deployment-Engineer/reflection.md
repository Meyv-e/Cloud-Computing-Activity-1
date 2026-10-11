# Mission 6 Reflection

## My Learning Reflection

Writing a docker-compose.yml file makes a cloud engineer's job easier because it allows multiple containers to be configured in one file. Instead of typing many commands manually, the engineer can use one command to start the entire application. It also makes the deployment easier to repeat and manage.

An indentation error in a YAML file can cause a configuration error. YAML uses spaces to organize its structure, so incorrect indentation or using tabs may prevent Docker Compose from reading the file correctly. This is why checking the format before deployment is important.

Environment variables such as MYSQL_PASSWORD, MYSQL_DATABASE, and MYSQL_USER provide the configuration needed by the application and database. They allow the containers to use matching database settings so that Nextcloud can connect to MariaDB. These variables make the configuration easier to understand and modify.

Deploying a cloud storage application such as Nextcloud is a useful learning experience because it demonstrates how different containers work together. The web application handles user access, while the database stores important information. Using Docker Compose makes the process more organized than configuring each container separately.

Since Mission 1, my understanding of Cloud Computing has developed from learning basic cloud concepts to understanding how applications can be deployed using containers. I have learned that cloud infrastructure involves more than simply running a server. It also requires proper configuration, communication between services, documentation, and troubleshooting. This activity helped me understand the importance of Infrastructure as Code because configurations can be written, reviewed, and reused. I can apply these skills to future cloud computing activities and projects.
