# 🏗️ AWS Multi-Tier Website Deployment with EC2, Auto Scaling & RDS

---

## 📌 **Project Overview**

Designed and deployed a **highly available multi-tier web application architecture on AWS** for Company ABC as part of their migration from on-premise infrastructure to the cloud.

This project demonstrates how **Amazon EC2**, **Auto Scaling**, and **Amazon RDS (MySQL)** can be combined to deliver a **scalable, resilient, and production-ready web application** capable of handling traffic spikes without manual intervention.

---

## 🧩 **Business Problem**

Company ABC currently runs a **PHP-based website** backed by a **MySQL database** on traditional infrastructure.

Challenges faced:
- Limited scalability
- Single point of failure
- Manual capacity planning
- Difficulty handling traffic spikes

The company requires:
- **High availability**
- **Automatic scaling**
- **Managed database service**
- **Minimal operational overhead**

---

## 🏗 **Architecture Components**

- **Amazon EC2 (Web/Application Tier)**
- **Auto Scaling Group (Minimum 2 Instances)**
- **Amazon RDS (MySQL) – Database Tier**
- **Elastic Load Balancer (optional / implicit via ASG)**
- **VPC & Security Groups**
- **PHP Web Application**
- **MySQL Database**

---

## 🎯 **Objective**

To implement a cloud-native solution that:

- Migrates a PHP + MySQL application to AWS
- Enables **Auto Scaling** for high availability
- Uses **Amazon RDS** for managed database operations
- Allows secure communication between application and database layers
- Supports traffic growth without manual scaling

---

## ⚙️ **Implementation Flow**

### 1️⃣ **EC2 Web/Application Tier**

- Launched an **EC2 instance** with required OS and PHP stack
- Deployed the PHP website on the instance
- Verified application functionality

---

### 2️⃣ **Auto Scaling Configuration**

- Created an **Auto Scaling Group**
- Configured:
  - Minimum instances: **2**
  - Desired capacity to ensure availability
- Enabled automatic scaling to handle traffic spikes
- Ensured new instances launch with application configuration

---

### 3️⃣ **RDS MySQL Database Setup**

- Created an **Amazon RDS MySQL instance**
- Configured database details:
  - **Database name:** `intel`
  - **Table name:** `data`
  - **Database password:** `intel123`
- Verified RDS availability and endpoint

---

### 4️⃣ **Database & Application Integration**

- Created required **database and table** inside RDS
- Updated **database hostname** in the PHP application
- Ensured application points to RDS endpoint instead of local DB

---

### 5️⃣ **Security Group Configuration**

- Allowed **all traffic** to EC2 instances (as per project requirement)
- Configured RDS security group to:
  - Allow **MySQL (Port 3306)** traffic only from EC2 instances
- Ensured database is not publicly accessible

---

## 🔐 **Security & High Availability Design**

- Application tier scaled using **Auto Scaling**
- Database isolated in a managed **RDS service**
- Network-level access control using **Security Groups**
- Eliminated single point of failure at the application layer
- AWS-managed services reduce operational risk

---

## 📈 **Key Learning Outcomes**

- Multi-tier architecture design on AWS
- EC2 Auto Scaling configuration
- RDS MySQL provisioning and connectivity
- PHP application migration to cloud
- Secure application-to-database communication
- High availability and scalability concepts
- Cloud-based production readiness

---

## 🏆 **Real-World Use Case**

This architecture is commonly used for:

- E-commerce websites
- SaaS applications
- Content management systems
- Enterprise web applications
- Production workloads requiring high availability
- Cloud migration from on-premise systems

---

## 📊 **Outcome**

Successfully deployed a **scalable, highly available PHP web application** backed by **Amazon RDS MySQL**.

The application now:
- Automatically scales with traffic
- Maintains availability during instance failures
- Uses managed database services for reliability
- Is production-ready on AWS infrastructure

---

## 🛠 **Skills Demonstrated**

- Amazon EC2
- Auto Scaling Groups
- Amazon RDS (MySQL)
- PHP Application Deployment
- Multi-Tier Architecture Design
- Cloud Networking & Security Groups
- High Availability Design
- AWS Cloud Migration Concepts

---

## 📸 **Proof of Implementation**

📄 Consolidated Project Execution PDF (Screenshots & Validation):  
👉 *https://drive.google.com/file/d/17Sy4pt4-vYzVgpQOpR1USivMahJFAUd1/view?usp=drive_link*

---

## 📚 **Course / Capstone Reference**

Project completed as part of:

**DevOps Architect Master’s Program – Intellipaat**

Certificate available in the main portfolio repository.
