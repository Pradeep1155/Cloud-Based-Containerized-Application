# Cloud-Based Containerized Application Deployment

##  Overview

This project demonstrates the deployment of a Dockerized web application on Amazon Web Services (AWS). The application is hosted on multiple EC2 instances and distributed through an Application Load Balancer (ALB) to provide high availability and improved reliability.

---

##  Objectives

- Containerize a web application using Docker.
- Deploy the application on AWS EC2 instances.
- Configure an Application Load Balancer.
- Distribute traffic across multiple EC2 instances.
- Demonstrate a highly available cloud deployment.

---

##  Technologies

- Amazon EC2
- Application Load Balancer (ALB)
- Docker
- Red Hat Enterprise Linux
- HTML
- CSS
- JavaScript
- Git
- GitHub

---

##  Repository Structure

```
Cloud-Based-Containerized-Application/
│
├── Dockerfile
├── index.html
├── style.css
├── script.js
└── README.md
```

---

##  Deployment Workflow

```
Developer
     │
     ▼
GitHub Repository
     │
     ▼
Docker Image
     │
     ▼
Amazon EC2 Instance 1
Amazon EC2 Instance 2
     │
     └──────────────┐
                    ▼
       Application Load Balancer
                    │
                    ▼
                End Users
```

---

##  Docker
Dockerhub image
docker pull pradeep1155/calculator-app:v1
### Build Image

```bash
docker build -t calculator-app .
```

### Run Container

```bash
docker run -d -p 80:80 calculator-app
```

### Verify Container

```bash
docker ps
```

---

##  AWS Infrastructure

- 2 Amazon EC2 Instances
- Docker Engine
- Application Load Balancer
- Target Group
- Security Groups
- Public Subnets
- Internet Gateway

---

## 🔄 Request Flow

```
User Request
      │
      ▼
Application Load Balancer
      │
 ┌────┴────┐
 │         │
 ▼         ▼
EC2-1    EC2-2
 │         │
Docker   Docker
 │         │
Calculator Application
```

---

##  Screenshots



---

## 📚 Skills Demonstrated

- Docker Containerization
- AWS EC2 Management
- Application Load Balancer Configuration
- High Availability Architecture
- Linux Administration
- Git Version Control
- GitHub Repository Management

---

## 🎓 Learning Outcomes

- Deploy applications using Docker.
- Configure AWS networking.
- Implement Load Balancing.
- Manage Linux servers.
- Understand cloud deployment architecture.

---

## 👨‍💻 Author

**Pradeep Kumar**

**Role:** Aspiring DevOps & Cloud Engineer

GitHub: https://github.com/Pradeep1155

---

### ⭐ If you like this project, give it a Star!
