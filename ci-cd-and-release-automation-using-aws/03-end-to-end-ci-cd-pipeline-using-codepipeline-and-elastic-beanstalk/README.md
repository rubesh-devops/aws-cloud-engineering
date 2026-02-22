# 🔁 End-to-End CI/CD Pipeline Using CodePipeline and Elastic Beanstalk

## 📌 Project Overview

A fully automated Continuous Integration and Continuous Deployment (CI/CD) pipeline was implemented using AWS CodePipeline to deploy a PHP application from GitHub to an Elastic Beanstalk environment.

The objective was to integrate source control with automated deployment so that application updates are automatically built and deployed to a managed platform without manual intervention.

This implementation demonstrates DevOps automation, CI/CD orchestration, and managed application deployment using AWS services.

---

## 🎯 Business Requirement

XYZ Corporation required:

- Automated application deployment  
- Integration with GitHub repository  
- Managed hosting environment  
- Reduced manual release effort  
- Faster development lifecycle  

---

## 🏗 Architecture Implemented

- GitHub Repository (Source Stage)  
- AWS CodePipeline  
- AWS CodeBuild (if applicable)  
- AWS Elastic Beanstalk (PHP Runtime)  
- IAM Roles for Pipeline Execution  
- Automated Deployment Workflow  

---

## ⚙️ Implementation Summary

### 1️⃣ Elastic Beanstalk Environment Setup

- Created Elastic Beanstalk environment  
- Selected PHP runtime platform  
- Configured environment settings  
- Verified environment health  

---

### 2️⃣ CodePipeline Configuration

- Created new CodePipeline  
- Configured GitHub as source provider  
- Connected GitHub repository  
- Defined branch for triggering pipeline  

---

### 3️⃣ Deployment Stage Setup

- Configured Elastic Beanstalk as deployment provider  
- Linked pipeline to existing Beanstalk environment  
- Defined artifact handling  
- Enabled automatic execution on code changes  

---

### 4️⃣ Pipeline Validation

- Committed code changes to GitHub  
- Triggered automatic pipeline execution  
- Monitored pipeline stages  
- Verified successful deployment on Beanstalk URL  

---

## 🔐 Security Configuration

- IAM role assigned to CodePipeline  
- GitHub connection secured  
- Least privilege access enforced  
- Environment access controlled via security groups  

---

## 📊 Outcome Achieved

- Successfully implemented automated CI/CD pipeline  
- Enabled GitHub-triggered deployments  
- Eliminated manual release processes  
- Reduced deployment time  
- Built scalable DevOps automation workflow  

---

## 🛠 Skills Demonstrated

- AWS CodePipeline Configuration  
- GitHub Integration with AWS  
- Elastic Beanstalk Deployment  
- CI/CD Pipeline Automation  
- IAM Role Configuration  
- Release Management Strategy  
- DevOps Workflow Implementation  

---

## 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(Documentation link will be updated)*  

---

## 🎓 Course Reference

Program: AWS Solutions Architect Track  
Track: DevOps & CI/CD Implementation on AWS
