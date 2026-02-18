# ☁️ CloudFormation – VPC & Public EC2 Infrastructure Deployment

## 📌 Project Overview

To standardize infrastructure deployment across Development, Testing, and Production environments, XYZ Corporation required a reusable CloudFormation template capable of provisioning network infrastructure and compute resources automatically.

This project demonstrates Infrastructure as Code (IaC) by deploying:

- 1 Custom VPC
- 1 Public Subnet
- 1 Amazon Linux EC2 Instance (Tagged: CFinstance)

All components are deployed using AWS CloudFormation to ensure repeatability and governance.

---

## 🎯 Business Objective

Create a reusable CloudFormation template that:

- Provisions a custom VPC
- Creates a public subnet within the VPC
- Launches an Amazon Linux EC2 instance inside the subnet
- Tags the instance as "CFinstance"
- Enables consistent multi-environment deployment

---

## 🏗 Architecture Components

- AWS CloudFormation
- Amazon VPC
- Public Subnet
- Internet Gateway
- Route Table
- Amazon EC2 (Amazon Linux)
- Resource Tagging

---

## ⚙️ Implementation Strategy

### 1️⃣ Network Infrastructure Provisioning

- Defined a custom VPC using CloudFormation
- Created a Public Subnet within the VPC
- Attached Internet Gateway for external connectivity
- Configured Route Table for internet access

---

### 2️⃣ EC2 Instance Deployment

- Launched Amazon Linux EC2 instance inside Public Subnet
- Configured network interface association
- Applied tagging:
  Name = CFinstance

---

### 3️⃣ Stack-Based Deployment

- Template deployed as CloudFormation Stack
- Resources validated via AWS Console
- Verified subnet placement and instance tag configuration

---

## 🛡 Security & Best Practices

- Infrastructure defined as code
- Environment-agnostic reusable template
- Tag-based resource identification
- Controlled network segmentation
- Avoided manual configuration drift

---

## 🚀 Outcomes Achieved

- Automated VPC and EC2 provisioning
- Standardized network architecture
- Reduced deployment time across environments
- Enabled scalable infrastructure rollout
- Improved governance and traceability

---

## 💼 Skills Demonstrated

- Infrastructure as Code (IaC)
- CloudFormation Template Design
- VPC Architecture Design
- EC2 Deployment Automation
- Cloud Networking Fundamentals
- Resource Tagging & Governance

---

## 📸 Validation & Evidence

📄 **Consolidated Execution Documentation**  
👉 Google Drive: *(Documentation link will be updated)*

---

## 📚 Module & Course Reference

**Module 8 – CloudFormation and App Services**  
**AWS Course**  
**Part of DevOps Architect Master’s Program – Intellipaat**
