# 🗄️ RDS MariaDB Engine Deployment & Connectivity Validation

## 📌 Project Overview

As part of AWS Database Services implementation, a managed relational database solution was designed using Amazon RDS with MariaDB engine.

The objective was to provision a highly available SQL database service and validate connectivity from both Windows and Linux environments.

This implementation demonstrates enterprise-grade database deployment, secure connectivity configuration, and cross-platform client access validation.

---

## 🎯 Business Requirement

XYZ Corporation required:

- A managed SQL database service
- High availability and automated backups
- Secure database connectivity
- Cross-platform access (Windows & Linux)

---

## 🏗 Architecture Implemented

- Amazon RDS (MariaDB Engine)
- Public/Private Subnet Placement (as per architecture)
- Security Group Configuration for controlled access
- EC2 Linux Instance for database connectivity validation
- SQL Client (Windows) for remote access testing

---

## ⚙️ Implementation Summary

### 1️⃣ RDS MariaDB Deployment

- Selected MariaDB as the database engine
- Configured DB instance class
- Allocated storage
- Enabled automated backups
- Configured VPC and subnet group
- Applied security groups to allow controlled MySQL access
- Configured master username and password

---

### 2️⃣ Connectivity from Windows (SQL Client)

- Installed MySQL-compatible SQL client
- Used RDS endpoint for connection
- Provided:
  - Endpoint DNS
  - Port (3306)
  - Username
  - Password
- Successfully connected and validated database operations

---

### 3️⃣ Connectivity from Linux EC2 Instance

- Launched Amazon Linux EC2 instance
- Installed MySQL client package
- Connected using RDS endpoint
- Executed sample SQL commands to validate connectivity

---

## 🔐 Security Configuration

- Restricted inbound access on port 3306
- Allowed only specific IP / security group access
- No open public database exposure
- IAM access controlled at account level
- Credentials managed securely

---

## 📊 Outcome Achieved

- Successfully deployed MariaDB RDS instance
- Validated cross-platform connectivity
- Confirmed SQL read/write capability
- Implemented secure database access model
- Demonstrated managed database deployment in AWS

---

## 🛠 Skills Demonstrated

- Amazon RDS Deployment
- MariaDB Engine Configuration
- VPC Networking for Database
- Security Group Configuration
- SQL Connectivity Validation
- Cross-Platform Database Access
- Managed Database Best Practices

---

## 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(Documentation link will be updated)*

---

## 🎓 Course Reference

Module: AWS Database Services  
Program: DevOps Course  
Track: DevOps Architect Master’s Program – Intellipaat

