# DevOps Project 1 – Dockerised Web App

![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) ![Apache](https://img.shields.io/badge/Apache_httpd-D22128?logo=apache&logoColor=white) ![Jenkins](https://img.shields.io/badge/Jenkins-D24939?logo=jenkins&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)

> A sample web app packaged with Apache httpd, used as the first end-to-end DevOps project.

## Overview

Static web page containerised with **Apache httpd**. The repository is used in the DevOps training track to practise Git, building Docker images and running them as containers. The `Instuctions` file lists the project flow: add code → push → configure Jenkins.

## Tech Stack

- **Docker**
- **Apache httpd**
- **Jenkins**
- **HTML/CSS**

## Repository Structure

```text
app/file1
app/file2
Dockerfile
index.html
Instuctions
README.md
```

## Getting Started

### Run with Docker

```bash
git clone https://github.com/Gamal-Mohammad/devops_project1.git
cd devops_project1
docker build -t devops-project1 .
docker run -d --name devops-project1 -p 8080:80 devops-project1
```

Then open http://localhost:8080.

## Author

**Gamal Mohammad**

[![GitHub](https://img.shields.io/badge/GitHub-Gamal--Mohammad-181717?logo=github)](https://github.com/Gamal-Mohammad)
