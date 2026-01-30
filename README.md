## 🌐 Application Access

https://vijetha-a.github.io/Project-webhosting/

# Static Website Hosting using Nginx on AWS EC2

This project demonstrates hosting a static website using **Nginx on an AWS EC2 instance**.  
The website UI is based on a free HTML/CSS/JavaScript template and focuses on deployment,
server configuration, and version control best practices.

## 📌 Project Overview

- Deployed a static website on **AWS EC2 (Ubuntu)**
- Configured **Nginx** as a web server
- Managed source code using **Git and GitHub**
- Enabled **GitHub Pages** for repository deployment view
- Followed Linux permission and deployment best practices

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript  
- **Web Server:** Nginx  
- **Cloud:** AWS EC2 (Ubuntu)  
- **Version Control:** Git & GitHub  

## 🚀 Deployment Steps 

1. Launched an Ubuntu EC2 instance on AWS
2. Installed and configured Nginx
3. Deployed static files to `/var/www/html`
4. Initialized Git repository in user workspace
5. Pushed source code to GitHub
6. Verified application using EC2 public IP

## 🌐 Application Access

https://vijetha-a.github.io/Project-webhosting/

## 📂 Project Structure

├── index.html
├── tooplate-fireworks-style.css
├── tooplate-fireworks-composer.js
└── ABOUT THIS TEMPLATE.txt

## 🎨 Template Credit

UI template sourced from **Tooplate** (Free HTML Templates).  
This project focuses on **deployment and DevOps practices**, not UI design.

## 📈 Key Learnings

- Static website hosting with Nginx
- Linux file permissions and deployment directories
- GitHub repository management
- Real-world EC2 web hosting workflow

## 💻 Setup & Deployment Commands

- sudo apt update && sudo apt install unzip -y
- wget -O app.zip https://www.tooplate.com/download/2153_fireworks_composer
- unzip app.zip
- cp 2153_fireworks_composer/* /var/www/html -r
- git init
- git add .
- git commit -m "c1"
- git remote add origin https://github.com/Vijetha-A/Project-webhosting.git
- git push origin master

## 👩‍💻 Author
**Vijetha A**  
