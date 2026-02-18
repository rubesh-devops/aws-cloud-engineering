# AWS CodeDeploy EC2 Application Automation

## 📌 Project Overview

XYZ Corporation required automation for application deployments after securing source code within AWS. To streamline deployment workflows and reduce manual intervention, AWS CodeDeploy was implemented to automate application deployment to EC2 instances.

This implementation demonstrates infrastructure-level deployment automation using AWS-native DevOps services.

---

## 🎯 Objective

Automate application deployment to EC2 instances using AWS CodeDeploy by:

- Creating a CodeDeploy application
- Configuring EC2-based deployment group
- Enabling structured and repeatable deployment workflows
- Reducing manual server-level deployment tasks

---

## 🏗️ Architecture Summary

- AWS CodeDeploy (Application)
- EC2 Compute Platform
- IAM Role for CodeDeploy
- Deployment Group targeting EC2 instance
- Integrated with AWS CodeCommit (from previous task)

---

## ⚙️ Implementation Summary

### 1️⃣ CodeDeploy Application Creation

- Created a CodeDeploy Application.
- Selected **EC2/On-Premises** as compute platform.
- Configured service role with appropriate IAM permissions.

### 2️⃣ Deployment Group Configuration

- Created a Deployment Group.
- Selected the target EC2 instance.
- Attached IAM role with required EC2 and deployment permissions.
- Configured deployment settings and rollback behavior.

### 3️⃣ Deployment Validation

- Verified successful deployment status in CodeDeploy dashboard.
- Confirmed application files were deployed on EC2 instance.
- Ensured deployment lifecycle hooks executed correctly.

---

## 🔐 Security & Governance

- IAM roles used for secure service-to-service communication.
- Deployment limited to specific EC2 instances via tagging.
- Controlled deployment policies and rollback configuration enabled.

---

## 🚀 DevOps Impact

- Eliminated manual SSH-based deployments.
- Enabled structured deployment lifecycle.
- Reduced risk of configuration drift.
- Prepared environment for CI/CD pipeline integration.

---

## 📊 Outcome

- Successfully automated EC2 application deployment using AWS CodeDeploy.
- Established scalable deployment mechanism.
- Created foundation for full CI/CD pipeline using AWS DevOps services.

---

## 📸 Validation & Evidence

📄 **Consolidated Execution Documentation**  
👉 Google Drive: (Documentation link will be updated)

---

## 🎓 Course Reference

DevOps Course  
DevOps Architect Master’s Program – Intellipaat  
AWS DevOps Module
