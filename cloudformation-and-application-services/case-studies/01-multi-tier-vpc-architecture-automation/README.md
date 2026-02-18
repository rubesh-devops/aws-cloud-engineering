# 🏗 Multi-Tier VPC Architecture with Route 53 & Stack Protection

## 📌 Project Overview

XYZ Corporation required a secure, production-ready multi-tier architecture to deploy and test a new web application without constant involvement from system administrators.

This project demonstrates the implementation of:

- 3-Tier AWS Architecture (Web, Application, Database)
- Secure VPC Design with Public & Private Subnets
- Controlled Security Group Communication
- Amazon RDS MySQL Deployment
- Route 53 DNS Routing
- Infrastructure Automation & Stack Protection Strategy

---

## 🎯 Business Objective

Build a scalable and secure multi-tier infrastructure that:

- Separates Web, Application, and Database layers
- Restricts access between tiers using security best practices
- Enables developers to test independently
- Prevents accidental deletion of critical database resources
- Supports domain-based routing

---

## 🏗 Architecture Design

### 🌐 Web Tier (Public Subnet)

- EC2 instance deployed in Public Subnet
- Security Group allows:
  - HTTP (Port 80) from Internet
  - SSH (Port 22) from Internet
- Acts as the frontend layer
- Connected to Route 53 domain

---

### ⚙️ Application Tier (Private Subnet)

- EC2 instance deployed in Private Subnet
- Security Group allows:
  - SSH only from Web Tier
- No direct internet access
- Processes application logic securely

---

### 🗄 Database Tier (Private Subnet)

- Amazon RDS MySQL instance deployed in Private Subnet
- Security Group allows:
  - MySQL (Port 3306) only from Application Tier
- No public exposure
- Fully isolated database layer

---

## 🌍 DNS Configuration

- Created Route 53 Hosted Zone
- Mapped domain to Web Tier EC2 Public IP
- Enabled domain-based access to the application

---

## 🔐 Security Architecture

- Network segmentation using Public & Private Subnets
- Strict Security Group rules for controlled inter-tier communication
- No direct internet access to Application & Database tiers
- Principle of Least Privilege enforced
- Database accessible only via Application layer

---

## 🚀 Developer Enablement Strategy

To allow the development team to deploy and test independently:

- Infrastructure defined using Infrastructure as Code (CloudFormation)
- Predefined stack templates for consistent deployments
- Automated provisioning of EC2, RDS, VPC resources
- Developers can launch and delete test stacks without admin dependency

---

## 🛡 RDS Protection Strategy

To prevent accidental deletion of the database:

- Enabled Deletion Protection on RDS instance
- Configured Stack Retention Policy for RDS resource
- Ensured database persists even if CloudFormation stack is deleted

---

## 📈 Outcomes Achieved

- Fully functional 3-tier secure AWS architecture
- Isolated application layers for enhanced security
- Independent developer testing environment
- Protected database layer from accidental deletion
- Production-ready networking and DNS configuration
- Enterprise-grade infrastructure design

---

## 💼 Skills Demonstrated

- AWS VPC Architecture Design
- Public & Private Subnet Configuration
- Security Groups & Network Segmentation
- Amazon RDS MySQL Deployment
- Route 53 DNS Configuration
- Multi-Tier Application Architecture
- Infrastructure as Code Strategy
- Stack Retention & Deletion Protection
- Secure Cloud Infrastructure Design

---

## 📸 Validation & Evidence

📄 **Consolidated Execution Documentation**  
👉 Google Drive: *(Documentation link will be updated)*

---

## 📚 Module & Course Reference

**Module 8 – CloudFormation and App Services**  
**AWS Course**  
**Part of DevOps Architect Master’s Program – Intellipaat**
