# Dockerized Flask + NGINX Web Application

A simple web application with Flask backend and NGINX frontend, containerized with Docker.
The goal it to automate multi-container app building using Docker Compose.

## Project Structure
docker-compose-activity/

├── backend/ 

│ ├── app.py

│ ├── requirements.txt

│ └── Dockerfile

├── frontend/ # NGINX

  └──Dockerfile
  
│ └── index.html

├── docker-compose.yml

└── README.md # This file


## Features
- Flask backend API with sample endpoint
- NGINX frontend serving static content
- Docker Compose for easy orchestration
- Separate containers for frontend/backend
