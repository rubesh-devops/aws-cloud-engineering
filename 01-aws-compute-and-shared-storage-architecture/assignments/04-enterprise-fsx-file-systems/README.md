# 🗄 Enterprise File Sharing & High-Performance Storage using Amazon FSx

---

## 📌 Project Overview

Designed and implemented enterprise-grade file storage solutions using **Amazon FSx for Windows File Server** and **Amazon FSx for Lustre** to support:

- High-performance file sharing
- Integration with Active Directory
- On-premises data replication support
- HPC and analytics workloads

This assignment demonstrates practical implementation of AWS managed file systems for both Windows and Linux environments.

---

## 🏗 Infrastructure Components Used

- Amazon FSx for Windows File Server
- AWS Managed Microsoft Active Directory
- Windows EC2 Instance
- Amazon FSx for Lustre
- Amazon Linux 2 EC2 Instance
- VPC & Security Groups

---

## 🎯 Objective

To implement:

1. A Windows-compatible managed file system integrated with Active Directory
2. A high-performance Lustre file system optimized for Linux workloads

---

## ⚙️ Implementation Summary

### 1️⃣ FSx for Windows File Server

- Created AWS Managed Microsoft Active Directory
- Configured valid domain name
- Deployed FSx for Windows File Server
- Joined FSx to Active Directory domain
- Connected Windows EC2 instance to the domain
- Mounted the FSx shared drive on Windows EC2
- Verified file creation and shared access

### 2️⃣ FSx for Lustre

- Created Amazon FSx for Lustre file system
- Deployed Amazon Linux 2 EC2 instance
- Installed Lustre client utilities
- Mounted Lustre file system on Linux instance
- Validated high-performance file access and storage

---

## 🔐 Security & Access Configuration

- Integrated FSx Windows with AWS Managed AD
- Restricted access using Security Groups
- Enabled domain-level authentication for Windows file sharing
- Configured VPC-level isolation
- Ensured controlled mount access for Linux instances

---

## 📈 Key Learning Outcomes

- Enterprise file system deployment in AWS
- Active Directory integration with cloud storage
- Windows-based network file sharing architecture
- High-performance distributed file system (Lustre)
- Hybrid cloud storage replication concepts
- Managed storage scalability & performance optimization

---

## 🏆 Real-World Use Cases

This architecture is commonly used for:

- Enterprise Windows file servers
- Hybrid cloud file storage
- High-performance computing (HPC)
- Big data analytics workloads
- Machine learning pipelines
- Media rendering farms
- Financial modeling environments

---

## 📊 Outcome

Successfully deployed and validated:

- Active Directory integrated Windows file server
- High-performance Lustre file system for Linux workloads

Demonstrated enterprise-grade cloud storage architecture capable of supporting hybrid infrastructure and high-throughput workloads.

---

## 🛠 Skills Demonstrated

- Amazon FSx (Windows & Lustre)
- AWS Managed Microsoft AD
- Windows Domain Integration
- Linux File System Mounting
- Enterprise File Sharing Architecture
- Hybrid Storage Design
- High-Performance Cloud Storage
- Infrastructure Security Configuration

---

## 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: (Documentation link will be updated)

---

## 📚 Course Reference

This assignment is part of:

**Module 2 – Introduction to EC2, EBS, EFS and Amazon FSx**  
**AWS Solutions Architect Course**  
Part of **DevOps Architect Master’s Program – Intellipaat**
