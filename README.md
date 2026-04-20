# 🚀 AWS CI/CD Pipeline using GitHub Actions & EC2

## 📌 Project Overview

This project demonstrates a complete **CI/CD pipeline** by automatically deploying a static web application to an AWS EC2 instance using GitHub Actions.

Whenever changes are pushed to the GitHub repository, the pipeline automatically connects to the EC2 server and deploys the updated application.

---
## 🏗️ Architecture Diagram
![Architecture](screenshots/architecture-diagram.png)

---

## 🛠️ Tech Stack

* **Cloud Provider:** AWS (EC2)
* **CI/CD Tool:** GitHub Actions
* **Version Control:** Git & GitHub
* **Web Server:** Apache (httpd)
* **OS:** Amazon Linux

---

## ⚙️ Architecture

1. Developer pushes code to GitHub
2. GitHub Actions workflow is triggered
3. Workflow connects to EC2 via SSH
4. Application is deployed to `/var/www/html`
5. Website is served via Apache

---

## 🔁 CI/CD Workflow

* Trigger: Push to `main` branch
* Steps:

  * Checkout repository
  * Connect to EC2 instance
  * Pull latest code
  * Deploy to Apache web server

---

## 📸 Screenshots

### 1. GitHub Repository Structure

![Repo](screenshots/1-github-repo.png)

### 2. GitHub Actions Workflow Success

![Actions](screenshots/2-github-actions.png)

### 3. Local Application Output

![Local](screenshots/3-local-output.png)

### 4. EC2 Instance Running

![EC2](screenshots/4-ec2-instance.png)

### 5. EC2 Terminal Deployment

![Terminal](screenshots/5-ec2-terminal.png)

### 6. Live Application Output

![Live](screenshots/6-web-output.png)

### 7. Security Group Configuration

![Security](screenshots/7-security-group.png)

---

## 📚 Key Learnings

* Setting up CI/CD pipelines using GitHub Actions
* Automating deployments to AWS EC2
* Managing secrets securely in GitHub
* Configuring Apache web server on EC2
* Understanding end-to-end DevOps workflow

---

## 🎯 Conclusion

This project showcases a real-world implementation of CI/CD by automating deployment workflows. It highlights how modern DevOps practices improve efficiency, reduce manual effort, and ensure faster delivery.

---

## 👨‍💻 Author

Hariharan R
