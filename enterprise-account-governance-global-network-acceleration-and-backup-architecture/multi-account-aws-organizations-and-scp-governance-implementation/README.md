# 🏢 Multi-Account AWS Organizations and SCP Governance Implementation

## 📌 Project Overview

A centralized multi-account governance structure was implemented using AWS Organizations to manage accounts securely and enforce policy-based restrictions.

The objective was to create an AWS Organization, define multiple Organizational Units (OUs), and apply Service Control Policies (SCPs) to restrict access exclusively to Amazon EC2 services.

This implementation demonstrates enterprise-grade account governance, centralized access control, and policy enforcement at scale.

---

## 🎯 Business Requirement

XYZ Corporation required:

- Centralized multi-account management  
- Logical account segregation using Organizational Units  
- Controlled service-level access across accounts  
- Enforcement of least-privilege governance policies  

---

## 🏗 Architecture Implemented

- AWS Organizations  
- Organizational Units (OU1, OU2, OU3)  
- Service Control Policy (SCP)  
- EC2-Only Access Restriction Model  
- Root and OU-Level Policy Attachment  

---

## ⚙️ Implementation Summary

### 1️⃣ AWS Organization Setup

- Created AWS Organization  
- Enabled all features mode  
- Established centralized management account  

---

### 2️⃣ Organizational Unit Configuration

- Created three Organizational Units:
  - OU1  
  - OU2  
  - OU3  
- Structured accounts under respective OUs  

---

### 3️⃣ Service Control Policy (SCP) Enforcement

- Created custom SCP policy  
- Allowed access only to Amazon EC2 service  
- Denied access to all other AWS services  
- Attached SCP to Organizational Units  
- Validated service restriction behavior  

---

## 🔐 Security Configuration

- SCP enforced at OU level  
- Centralized governance applied from management account  
- Restricted non-EC2 service access  
- Applied principle of least privilege  

---

## 📊 Outcome Achieved

- Successfully implemented multi-account governance  
- Established hierarchical account structure  
- Enforced EC2-only service policy  
- Demonstrated enterprise-level AWS account control  
- Built scalable account management foundation  

---

## 🛠 Skills Demonstrated

- AWS Organizations Setup  
- Organizational Unit Management  
- Service Control Policy (SCP) Creation  
- Multi-Account Governance  
- Enterprise Cloud Security Controls  
- Access Restriction Strategy  
- Cloud Compliance Implementation  

---

## 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(Documentation link will be updated)*  

---

## 🎓 Course Reference

Program: AWS Solutions Architect Track  
Track: Cloud Governance & Enterprise Architecture Implementation
