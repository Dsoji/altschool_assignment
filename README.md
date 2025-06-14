# AltSchool Cloud Project – The Future of [Your Startup Idea]

## 🚀 Live URL
http://51.21.199.17

## 📸 Screenshot
![Screenshot](<img width="1465" alt="Screenshot 2025-06-14 at 22 01 41" src="https://github.com/user-attachments/assets/a5f7d046-8983-4e01-b5a7-a2d91cab48cc" />
)

## 🧠 Summary
This project is a cloud-hosted landing page titled **“The Future of [Your Startup Idea]”**, showcasing a dynamic and personalized site deployed on an Ubuntu server using Nginx.

## 🔧 Stack Used
- AWS EC2 (Ubuntu)
- Nginx Web Server
- HTML/CSS/JavaScript
- SCP and SSH for deployment

## 🛠️ Setup Steps

### 🖥️ Server Provisioning
- Launched Ubuntu EC2 instance on AWS using `altsch-key.pem`
- Configured security group to allow ports 22 (SSH), 80 (HTTP), 443 (HTTPS)

### 🌐 Web Server
- Installed and started Nginx:
  ```bash
  sudo apt update
  sudo apt install nginx -y
