# Dockerized Flask + NGINX Web Application

A simple web application with Flask backend and NGINX frontend, containerized with Docker.
The goal it to automate multi-container app building using Docker Compose.

## Project Structure
my-docker-app/
├── backend/ # Flask API
│ ├── app.py # Flask application
│ ├── requirements.txt
│ └── Dockerfile
├── frontend/ # NGINX
│ └── index.html
├── docker-compose.yml
└── README.md # This file


## Features
- Flask backend API with sample endpoint
- NGINX frontend serving static content
- Docker Compose for easy orchestration
- Separate containers for frontend/backend
