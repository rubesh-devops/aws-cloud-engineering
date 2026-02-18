# 🚀 Automation & Configuration Management using Beanstalk, Lambda & OpsWorks

## 📌 Project Overview

Designed and implemented a **fully automated cloud-native deployment architecture** using AWS managed services including:

- Elastic Beanstalk
- AWS Lambda
- Amazon S3
- AWS OpsWorks

This solution demonstrates automated deployment, serverless event-driven architecture, and configuration-managed infrastructure.

---

## 🎯 Business Requirement

XYZ Organization required:

- Managed hosting for PHP-based web application
- Automated update deployment capability
- Event-driven serverless execution
- Configuration-managed infrastructure provisioning
- Minimal manual server management

---

## 🏗 Architecture Implemented

### Deployment Layers:

Elastic Beanstalk → Managed PHP Application Hosting  
S3 → Event Source  
Lambda → Serverless Processing  
OpsWorks → Configuration Managed EC2 Stack  

---

## ⚙️ Implementation Summary

### 1️⃣ Elastic Beanstalk Environment Deployment

- Created a Beanstalk environment with PHP runtime
- Deployed a custom PHP application
- Validated application availability via environment URL
- Ensured managed infrastructure provisioning by AWS

---

### 2️⃣ Application Update Deployment

- Uploaded updated PHP file displaying:
  
  **"Updated Hello World"**
  
- Triggered environment deployment
- Verified successful application update without downtime

---

### 3️⃣ Serverless Event-Driven Automation

- Created an S3 bucket
- Configured object creation event as Lambda trigger
- Developed Lambda function to execute upon new object upload
- Verified automatic invocation via CloudWatch logs

---

### 4️⃣ Configuration Managed Stack using OpsWorks

- Created OpsWorks stack
- Provisioned EC2 instance within stack
- Hosted “Hello World” HTML page
- Validated centralized configuration management
- Confirmed application availability via instance public IP

---

## 🔐 Automation & Governance Controls

- Managed environment provisioning via Elastic Beanstalk
- Event-driven automation using S3 + Lambda
- Configuration management using OpsWorks
- Version-controlled deployments
- Reduced infrastructure overhead

---

## 📈 Outcomes Achieved

- Fully managed PHP hosting
- Zero-downtime update deployment
- Serverless automation workflow
- Configuration-driven infrastructure management
- Scalable cloud-native architecture

---

## 💼 Skills Demonstrated

- AWS Elastic Beanstalk
- AWS Lambda (Event-driven architecture)
- Amazon S3 Event Triggers
- AWS OpsWorks
- Configuration Management
- Serverless Architecture
- Application Lifecycle Automation
- Cloud Deployment Strategy

---

## 🏆 Real-World Use Case

This architecture is suitable for:

- Enterprise web application hosting
- Event-driven serverless automation
- Continuous application deployment
- Managed infrastructure provisioning
- DevOps automation workflows

---

## 📸 Validation & Evidence

📄 **Consolidated Execution Documentation**  
👉 Google Drive: *(Documentation link will be updated)*

---

## 📚 Module & Course Reference

**Module 9 – AWS Lambda, Elastic Beanstalk, AWS OpsWorks and API Gateway**  
**AWS Course**  
**Part of DevOps Architect Master’s Program – Intellipaat**
