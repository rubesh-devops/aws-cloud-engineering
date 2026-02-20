# 🔐 IAM Policy-Based Access Control Architecture Implementation

## 📌 Project Overview

A structured policy-based access control model was implemented using AWS Identity and Access Management (IAM) to enforce role-driven permissions across development and operations teams.

The objective was to design and attach custom IAM policies that align with business responsibilities while maintaining least-privilege security principles.

This implementation demonstrates granular permission control, policy design, and scalable group-based access management.

---

## 🎯 Business Requirement

XYZ Corporation required:

- Role-based permission segregation  
- Controlled access to AWS services  
- Centralized policy management through IAM groups  
- Improved visibility and monitoring of user activities  

---

## 🏗 Architecture Implemented

- Custom IAM Policies  
- IAM Groups (Dev Team & Ops Team)  
- Group-based policy attachment model  
- Service-level permission restrictions  
- Principle of least privilege enforcement  

---

## ⚙️ Implementation Summary

### 1️⃣ Policy Design – Development Team Access Model

Created a custom policy granting:

- Full access to Amazon S3  
- Permission to create EC2 instances (restricted to instance creation only)  
- Full access to Amazon RDS  

This policy was structured to support development workloads while restricting unnecessary administrative privileges.

---

### 2️⃣ Policy Design – Operations Team Access Model

Created a second custom policy granting:

- Full access to CloudWatch for monitoring and observability  
- Full access to AWS Billing information  
- Read-only (List) permissions for EC2 and S3 resources  

This ensured the operations team could monitor infrastructure without modifying core services.

---

### 3️⃣ Group-Based Policy Attachment

- Attached Development policy to **Dev Team** group  
- Attached Operations policy to **Ops Team** group  

This approach eliminates direct policy attachment to individual users, improving scalability and maintainability.

---

## 🔐 Security Configuration

- Implemented least privilege model  
- Avoided direct user-level policy assignment  
- Segregated duties between development and operations  
- Restricted sensitive modification permissions  
- Ensured billing visibility only for authorized users  

---

## 📊 Outcome Achieved

- Established structured role-based access control  
- Improved access governance across teams  
- Reduced risk of privilege misuse  
- Enhanced monitoring capability for operations  
- Enabled scalable permission management  

---

## 🛠 Skills Demonstrated

- IAM Custom Policy Creation  
- JSON Policy Design  
- Role-Based Access Control (RBAC)  
- Group-Level Policy Attachment  
- AWS Service Permission Segregation  
- Least Privilege Security Implementation  

---

## 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(https://drive.google.com/file/d/1dMjlECwSiZUEQNknesvhMlEPw0maCmdh/view?usp=drive_link)*  

---

## 🎓 Course Reference

Module: AWS Identity and Monitoring  
Program: AWS Solutions Architect Track  
Track: Cloud Engineering & Architecture Implementation
