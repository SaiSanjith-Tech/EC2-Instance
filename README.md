# Static-Web-EC2-Deployment
# Modern Static Website Deployment on AWS

A fast, responsive static website built with pure HTML5/CSS3 and deployed to an AWS EC2 instance served via an Nginx web server. 

This project demonstrates the complete lifecycle of a static web application—from writing clean, dependency-free frontend code to provisioning cloud infrastructure and configuring a production-grade web server.

---

## 🌐 Live Project URL
*(Insert your live EC2 Public IPv4 DNS or custom domain here)*

## 🚀 Features
* **Lightweight & Fast:** Built with pure HTML5 and modern CSS3, eliminating the bloat and overhead of external frameworks.
* **Fully Responsive:** Adapts seamlessly to desktop, tablet, and mobile displays using modern CSS media queries.
* **Production-Ready Infrastructure:** Configured for high-performance delivery using Nginx on an AWS EC2 instance.
* **Cost-Effective:** Utilizes minimal compute resources, making it ideal for the AWS Free Tier.

## 🛠️ What I Have Done (Project Architecture)
In building and deploying this project, I completed the following phases:
1. **Frontend Development:** Designed and coded a responsive static website from scratch using semantic HTML5 and CSS3.
2. **Cloud Provisioning:** Launched and configured an Amazon EC2 instance (Linux), setting up appropriate Security Groups to allow inbound HTTP (port 80) and SSH (port 22) traffic.
3. **Server Configuration:** Installed and configured **Nginx**, a high-performance web server, to handle incoming web requests.
4. **Deployment:** Transferred the local repository files to the EC2 instance and configured the Nginx web root directory (`/var/www/html`) to serve the website securely and efficiently to the public internet.

## 💡 Project Uses
This repository serves multiple purposes and can be adapted for various use cases:
* **Personal Portfolios:** A lightweight template for developers or designers to showcase their work.
* **Business Landing Pages:** A fast-loading, low-maintenance placeholder or promotional page for small businesses.
* **Educational Baseline:** A practical reference for beginners learning how to connect cloud infrastructure (AWS) with web servers (Nginx) without the complexity of backend databases or frameworks.
* **CI/CD Foundation:** A perfect starter repository for practicing automated deployments using GitHub Actions and AWS CodeDeploy.

## 📖 How to Use This Project (Deployment Guide)
If you want to clone this repository and deploy it to your own AWS environment, follow these steps:

### Prerequisites
* An AWS Account (Free Tier eligible is fine).
* Basic knowledge of the terminal/command line.
* Git installed on your local machine.

### Step 1: Clone the Repository
Clone this project to your local machine:
```bash
git clone [https://github.com/YourUsername/Static-Web-EC2-Deployment.git](https://github.com/YourUsername/Static-Web-EC2-Deployment.git)
cd Static-Web-EC2-Deployment
