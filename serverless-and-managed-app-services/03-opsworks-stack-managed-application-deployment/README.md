# ⚙️ Managed Application Deployment using AWS OpsWorks Stack

## 📌 Project Overview

Designed and implemented a **configuration-managed web application deployment** using AWS OpsWorks to automate provisioning, scaling, and application updates.

This solution enables centralized configuration management while ensuring consistency across multiple EC2 instances.

---

## 🎯 Business Requirement

XYZ Corporation required:

- Managed infrastructure provisioning
- Centralized application deployment
- Automatic configuration management
- Scalable environment with multiple instances
- Real-time code update propagation across servers

---

## 🏗 Architecture Implemented

**Deployment Model:**

Git Repository → AWS OpsWorks Stack → Managed EC2 Instances → Application Deployment

Key Components:

- OpsWorks Stack
- Application Layer
- EC2 Instances (t2.medium)
- Git-based deployment
- Chef-based configuration management

---

## ⚙️ Implementation Summary

### 1️⃣ Created OpsWorks Stack
- Selected sample stack template
- Configured stack settings
- Defined application layer
- Launched initial EC2 instance
- Deployed web application from repository

---

### 2️⃣ Scaled Infrastructure
- Added 2 additional t2.medium instances
- Instances automatically configured via OpsWorks
- Ensured uniform configuration across all nodes

---

### 3️⃣ Repository Code Update Validation
- Modified application code in repository
- Triggered redeployment
- Verified that updates reflected across all instances
- Confirmed centralized configuration management

---

## 🔐 Infrastructure & Management Controls

- Centralized configuration via Chef recipes
- Automated instance provisioning
- Layer-based deployment architecture
- Version-controlled application deployment
- Consistent environment across all instances

---

## 📈 Outcomes Achieved

- Automated multi-instance deployment
- Centralized configuration management
- Reduced manual server management
- Seamless horizontal scaling
- Uniform application updates across cluster

---

## 💼 Skills Demonstrated

- AWS OpsWorks
- Configuration Management (Chef-based)
- Stack & Layer Architecture
- Multi-Instance Deployment
- Git-based Application Deployment
- Infrastructure Automation

---

## 🏆 Real-World Use Case

This architecture is suitable for:

- Managed web application clusters
- Chef-based infrastructure automation
- Centralized configuration control
- Multi-instance production environments
- DevOps-driven deployment pipelines

---

## 📸 Validation & Evidence

📄 **Consolidated Execution Documentation**  
👉 Google Drive: *(Documentation link will be updated)*

---

## 📚 Module & Course Reference

**Module 9 – AWS Lambda, Elastic Beanstalk, AWS OpsWorks and API Gateway**  
**AWS Course**  
**Part of DevOps Architect Master’s Program – Intellipaat**
