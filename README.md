# Dockerized Python Flask Application

## Project Overview

This project demonstrates how to containerize a Python Flask web application using Docker. The application displays a personalized greeting using environment variables and runs inside a Docker container.

## Technologies Used

* Python
* Flask
* Docker
* Linux

## Features

* Flask-based web application
* Docker containerization
* Environment variable configuration
* Port mapping using Docker
* Easy deployment and scalability

## Project Structure

```
flask-docker-app/
│
├── app.py
├── requirements.txt
├── Dockerfile
└── README.md
```

## Installation and Setup

### Clone Repository

```bash
git clone <repository-url>
cd flask-docker-app
```

### Build Docker Image

```bash
docker build -t flask-app .
```

### Run Docker Container

```bash
docker run -d -p 5000:5000 -e NAME=Sarada flask-app
```

### Access Application

Open your browser and visit:

```
http://localhost:5000
```

## Output

```
Hello Sarada from Docker!
```

## Learning Outcomes

* Created a Flask web application
* Built and managed Docker images
* Used environment variables inside containers
* Implemented Docker port mapping
* Performed container debugging and troubleshooting

## Challenges Faced

- Fixed Flask startup issues caused by incorrect __main__ syntax.
- Resolved Docker container port conflicts.
- Debugged Internal Server Error (500) during development.

## Key Learnings

- Docker image creation and container management.
- Environment variables in Docker.
- Flask deployment inside containers.
- Container troubleshooting and debugging.

## Author

**Revunuru Sarada Maheswari**

DevOps & Cloud Computing Aspirant
