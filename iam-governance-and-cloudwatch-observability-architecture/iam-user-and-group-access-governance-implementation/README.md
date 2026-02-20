# 👥 IAM User and Group Access Governance Implementation

## 📌 Project Overview

A structured Identity and Access Management (IAM) governance model was implemented to organize users based on roles and responsibilities within the AWS environment.

The objective was to create a scalable access control structure using IAM users and groups, enabling centralized permission management and improved visibility across the organization.

This implementation demonstrates foundational AWS identity governance aligned with enterprise security best practices.

---

## 🎯 Business Requirement

XYZ Corporation required:

- Structured identity management for AWS users  
- Logical grouping of users based on roles  
- Simplified access administration  
- Improved visibility and monitoring of user activities  

---

## 🏗 Architecture Implemented

- AWS IAM Users  
- AWS IAM Groups  
- Role-based access organization structure  
- Centralized permission assignment through group membership  

---

## ⚙️ Implementation Summary

### 1️⃣ IAM User Creation

Created four IAM users to represent development and testing roles:

- Dev1  
- Dev2  
- Test1  
- Test2  

Each user was configured with secure console access credentials.

---

### 2️⃣ IAM Group Creation

Created two logical access groups:

- Dev Team  
- Ops Team  

These groups were designed to manage access collectively instead of assigning permissions individually.

---

### 3️⃣ Group Membership Configuration

Configured group memberships as follows:

- Dev1 and Dev2 added to **Dev Team**
- Dev1, Test1, and Test2 added to **Ops Team**

This approach allows a single user (Dev1) to belong to multiple groups, enabling cross-functional access modeling.

---

## 🔐 Security Configuration

- Implemented least privilege access design  
- Avoided direct policy attachment to users  
- Used group-based access control for scalability  
- Prepared structure for future policy attachment and monitoring  
- Enabled IAM activity visibility through AWS logging mechanisms  

---

## 📊 Outcome Achieved

- Established structured IAM governance model  
- Enabled scalable permission management  
- Reduced administrative overhead  
- Improved user role clarity  
- Prepared environment for monitoring and auditing  

---

## 🛠 Skills Demonstrated

- AWS IAM User Management  
- IAM Group-Based Access Control  
- Role Segregation Strategy  
- Identity Governance Best Practices  
- Multi-Group Membership Configuration  
- Secure AWS Account Structuring  

---

## 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(https://drive.google.com/file/d/1uAzTeiNNxVDZY5H-modZEM_xudRbo44w/view?usp=drive_link)*  

---

## 🎓 Course Reference

Module: AWS Identity and Monitoring  
Program: AWS Solutions Architect Track  
Track: Cloud Engineering & Architecture Implementation
