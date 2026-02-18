# AWS CodePipeline PHP Application CI/CD with Elastic Beanstalk

## 📌 Project Overview

XYZ Corporation required a fully automated CI/CD pipeline to streamline application deployments directly from source control to a managed AWS environment.

To achieve this, AWS CodePipeline was implemented to integrate GitHub as the source stage and deploy a PHP application to an Elastic Beanstalk environment automatically.

This project demonstrates end-to-end AWS-native CI/CD pipeline implementation.

---

## 🎯 Objective

Automate application deployment by:

- Integrating GitHub as source repository
- Creating a CodePipeline workflow
- Deploying PHP application to Elastic Beanstalk
- Eliminating manual deployment processes

---

## 🏗️ Architecture Summary

- GitHub Repository (PHP Application Source)
- AWS CodePipeline
- AWS CodeBuild (if required in pipeline stage)
- AWS Elastic Beanstalk (PHP Runtime)
- IAM Roles for pipeline execution

---

## ⚙️ Implementation Summary

### 1️⃣ Source Stage Configuration

- Connected GitHub repository containing PHP application.
- Configured webhook integration for automatic pipeline trigger on code push.
- Verified successful source artifact retrieval.

### 2️⃣ Build Stage (Optional if Included)

- Configured build stage (if required).
- Validated artifact packaging for deployment.

### 3️⃣ Deployment Stage Configuration

- Selected Elastic Beanstalk as deployment provider.
- Configured existing PHP runtime environment.
- Linked application and environment to pipeline.

### 4️⃣ Pipeline Execution

- Triggered pipeline automatically via GitHub commit.
- Verified successful deployment to Elastic Beanstalk.
- Confirmed updated application version running in environment.

---

## 🔐 Security & Governance

- IAM roles configured for least-privilege access.
- Secure GitHub integration using OAuth connection.
- Controlled environment-level deployment permissions.

---

## 🚀 DevOps Impact

- Enabled automated build and deployment workflow.
- Reduced deployment time and human error.
- Established CI/CD best practices using AWS managed services.
- Improved development-to-production release cycle.

---

## 📊 Outcome

- Successfully implemented AWS CodePipeline.
- Automated PHP application deployment from GitHub to Elastic Beanstalk.
- Achieved fully managed CI/CD lifecycle in AWS cloud.

---

## 📸 Validation & Evidence

📄 **Consolidated Execution Documentation**  
👉 Google Drive: (Documentation link will be updated)

---

## 🎓 Course Reference

DevOps Course  
DevOps Architect Master’s Program – Intellipaat  
AWS DevOps Module
