# 🏗️ AWS Multi-Tier Web Application Architecture (Web, App & DB)

---

## 📌 **Project Overview**

Designed and implemented a **secure and scalable multi-tier architecture on AWS** to support the testing of a new web-based application for XYZ Corporation.

This case study demonstrates how **Web, Application, and Database tiers** can be isolated using **VPC subnets and security controls**, while enabling developers to **self-provision infrastructure using automation**, without relying on system administrators.

---

## 🏗 **Architecture Components**

- **Amazon EC2 (Web Tier)**
- **Amazon EC2 (Application Tier)**
- **Amazon RDS (MySQL) – Database Tier**
- **Amazon VPC**
- **Public & Private Subnets**
- **Security Groups**
- **Amazon Route 53**
- **AWS CloudFormation**
- **Multi-Tier Architecture Design**

---

## 🎯 **Objective**

To design an architecture that:

- Separates **Web, Application, and Database tiers**
- Enforces **strict network security and access control**
- Enables developers to **deploy and test applications independently**
- Prevents accidental deletion of **database resources**
- Supports automated provisioning and teardown

---

## ⚙️ **Implementation Steps**

### 1️⃣ **Web Tier Deployment**

- Launched an **EC2 instance** in a **public subnet**
- Configured security group to allow:
  - **HTTP (Port 80)** from the internet
  - **SSH (Port 22)** from the internet
- Used this instance as the entry point for application traffic

---

### 2️⃣ **Application Tier Deployment**

- Launched an **EC2 instance** in a **private subnet**
- Configured security group to:
  - Allow **SSH access only from the Web Tier public subnet**
- Ensured no direct internet access to the application tier
- Used this tier for business logic and application processing

---

### 3️⃣ **Database Tier Deployment**

- Created an **Amazon RDS MySQL instance**
- Deployed RDS in a **private subnet**
- Configured security group to allow:
  - **MySQL (Port 3306)** access only from the **Application Tier private subnet**
- Ensured database is not publicly accessible

---

### 4️⃣ **Route 53 DNS Configuration**

- Created a **Route 53 hosted zone**
- Configured DNS record to route traffic to the **Web Tier EC2 instance**
- Enabled domain-based access to the application

---

### 5️⃣ **Automation & Stack Protection**

- Used **AWS CloudFormation** to automate resource provisioning
- Enabled developers to deploy and delete stacks independently
- Configured **DeletionPolicy: Retain** for RDS to:
  - Prevent database deletion when the stack is deleted
  - Protect critical data from accidental loss

---

## 🔐 **Security & Architecture Configuration**

- Network isolation using **public and private subnets**
- Strict **security group-based access control**
- No direct internet access to application and database tiers
- Database access restricted to application layer only
- Automated provisioning reduced human error

---

## 📈 **Key Learning Outcomes**

- Multi-tier architecture design in AWS
- Secure VPC subnet planning
- Tier-based access control using security groups
- Route 53 DNS routing
- CloudFormation-based automation
- Resource lifecycle management
- Protecting critical resources using retention policies

---

## 🏆 **Real-World Use Case**

This architecture is widely used in:

- Enterprise web applications
- Dev/Test/Prod environments
- Secure application deployments
- Cloud migration from on-premise systems
- DevOps-driven development workflows
- Applications requiring strong data protection

---

## 📊 **Outcome**

Successfully deployed a **secure, automated, multi-tier AWS architecture** that:

- Enables developers to test applications independently
- Enforces strong security between tiers
- Automates infrastructure provisioning
- Protects critical database resources from deletion
- Reduces dependency on system administrators

---

## 🛠 **Skills Demonstrated**

- AWS Multi-Tier Architecture Design
- Amazon EC2 & RDS Integration
- VPC Networking & Subnet Design
- Security Group Configuration
- Route 53 DNS Management
- AWS CloudFormation (IaC)
- Resource Retention & Data Protection
- DevOps-Friendly Infrastructure Automation

---

## 📸 **Proof of Implementation**

📄 Consolidated Assignment Execution PDF:  
👉 *https://drive.google.com/file/d/1-F6uNehOLDD18LJS3PfyPucLy2PRlQy_/view?usp=drive_link*

---

## 📚 **Course Reference**

Case Study completed as part of:

**AWS Solutions Architect – DevOps Architect Master’s Program (Intellipaat)**  

Certificate available in the main repository.
