# Task 4: Dockerized Nginx Website

## Objective
Manage a website deployment using Docker and Nginx while following DevOps best practices.

## Tools
- Docker
- Nginx
- Git / GitHub

## Steps Completed

1. **Project Setup**
   - Collected all website files: HTML, CSS, JS, images
   - Removed broken symlinks and unnecessary folders

2. **Docker Configuration**
   - Created a `Dockerfile` based on `nginx:alpine`
   - Copied all website files into `/usr/share/nginx/html`
   - Built Docker image: `task4-nginx:polk-1.0.7`

3. **Container Management**
   - Stopped and removed old containers
   - Ran new container on port `8081`
   - Verified website loads fully with all assets

4. **Version Control**
   - Initialized Git repository
   - Added `.gitignore` to ignore unnecessary files
   - Committed all changes
   - Pushed project to GitHub repository
   - Added Git tag: `v1.0.1`

5. **Testing**
   - Verified all pages (index, about, contact, design, company, news) load correctly
   - CSS, JS, and images render properly

## Outcome
- Fully functional website containerized in Docker
- Project is version-controlled and ready for review
- Docker image and Git repository follow DevOps best practices

## Author
**Ashok Jangid**  
GitHub: [https://github.com/Aj4236](https://github.com/Aj4236)  
Email: Ajdevops65@gmail.com

