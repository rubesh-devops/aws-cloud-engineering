# 🏗 High Availability Multi-Tier Web Application Deployment with Auto Scaling and RDS

## 📌 Project Overview

A production-ready multi-tier web architecture was designed and deployed using Amazon EC2, Auto Scaling, and Amazon RDS to ensure high availability and scalability for a PHP-based web application.

The objective was to migrate an existing on-premise MySQL and PHP-based application to AWS while implementing horizontal scaling and managed database services to support dynamic traffic demands.

This implementation demonstrates high availability architecture, database integration, and auto scaling strategy in a cloud-native environment.

---

## 🎯 Business Requirement

Company ABC required:

- Migration of PHP website and MySQL database to AWS  
- High availability for the web application  
- Automatic scaling during traffic spikes  
- Managed relational database service  
- Secure communication between application and database tiers  

---

## 🏗 Architecture Implemented

- Amazon EC2 (Web Tier – PHP Application)  
- EC2 Auto Scaling Group (Minimum 2 Instances)  
- Application Load Balancer (Recommended for HA)  
- Amazon RDS MySQL (Database Tier)  
- Security Groups for Controlled Communication  
- Multi-Tier Architecture (Web + DB Layer)  

---

## ⚙️ Implementation Summary

### 1️⃣ EC2 Web Server Deployment

- Launched EC2 instance  
- Installed Apache, PHP, and required dependencies  
- Deployed PHP website  
- Configured security group to allow HTTP and SSH access  
- Verified website accessibility  

---

### 2️⃣ Auto Scaling Configuration

- Created launch template  
- Configured Auto Scaling group  
- Set minimum instances to 2  
- Enabled scaling policies (CPU-based)  
- Attached Load Balancer for traffic distribution  
- Validated scaling behavior  

---

### 3️⃣ RDS MySQL Deployment

- Created Amazon RDS MySQL instance  
- Configured database credentials  
- Created database:
  - **Database Name:** `intel`  
  - **Table Name:** `data`  
  - **Password:** `intel123`  
- Enabled automated backups  
- Verified database connectivity  

---

### 4️⃣ Application–Database Integration

- Updated website configuration file with RDS endpoint  
- Modified hostname settings  
- Verified successful DB connection from EC2  
- Tested data insertion and retrieval  

---

### 5️⃣ Network and Security Configuration

- Allowed inbound HTTP/SSH traffic to EC2  
- Allowed MySQL traffic (3306) from EC2 security group to RDS  
- Restricted public database exposure  
- Validated secure communication  

---

## 🔐 Security Configuration

- Security group-level access control  
- Controlled RDS access via EC2 security group  
- No public RDS exposure  
- IAM-based administrative control  
- Auto Scaling integrated with secure launch template  

---

## 📊 Outcome Achieved

- Successfully migrated multi-tier application to AWS  
- Enabled high availability with minimum 2 EC2 instances  
- Integrated managed RDS database  
- Implemented horizontal scaling strategy  
- Achieved resilient and scalable cloud architecture  

---

## 🛠 Skills Demonstrated

- Multi-Tier Architecture Design  
- EC2 Deployment and Configuration  
- Auto Scaling Group Setup  
- RDS MySQL Configuration  
- Load Balancer Integration  
- Secure Application–Database Communication  
- High Availability Cloud Design  
- Production-Ready Deployment Strategy  

---

## 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(Documentation link will be updated)*  

---

## 🎓 Course Reference

Program: AWS Solutions Architect Track  
Track: High Availability Architecture & Scalable Application Deployment
