# aws-ec2-nginx-static-website
# Host a Static Website on AWS EC2 using NGINX

## Project Overview

This project demonstrates how to host a static website on an AWS EC2 Ubuntu instance using NGINX.

The website was deployed manually by connecting to the EC2 instance through SSH and configuring NGINX as a web server.

---

## Technologies Used

- AWS EC2
- Ubuntu Linux
- NGINX
- SSH
- Linux Commands

---

## Architecture

User Browser → AWS EC2 → NGINX → Static Website

---

## Steps Performed

### 1. Launch EC2 Instance

- Created Ubuntu EC2 instance
- Allowed HTTP (80) and SSH (22) in Security Group

### 2. Connect to EC2

```bash
ssh -i key.pem ubuntu@your-public-ip
