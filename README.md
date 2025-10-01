Task 4: Version-Controlled DevOps Project with Git
🚀 Project Overview
To view your website in a browser, simply open this link:
https://aj4236.github.io/devops-task4/

This project demonstrates best practices in version control using Git and GitHub for a DevOps workflow.
It includes:

A local Docker container running Nginx with a sample website (index.html and assets).

Proper branching workflow: main, dev, feature/*.

Demonstration of pull requests, merges, and tagging.

Clear documentation using Markdown for task tracking.

🛠 Tools & Technologies

Git: version control and branching.

GitHub: remote repository and pull request management.

Docker: containerization of the website.

Nginx: web server to host index.html.

🌳 Branching Workflow
Branch	Purpose
main	Production-ready code
dev	Development integration branch
feature/*	Individual feature/bugfix branches

Workflow:

Branch off dev to create feature/*.

Commit changes frequently.

Push the feature branch to GitHub.

Open a pull request to merge into dev.

After testing in dev, merge into main.

Tag releases for versioning, e.g., v1.0.0.

📂 Project Structure
File / Folder	Description
Dockerfile	Builds Docker image with Nginx and website
index.html	Main web page
css/	Stylesheets for website
js/	JavaScript files
images/	Website images and icons
.gitignore	Excludes logs, state files, and unnecessary files
README.md	This documentation
TASKS.md	Task progress and details
📝 Git & GitHub Best Practices

Feature branches for each task.

Pull requests for code review and merging.

Commit messages follow conventional style:

feat: add version info to index page
chore: initial commit – add Dockerfile, README, .gitignore


Clean up merged feature branches to keep repo tidy.

🐳 Docker Instructions

Build Docker image:

docker build -t task4-nginx:polk-1.0.6 .


Run container:

docker run -d -p 8081:80 task4-nginx:polk-1.0.6


Open in browser:

http://localhost:8081


Stop container:

docker stop <container_id>

🏷 Versioning

v1.0.0 → Initial release of Task 4 project

Tags maintained in Git for traceability and reproducibility.

✅ Notes for HR / Reviewers

All tasks are reproducible on any system with Git, Docker, and Nginx installed.

The project demonstrates DevOps workflow: branching, PRs, merges, Docker containerization, and deployment.

Repository is clean, organized, and professional for review.

📧 Contact / Author

Ashok Jangid
GitHub: https://github.com/Aj4236

Email: Ajdevops65@gmail.com
