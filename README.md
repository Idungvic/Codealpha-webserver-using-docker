# Docker Web Server Deployment on AWS EC2

## Project Overview

This project demonstrates the deployment of a containerized web server using Docker on an AWS EC2 instance. The objective was to gain hands-on experience with Docker containerization, container lifecycle management, monitoring, and troubleshooting while hosting a simple web application.

## Technologies Used

* AWS EC2
* Ubuntu 22.04 LTS
* Docker
* NGINX
* HTML
* Git & GitHub

## Project Architecture

```text
User Browser
      │
      ▼
AWS EC2 Instance
      │
      ▼
Docker Engine
      │
      ▼
NGINX Container
      │
      ▼
Web Application
```

## Features

* Dockerized web application deployment
* NGINX web server running inside a container
* Container lifecycle management
* Container monitoring and logging
* AWS cloud hosting

## Project Files

```text
.
├── Dockerfile
├── index.html
├── README.md
```

## Docker Commands Used

Build Image:

```bash
docker build -t docker-web-server .
```

Run Container:

```bash
docker run -d -p 80:80 --name web-container docker-web-server
```

Check Running Containers:

```bash
docker ps
```

View Logs:

```bash
docker logs web-container
```

## Learning Outcomes

Through this project, I gained practical experience in:

* Docker image creation
* Container deployment and management
* AWS EC2 administration
* NGINX web server configuration
* Container monitoring and troubleshooting
* Cloud-based application hosting

## Conclusion

This project successfully demonstrated how Docker can be used to package and deploy web applications in a consistent and portable manner. It also provided valuable hands-on experience with containerized deployments and cloud infrastructure management.
# Codealpha-webserver-using-docker
