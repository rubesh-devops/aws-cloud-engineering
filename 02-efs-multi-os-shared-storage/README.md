# Multi-OS Shared Storage Architecture using Amazon EFS

## 📌 Project Overview

Designed and implemented a centralized shared file storage architecture using **Amazon Elastic File System (EFS)** connected to three EC2 instances running different operating systems:

- Ubuntu
- Red Hat Enterprise Linux (RHEL)
- Amazon Linux 2

This project demonstrates cross-platform shared storage configuration using a highly available, scalable NFS-based solution within a VPC.

---

## 🎯 Objective

To implement centralized, persistent, and scalable shared storage across multiple EC2 instances running different Linux distributions.

---

## 🏗 Architecture Components

- Amazon EC2 (Ubuntu, RHEL, Amazon Linux 2)
- Amazon EFS
- Mount Targets (Multi-AZ)
- Security Groups
- NFS (Network File System)
- VPC & Subnets

---

## ⚙️ Implementation Steps

### 1️⃣ Network Preparation
- Used existing VPC with public subnets
- Configured Security Group to allow:
  - Port 22 (SSH)
  - Port 2049 (NFS)

### 2️⃣ EC2 Deployment
- Launched three EC2 instances:
  - Ubuntu
  - Red Hat Enterprise Linux
  - Amazon Linux 2
- Enabled SSH access
- Installed NFS client packages on all instances

### 3️⃣ EFS Configuration
- Created Amazon EFS file system
- Configured Mount Targets in respective Availability Zones
- Attached Security Group allowing NFS traffic (Port 2049)

### 4️⃣ Mounting EFS on All Instances

Installed NFS utilities:

Ubuntu:
```bash
sudo apt install nfs-common -y
