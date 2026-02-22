# 🚀 Elastic Beanstalk High Availability PHP Orchestration with External RDS

## 📌 Project Overview

A highly available and scalable PHP web application was orchestrated using AWS Elastic Beanstalk with an external Amazon RDS database to decouple application and database lifecycles.

The objective was to deploy a production-ready PHP application using managed platform services while ensuring high availability, automated scaling, and independent database management.

This implementation demonstrates cloud-native application orchestration, blue/green deployment readiness, and scalable infrastructure automation.

---

## 🎯 Business Requirement

The organization required:

- Fast website orchestration with minimal manual configuration  
- High availability with Auto Scaling  
- Managed platform deployment  
- External database decoupled from application lifecycle  
- Support for blue/green deployments  

---

## 🏗 Architecture Implemented

- AWS Elastic Beanstalk (PHP Runtime Environment)  
- Amazon RDS (External Database)  
- Application Load Balancer (Managed by Beanstalk)  
- Auto Scaling Group (Managed by Beanstalk)  
- Security Groups for Application–DB Communication  
- Multi-AZ Deployment for High Availability  

---

## ⚙️ Implementation Summary

### 1️⃣ RDS Database Deployment

- Created Amazon RDS instance  
- Configured MySQL engine  
- Enabled automated backups  
- Placed DB in appropriate subnet group  
- Configured security groups to allow traffic from Beanstalk environment  
- Verified database accessibility  

---

### 2️⃣ Elastic Beanstalk Environment Creation

- Created Elastic Beanstalk environment  
- Selected PHP runtime platform  
- Configured instance type and capacity  
- Enabled Auto Scaling (minimum and maximum instances)  
- Verified environment health  

---

### 3️⃣ Application Deployment

- Uploaded PHP application package  
- Configured environment variables for external RDS endpoint  
- Updated database connection settings  
- Deployed application  
- Verified successful integration with RDS  

---

### 4️⃣ Scaling and High Availability Configuration

- Enabled Auto Scaling policies  
- Configured load balancing  
- Validated instance scaling behavior  
- Confirmed database persistence during environment updates  

---

## 🔐 Security Configuration

- Restricted RDS inbound access to Beanstalk security group only  
- Controlled HTTP/HTTPS access via load balancer  
- IAM roles configured for Elastic Beanstalk  
- No direct public database exposure  

---

## 📊 Outcome Achieved

- Successfully orchestrated high-availability PHP application  
- Implemented external RDS for lifecycle decoupling  
- Enabled Auto Scaling and load balancing  
- Achieved blue/green deployment readiness  
- Reduced deployment time using managed services  

---

## 🛠 Skills Demonstrated

- Elastic Beanstalk Environment Management  
- External RDS Database Integration  
- Auto Scaling Configuration  
- Load Balancer Management  
- Application–Database Decoupling Strategy  
- Blue/Green Deployment Readiness  
- Cloud-Native Orchestration  

---

## 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(Documentation link will be updated)*  

---

## 🎓 Course Reference

Program: AWS Solutions Architect Track  
Track: Application Orchestration & High Availability Architecture
