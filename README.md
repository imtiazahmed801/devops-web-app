🌐 Minimalist Web App

A simple, modern, and minimalist static web app deployed on an Ubuntu server.
This project demonstrates the fundamentals of DevOps deployment, server configuration, and version control with Git + SSH.

🚀 Project Overview

This project hosts a lightweight web page built with HTML, CSS, and JavaScript — styled with neutral colors and designed for simplicity and responsiveness.
It was deployed on an Ubuntu server using Nginx as the web server.

🧩 Features

- Minimalist design using HTML, CSS, and JavaScript

- Light/Dark mode toggle

- Interactive server status button

- Fully responsive layout

- Secure Git version control via SSH

⚙️ Technologies Used

- Operating System: Ubuntu (Linux)

- Web Server: Nginx

- Version Control: Git + GitHub (SSH authentication)

- Frontend: HTML5, CSS3, JavaScript

🖥️ Setup Instructions

- 1. Clone the repository
git clone git@github.com:imtiazahmed801/devops-web-app.git
cd devops-web-app

- 2. Move project files to Nginx web root
sudo cp -r * /var/www/html/

- 3. Verify deployment

Visit your server’s IP in your browser:

http://"your-server-ip"

🔐 SSH Deployment Setup

- Generate SSH key on your Ubuntu server:

- ssh-keygen -t ed25519 -C "your_email@example.com"


Add the public key to GitHub → Settings → SSH and GPG keys → New SSH key

Test connection:

- ssh -T git@github.com

🧠 Learning Outcomes

Through this project, I practiced managing code with Git and Github via SSh while configuring an Ubunutu web server for web deployment. I used Nginx to host the static content and automation with the command line in Linux for the workflow


🧾 Future Improvements

- Add CI/CD pipeline for automatic deployment

- Integrate with a backend API

- Use Docker for containerized deployment
