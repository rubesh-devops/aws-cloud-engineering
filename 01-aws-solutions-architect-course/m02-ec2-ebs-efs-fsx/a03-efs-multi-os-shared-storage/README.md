# 📂 Amazon EFS Deployment & Multi-OS EC2 Integration Validation

## 📌 Project Overview

As part of AWS shared storage implementation, a scalable and highly available file storage system was deployed using Amazon Elastic File System (EFS) and mounted across multiple EC2 instances running different operating systems.

The objective was to demonstrate centralized file storage accessible across heterogeneous Linux environments.

This implementation validates cross-platform shared storage architecture in AWS.

---

## 🎯 Business Requirement

XYZ Corporation required:

- Centralized shared file storage
- Mounting storage across multiple EC2 instances
- Support for different Linux operating systems
- High availability and scalable storage

---

## 🏗 Architecture Implemented

- Amazon EFS (Regional File System)
- EC2 Ubuntu Instance
- EC2 Red Hat Linux Instance
- EC2 Amazon Linux 2 Instance
- Mount Targets in Availability Zones
- Security Groups for NFS access (Port 2049)

---

## ⚙️ Implementation Summary

### 1️⃣ EFS File System Creation

- Created an Amazon EFS file system
- Configured mount targets in required subnets
- Applied security group allowing NFS traffic (Port 2049)
- Enabled lifecycle management for cost optimization

---

### 2️⃣ EC2 Instances Deployment

- Launched three EC2 instances:
  - Ubuntu
  - Red Hat Linux
  - Amazon Linux 2
- Configured SSH access
- Installed required NFS utilities on each OS

---

### 3️⃣ Mounting EFS Across All Instances

- Mounted EFS on Ubuntu instance
- Mounted EFS on Red Hat Linux instance
- Mounted EFS on Amazon Linux 2 instance
- Created test files from different instances
- Verified file visibility across all servers

---

## 🔐 Security Configuration

- Restricted NFS access to specific security groups
- No public exposure of EFS endpoints
- EC2 instances secured via SSH key authentication
- IAM-based access control applied

---

## 📊 Outcome Achieved

- Successfully provisioned centralized EFS storage
- Mounted shared storage across 3 different Linux OS instances
- Validated file synchronization across servers
- Demonstrated cross-platform shared file architecture

---

## 🛠 Skills Demonstrated

- Amazon EFS Deployment
- Cross-OS Shared Storage Configuration
- NFS Protocol Implementation
- EC2 Multi-Instance Architecture
- Secure Network File Access
- High Availability File System Design

---

## 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(Documentation link will be updated)*

---

## 🎓 Course Reference

Module: Introduction to EC2, EBS, EFS and Amazon FSx  
Program: AWS Solutions Architect Course  
Track: DevOps Architect Master’s Program – Intellipaat
