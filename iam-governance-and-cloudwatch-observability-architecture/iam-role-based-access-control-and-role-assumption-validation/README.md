# 🛡️ IAM Role-Based Access Control and Role Assumption Validation

## 📌 Project Overview

A secure IAM role-based access control model was implemented to provide controlled elevated permissions to specific users without directly attaching high-privilege policies to them.

The objective was to design an IAM Role granting full access to Amazon VPC and DynamoDB services, and allow only authorized users to assume this role when required.

This implementation demonstrates secure privilege delegation, temporary access elevation, and AWS role assumption validation.

---

## 🎯 Business Requirement

XYZ Corporation required:

- Controlled elevated access to networking and database services  
- Avoidance of direct high-privilege user permissions  
- Temporary privilege escalation mechanism  
- Clear audit visibility of access usage  

---

## 🏗 Architecture Implemented

- AWS IAM Role  
- Trust Policy restricting role assumption to specific users  
- Inline/Managed Policy granting full access to:
  - Amazon VPC  
  - Amazon DynamoDB  
- Role assumption testing via AWS Console  

---

## ⚙️ Implementation Summary

### 1️⃣ IAM Role Creation

Created a custom IAM role with:

- Full access permissions for:
  - Amazon VPC
  - Amazon DynamoDB  

Attached required managed or custom policies to the role.

---

### 2️⃣ Trust Policy Configuration

Configured the trust relationship to allow only:

- User1  
- User2  

to assume the role.

This ensured that no other IAM users could elevate privileges using this role.

---

### 3️⃣ Role Assumption Validation

- Logged in as User1  
- Switched role via AWS Console  
- Verified successful privilege elevation  
- Confirmed access to VPC and DynamoDB resources  

Validated that permissions were only active while the role was assumed.

---

## 🔐 Security Configuration

- No direct full-access policy attached to users  
- Implemented temporary privilege model  
- Restricted role assumption through trust policy  
- Enforced least privilege design  
- Enabled audit visibility through AWS logging  

---

## 📊 Outcome Achieved

- Successfully implemented role-based privilege elevation  
- Restricted high-level access to authorized users only  
- Reduced long-term security exposure  
- Improved governance and accountability  
- Demonstrated secure AWS access control architecture  

---

## 🛠 Skills Demonstrated

- IAM Role Creation  
- Trust Policy Configuration  
- Role Assumption Validation  
- Temporary Privilege Elevation  
- VPC and DynamoDB Permission Management  
- AWS Security Best Practices  

---

## 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(https://drive.google.com/file/d/1sno3slZKdwYI2P8jLcB4fa4aKzelTrju/view?usp=drive_link)*  

---

## 🎓 Course Reference

Module: AWS Identity and Monitoring  
Program: AWS Solutions Architect Track  
Track: Cloud Engineering & Architecture Implementation
