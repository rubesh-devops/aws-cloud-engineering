# IAM Policy Architecture & Role-Based Access Governance Implementation

---

## 📌 Project Overview

Designed and implemented a structured IAM access control framework in AWS for XYZ Corporation to enforce secure, scalable, and role-based permissions across development and operations teams.

This implementation ensures proper separation of duties while following the Principle of Least Privilege.

---

## 🏢 Business Requirement

XYZ Corporation required:

- Controlled infrastructure access for development teams  
- Monitoring and billing visibility for operations teams  
- Prevention of unauthorized resource modification  
- Centralized and scalable identity governance  

---

## 🛠 Implementation Summary

### 🔹 Development Infrastructure Access Policy

Created a custom IAM policy that enables:

- Full access to Amazon S3  
- Permission to create EC2 instances (restricted scope)  
- Full access to Amazon RDS  

Attached this policy to:

Dev Team IAM Group

---

### 🔹 Operations Monitoring & Cost Governance Policy

Created a second custom IAM policy that enables:

- Full access to CloudWatch  
- Full access to AWS Billing & Cost Explorer  
- Read-only access to EC2 resources  
- Read-only access to S3 resources  

Attached this policy to:

Ops Team IAM Group

---

## 🏗 Access Control Architecture

Implemented group-based permission management:

- Users inherit permissions via IAM groups  
- Policies attached at group level (not user level)  
- Simplified scalability and onboarding  
- Reduced direct permission misconfiguration risk  

---

## 🔐 Security & Governance Strategy

✔ Enforced least privilege access  
✔ Segregated development and operations responsibilities  
✔ Eliminated direct user-level policy attachment  
✔ Reduced blast radius of compromised credentials  
✔ Improved audit readiness and compliance posture  

---

## 📊 Outcome

- Secure IAM governance structure implemented  
- Clear separation of deployment and monitoring access  
- Improved operational visibility  
- Reduced risk of accidental infrastructure changes  
- Enterprise-ready identity management framework  

---

## 🧠 Skills Demonstrated

- IAM Policy Architecture  
- Role-Based Access Control (RBAC)  
- Cloud Governance Design  
- AWS Security Implementation  
- Access Segmentation Strategy  

---

## 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(Documentation link will be updated)*

---

## 📚 Course Reference

Module 3 – Introduction to IAM and CloudWatch  
DevOps Course  
Part of DevOps Architect Master’s Program – Intellipaat
