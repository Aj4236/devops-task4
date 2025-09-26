# Task 4: Dockerized Nginx Website

## Project Overview
This project demonstrates deploying a full website using **Docker** and **Nginx**.  
It includes HTML, CSS, JS, and images, fully versioned using Git. The project showcases best practices in DevOps including Docker containerization, version control, and website deployment.

## Key Features
- Full website deployment with Nginx in Docker
- Includes HTML, CSS, JS, and images
- Docker image tagged with versioning (e.g., `polk-1.0.7`)
- Git version control with proper commits and README documentation
- Easily reproducible environment for testing and development

## Project Structure

| File/Folder | Description |
|-------------|-------------|
| `index.html` | Main landing page of the website |
| `about.html` | About page |
| `contact.html` | Contact page |
| `design.html` | Design page |
| `company.html` | Company info page |
| `news.html` | News page |
| `css/` | All CSS files |
| `js/` | JavaScript files |
| `images/` | All images used in the website |
| `Dockerfile` | Dockerfile to build Nginx container |
| `README.md` | Project documentation |
| `.gitignore` | Ignore unnecessary files and folders |

## Prerequisites
- Docker installed on your machine
- Basic knowledge of Docker and Nginx
- Git installed for version control

## How to Build and Run

1. **Build Docker image:**
```bash

docker build --no-cache -t task4-nginx:polk-1.0.7 .
Stop and remove old container if exists:
docker ps -q --filter "name=task4-nginx" | xargs -r docker stop
docker ps -aq --filter "name=task4-nginx" | xargs -r docker rm

Run the container:
docker run -d --name task4-nginx -p 8081:80 task4-nginx:polk-1.0.7

Open website in browser:

arduino
Copy code
http://localhost:8081
Notes for Reviewers
The project is fully containerized, making it easy to run on any system with Docker.

All website assets (HTML, CSS, JS, images) are included in the Docker image.

Git commits and version tags demonstrate proper DevOps workflow.

Skills Demonstrated
Docker containerization

Nginx web server deployment

Git version control and branching

Project documentation and DevOps workflow understanding

Author / Contact
Ashok Jangid
GitHub: https://github.com/Aj4236
Email: Ajdevops65@gmail.com
