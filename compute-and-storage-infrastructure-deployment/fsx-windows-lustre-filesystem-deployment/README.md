# 🗂 Amazon FSx Multi-Platform File System Deployment & Integration Validation

## 📌 Project Overview

As part of high-performance file storage implementation, Amazon FSx was deployed to support both Windows-based file sharing and high-performance computing workloads.

The objective was to configure:

- Amazon FSx for Windows File Server integrated with AWS Managed Active Directory
- Amazon FSx for Lustre integrated with Amazon Linux 2

This implementation demonstrates enterprise-grade file system integration for hybrid workloads and cross-platform environments.

---

## 🎯 Business Requirement

XYZ Corporation required:

- Faster file sharing within the organization
- Active Directory integrated Windows file storage
- High-performance file system for Linux workloads
- Support for on-premises style replication capabilities
- Secure and scalable managed file systems

---

## 🏗 Architecture Implemented

- AWS Managed Microsoft Active Directory
- Amazon FSx for Windows File Server
- Windows EC2 Instance (Domain Joined)
- Amazon FSx for Lustre
- Amazon Linux 2 EC2 Instance
- VPC with Private Subnets
- Security Groups for SMB (445) and Lustre traffic

---

## ⚙️ Implementation Summary

### 1️⃣ AWS Managed Active Directory Setup

- Created AWS Managed Microsoft AD
- Configured valid domain name
- Deployed directory within VPC subnets
- Verified directory health and availability

---

### 2️⃣ FSx for Windows File Server Deployment

- Created FSx for Windows file system
- Integrated with AWS Managed AD
- Configured storage capacity and throughput
- Enabled automatic backups
- Created file share within the Windows file system

---

### 3️⃣ Windows EC2 Integration

- Launched Windows EC2 instance
- Joined instance to the managed domain
- Mounted FSx Windows file share using SMB protocol
- Verified read/write operations successfully

---

### 4️⃣ FSx for Lustre Deployment

- Created FSx for Lustre file system
- Configured deployment type
- Associated with appropriate subnet
- Applied security groups for access control

---

### 5️⃣ Amazon Linux 2 Integration

- Launched Amazon Linux 2 EC2 instance
- Installed Lustre client packages
- Mounted FSx Lustre file system
- Created and validated file operations

---

## 🔐 Security Configuration

- Domain-based authentication for Windows file access
- Restricted SMB (Port 445) access within VPC
- Restricted Lustre client access to specific security groups
- IAM-based access control enforced
- No public exposure of file systems

---

## 📊 Outcome Achieved

- Successfully deployed Windows-based managed file system
- Integrated file sharing with Active Directory
- Mounted high-performance Lustre storage on Linux
- Demonstrated cross-platform enterprise storage architecture
- Validated secure file access and operations

---

## 🛠 Skills Demonstrated

- Amazon FSx for Windows Configuration
- Amazon FSx for Lustre Deployment
- AWS Managed Microsoft AD Integration
- Domain Joining EC2 Instances
- SMB and Lustre Protocol Configuration
- Enterprise File Storage Architecture
- Secure Network File System Implementation

---

## 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(Documentation link will be updated)*

---

## 🎓 Course Reference

Module: Introduction to EC2, EBS, EFS and Amazon FSx  
Program: AWS Solutions Architect Course  
Track: DevOps Architect Master’s Program – Intellipaat
