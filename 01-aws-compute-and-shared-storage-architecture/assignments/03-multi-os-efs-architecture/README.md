# 🗂 Multi-OS Shared File System Architecture using Amazon EFS

---

## 📌 Project Overview

Implemented a **centralized, highly available shared storage architecture** using **Amazon Elastic File System (EFS)** connected to three EC2 instances running different Linux operating systems.

This assignment demonstrates real-world **cross-platform shared storage configuration** in AWS using a scalable and distributed NFS-based solution.

---

## 🏗 Infrastructure Components Used

- Amazon EC2 (Ubuntu, Red Hat Enterprise Linux, Amazon Linux 2)
- Amazon Elastic File System (EFS)
- Mount Targets (Multi-AZ)
- Security Groups
- VPC & Subnets
- NFS Protocol

---

## 🎯 Objective

To design and implement **persistent, centralized, and shared storage** across multiple EC2 instances running different operating systems while ensuring high availability.

---

## ⚙️ Implementation Summary

### 1️⃣ Network Configuration
- Used VPC with subnets across Availability Zones
- Configured Security Groups to allow:
  - SSH (Port 22)
  - NFS (Port 2049)

### 2️⃣ EC2 Deployment
- Launched three EC2 instances:
  - Ubuntu
  - Red Hat Enterprise Linux
  - Amazon Linux 2
- Installed NFS client utilities on all instances

### 3️⃣ EFS Configuration
- Created Amazon EFS file system
- Configured Mount Targets in multiple Availability Zones
- Attached proper Security Group allowing NFS traffic

### 4️⃣ Mounting EFS Across Instances
- Mounted EFS on all three instances
- Configured persistent mount configuration
- Ensured storage remains attached after reboot

### 5️⃣ Validation
- Created file from Ubuntu instance
- Verified same file visible on:
  - Red Hat instance
  - Amazon Linux 2 instance
- Confirmed real-time shared storage synchronization

---

## 🔐 Security Implementation

- Restricted NFS traffic via Security Groups
- EFS accessible only within VPC
- Controlled SSH access to instances
- Ensured isolated internal storage architecture

---

## 📈 Key Learning Outcomes

- Distributed file storage architecture in AWS
- Cross-OS shared file system configuration
- NFS protocol implementation in cloud
- Multi-AZ high availability storage design
- Persistent mount configuration
- Storage access control using Security Groups

---

## 🏆 Real-World Use Cases

This architecture is commonly used in:

- Web server clusters
- Containerized microservices
- Shared application logs
- Enterprise application environments
- Scalable production systems

---

## 📊 Outcome

Successfully deployed a centralized shared storage system across multiple EC2 instances running different operating systems.

Validated real-time file synchronization and high availability configuration.

---

## 🛠 Skills Demonstrated

- Amazon EFS Architecture
- EC2 Multi-OS Deployment
- NFS Configuration
- Linux System Administration
- VPC Networking
- Storage High Availability Design
- Cloud Storage Troubleshooting

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
