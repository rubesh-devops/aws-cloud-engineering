# 🔐 Enterprise IAM Access Governance & Infrastructure Control Architecture

---

## 📌 Project Overview

Designed and implemented a **secure Identity & Access Management (IAM) governance model** during XYZ Corporation’s migration from on-premises infrastructure to AWS.

The objective was to:

- Enable controlled infrastructure provisioning
- Restrict excessive permissions
- Implement role-based access boundaries
- Strengthen cloud security posture

---

## 🎯 Business Challenge

XYZ Corporation faced:

- Increasing infrastructure costs on-premises
- Frequent hardware scaling requirements
- Limited access governance model
- Risk of over-privileged users

Migration to AWS required:

- Secure IAM foundation
- Controlled EC2 lifecycle management
- VPC and RDS provisioning permissions
- Resource protection mechanisms

---

## 🏗 Architecture Components

- **AWS IAM Users**
- **IAM Groups**
- **Custom IAM Policies**
- **Amazon EC2**
- **Amazon VPC (Subnets, NACL, Security Groups)**
- **Amazon RDS**
- **Least Privilege Security Model**

---

## ⚙️ Implementation Summary

### 1️⃣ Console Access & Controlled EC2 Operations

✔ Created IAM User with Console Login  
✔ Configured secure password policy  
✔ Created IAM Group with restricted EC2 permissions  

Group permissions allowed:
- Launch EC2 Instances
- Start EC2 Instances
- Stop EC2 Instances

Restricted:
- Instance termination
- IAM modification
- Billing access
- Other service access

This enforced **controlled infrastructure lifecycle management**.

---

### 2️⃣ Infrastructure Provisioning Permissions

Extended permissions for the user to:

✔ Create VPCs  
✔ Create Subnets  
✔ Configure Network ACLs  
✔ Create and manage Security Groups  
✔ Provision RDS Instances  

This enabled infrastructure expansion while maintaining control.

---

### 3️⃣ Security Hardening & Governance Controls

Implemented additional protection mechanisms:

- Principle of **Least Privilege**
- Segregation of duties via IAM Groups
- Role-based access strategy
- Policy-based permission scoping
- Avoidance of wildcard (*) access
- Restricting IAM modification permissions

Security best practices explored:

- IAM Role-based access instead of static credentials
- MFA enforcement
- CloudTrail monitoring
- Resource tagging strategy
- Billing alerts & monitoring integration

---

## 📊 Governance & Operational Impact

✔ Reduced risk of over-permissioned users  
✔ Enabled controlled infrastructure provisioning  
✔ Secured EC2 lifecycle management  
✔ Implemented scalable IAM governance model  
✔ Strengthened migration security posture  

---

## 🔐 Security Strategy Highlights

- Enforced least privilege
- Separated compute control from network control
- Avoided administrative access leakage
- Established scalable IAM foundation for future growth

---

## 🚀 Outcome

Successfully built a **Secure IAM Governance Framework** supporting:

- Infrastructure scalability
- Controlled cloud adoption
- Secure AWS migration
- Enterprise-grade access management

This implementation forms the **Access Control & Identity Governance Layer** of the AWS Portfolio.

---

## 🏷 Skills Demonstrated

- AWS IAM Users & Groups
- Custom IAM Policies
- Access Control Architecture
- EC2 Permission Governance
- VPC Provisioning Control
- RDS Access Management
- Least Privilege Implementation
- Cloud Security Strategy

---

## 📸 Validation & Evidence

📄 **Execution Screenshots & Policy Configuration Evidence**  
👉 Google Drive: *(Documentation link will be updated)*

---

## 📚 Module Reference

**Module: Introduction to IAM and CloudWatch**  
**Course: DevOps Course**  
**Program: DevOps Architect Master’s Program – Intellipaat**

---
