# 🚀 CodeDeploy EC2 Deployment Group and Automation Implementation

## 📌 Project Overview

An automated application deployment workflow was implemented using AWS CodeDeploy with EC2 as the compute platform.

The objective was to create a CodeDeploy application, configure a deployment group, and integrate selected EC2 instances to enable controlled and repeatable application deployments.

This implementation demonstrates deployment automation, infrastructure targeting, and DevOps release management using AWS-native services.

---

## 🎯 Business Requirement

XYZ Corporation required:

- Automated deployment to EC2 instances  
- Reduced manual release effort  
- Controlled deployment strategy  
- Centralized deployment management  
- Cloud-native DevOps automation  

---

## 🏗 Architecture Implemented

- AWS CodeDeploy Application  
- EC2 Compute Platform  
- Deployment Group Configuration  
- IAM Service Role for CodeDeploy  
- Target EC2 Instance(s)  
- AppSpec-based Deployment Model  

---

## ⚙️ Implementation Summary

### 1️⃣ CodeDeploy Application Creation

- Created CodeDeploy application  
- Selected EC2/On-Premises compute platform  
- Configured application name and settings  

---

### 2️⃣ IAM Role Configuration

- Created/assigned CodeDeploy service role  
- Granted necessary permissions  
- Ensured secure deployment execution  

---

### 3️⃣ Deployment Group Setup

- Created deployment group  
- Selected EC2 instance(s) via tags  
- Configured deployment settings  
- Enabled automatic rollback (optional best practice)  

---

### 4️⃣ Deployment Validation

- Initiated deployment from repository  
- Monitored deployment status  
- Verified successful application installation  
- Confirmed service availability on EC2  

---

## 🔐 Security Configuration

- IAM role with least privilege permissions  
- EC2 instances associated with correct IAM profile  
- Security groups configured appropriately  
- Controlled deployment targeting via tagging  

---

## 📊 Outcome Achieved

- Successfully configured CodeDeploy application  
- Automated deployment to EC2 instances  
- Reduced manual deployment intervention  
- Established repeatable release process  
- Built scalable DevOps deployment foundation  

---

## 🛠 Skills Demonstrated

- AWS CodeDeploy Configuration  
- EC2 Deployment Automation  
- IAM Role Setup for Deployment  
- Deployment Group Targeting  
- Release Automation Strategy  
- DevOps CI/CD Foundations  
- Infrastructure Deployment Management  

---

## 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(Documentation link will be updated)*  

---

## 🎓 Course Reference

Program: AWS Solutions Architect Track  
Track: DevOps & CI/CD Implementation on AWS
