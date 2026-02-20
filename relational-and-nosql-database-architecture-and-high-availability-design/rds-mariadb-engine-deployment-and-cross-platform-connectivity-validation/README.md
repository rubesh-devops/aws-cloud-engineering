# 🗄️ RDS MariaDB Engine Deployment and Cross-Platform Connectivity Validation

## 📌 Project Overview

A managed relational database solution was designed and deployed using Amazon RDS with the MariaDB engine to support application data storage requirements.

The objective was to provision a highly available SQL database and validate secure connectivity from both Windows and Linux environments.

This implementation demonstrates enterprise-grade database provisioning, secure access configuration, and cross-platform database connectivity validation.

---

## 🎯 Business Requirement

XYZ Corporation required:

- A managed SQL database engine  
- High availability and automated backups  
- Secure and controlled database access  
- Cross-platform connectivity validation  

---

## 🏗 Architecture Implemented

- Amazon RDS (MariaDB Engine)  
- VPC-based Deployment  
- Subnet Group Configuration  
- Security Group for Controlled Access  
- Windows SQL Client Connectivity  
- Linux EC2 Instance for CLI-Based Access  

---

## ⚙️ Implementation Summary

### 1️⃣ MariaDB RDS Deployment

- Selected MariaDB as database engine  
- Configured DB instance class  
- Allocated storage  
- Enabled automated backups  
- Configured VPC and subnet group  
- Set master username and password  
- Applied security group allowing MySQL (Port 3306) access from trusted sources  

---

### 2️⃣ Connectivity Validation – Windows SQL Client

- Installed MySQL-compatible SQL client on Windows  
- Connected using RDS endpoint  
- Provided:
  - Endpoint DNS  
  - Port 3306  
  - Username  
  - Password  
- Executed sample SQL commands to validate connectivity  

---

### 3️⃣ Connectivity Validation – Linux EC2 Instance

- Launched Amazon Linux EC2 instance  
- Installed MySQL client package  
- Connected using RDS endpoint via CLI  
- Executed sample queries to confirm read/write capability  

---

## 🔐 Security Configuration

- Restricted inbound traffic to Port 3306  
- Allowed only specific IP ranges or security group references  
- Prevented public exposure unless explicitly required  
- Enforced least privilege network access  
- Maintained credential confidentiality  

---

## 📊 Outcome Achieved

- Successfully deployed MariaDB RDS instance  
- Validated connectivity from Windows and Linux platforms  
- Confirmed SQL read/write operations  
- Implemented secure database access model  
- Demonstrated managed relational database architecture  

---

## 🛠 Skills Demonstrated

- Amazon RDS Deployment  
- MariaDB Engine Configuration  
- VPC and Subnet Group Configuration  
- Security Group Design for Databases  
- Cross-Platform Database Connectivity  
- SQL Validation and Testing  
- Managed Database Best Practices  

---

## 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(https://drive.google.com/file/d/1RNjfKyDCph-XoPuzN6mXzWCp1XrVtUzF/view?usp=drive_link)*  

---

## 🎓 Course Reference

Program: AWS Solutions Architect Track  
Track: Cloud Engineering & Architecture Implementation
