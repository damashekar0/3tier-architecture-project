

# 📌 Project Overview

This project demonstrates the deployment of a **secure and scalable 3-Tier Web Application Architecture on AWS**.

The architecture separates the application into three layers:

* **Web Tier (Presentation Layer)**
* **Application Tier (Business Logic Layer)**
* **Database Tier (Data Layer)**

This architecture improves **scalability, security, and high availability**.

---

# ☁️ AWS Services Used

* Amazon VPC
* Amazon EC2
* Elastic Load Balancer (Application Load Balancer)
* Amazon RDS
* Amazon Route53
* AWS Certificate Manager
* Amazon S3
* Internet Gateway
* NAT Gateway
* Security Groups
* IAM Roles

---

# 🏗️ Architecture Diagram

Add your architecture diagram here.

```
Internet
   |
Route53
   |
Application Load Balancer
   |
Public Subnet (Web Tier)
   |
Private Subnet (Application Tier)
   |
Private Subnet (Database Tier - RDS)
```

---

# 📂 Project Structure

```
3tier-architecture-project
│
├── README.md
├── architecture-diagram.png
│
├── screenshots
│   ├── vpc.png
│   ├── subnets.png
│   ├── nat-gateway.png
│   ├── ec2-instances.png
│   ├── load-balancer.png
│   ├── route53.png
│   ├── acm-certificate.png
│   └── final-output.png
│
├── app-code
│   ├── index.php
│   └── db.php
│
└── deployment
    ├── nginx.conf
    ├── userdata.sh
    └── database.sql
```

---

# ⚙️ Deployment Steps

### 1️⃣ Create VPC

* Create custom VPC
* Configure CIDR block
* Create public and private subnets

### 2️⃣ Configure Networking

* Attach Internet Gateway
* Create NAT Gateway
* Configure Route Tables

### 3️⃣ Launch EC2 Instances

* Web server in public subnet
* Application server in private subnet

### 4️⃣ Configure Load Balancer

* Create Application Load Balancer
* Create target group
* Register EC2 instances

### 5️⃣ Setup Database

* Launch Amazon RDS instance
* Configure security groups

### 6️⃣ Setup Domain and HTTPS

* Configure Route53 hosted zone
* Request SSL certificate using AWS Certificate Manager
* Attach certificate to Load Balancer

---

# 📸 Screenshots

### VPC Setup

![VPC](screenshots/vpc.png)

### EC2 Instances

![EC2](screenshots/ec2-instances.png)

### Load Balancer

![ALB](screenshots/load-balancer.png)

### Route53 Domain Configuration

![Route53](screenshots/route53.png)

### SSL Certificate

![ACM](screenshots/acm-certificate.png)

### Final Website Output

![Website](screenshots/final-output.png)

---

# 🎯 Project Outcome

* Deployed scalable web application on AWS
* Implemented secure 3-tier architecture
* Configured domain with HTTPS
* Improved application security and availability

---

# 👨‍💻 Author

**Shekar Dama**

GitHub:
https://github.com/damashekar0
