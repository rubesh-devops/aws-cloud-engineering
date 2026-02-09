# Multi-OS Shared Storage Architecture using Amazon EFS

## 📌 Project Overview

Designed and implemented a centralized shared storage architecture using Amazon Elastic File System (EFS) connected to three EC2 instances running different operating systems:

- Ubuntu  
- Red Hat Enterprise Linux (RHEL)  
- Amazon Linux 2  

This project demonstrates cross-platform shared storage configuration using a highly available and scalable NFS-based solution inside a VPC.

---

## 🎯 Objective

Implement centralized, persistent, and scalable shared storage across multiple EC2 instances running different Linux distributions.

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

---

### 2️⃣ EC2 Deployment

- Launched three EC2 instances:
  - Ubuntu
  - Red Hat Enterprise Linux
  - Amazon Linux 2
- Enabled SSH access
- Installed NFS client packages

---

### 3️⃣ EFS Configuration

- Created Amazon EFS file system
- Configured Mount Targets in respective Availability Zones
- Attached Security Group allowing NFS traffic (Port 2049)

---

### 4️⃣ Mounting EFS on All Instances

Installed NFS utilities:

**Ubuntu**
sudo apt install nfs-common -y


**Amazon Linux / RHEL**
sudo yum install nfs-utils -y


Mounted EFS:
sudo mount -t nfs4 <efs-dns-name>:/ /mnt/efs


Configured persistent mount using `/etc/fstab`.

---

### 5️⃣ Validation

- Created a file from Ubuntu instance
- Verified same file visible in:
  - Red Hat instance
  - Amazon Linux 2 instance
- Confirmed centralized shared storage functioning successfully

---

## 🔐 Security Configuration

- Restricted NFS access via Security Groups
- Controlled SSH access using key-based authentication
- EFS accessible only within VPC
- Followed principle of least privilege

---

## 📈 Key Learning Outcomes

- Distributed shared storage architecture design
- Cross-OS file system mounting
- NFS protocol implementation in AWS
- Multi-AZ high availability storage design
- Security Group configuration
- Persistent mount configuration using fstab
- Cloud-based centralized storage implementation

---

## 🏆 Real-World Use Cases

- Web server clusters
- Containerized workloads
- Shared application logs
- Microservices architectures
- Scalable enterprise applications

---

## 📊 Outcome

Successfully deployed a scalable shared storage solution across multiple EC2 instances with different operating systems.

Validated real-time file synchronization across all nodes.

---

## 🛠 Skills Demonstrated

- Amazon EFS
- EC2 Multi-OS Deployment
- NFS Configuration
- Linux Administration
- VPC Networking
- High Availability Architecture
- Infrastructure Troubleshooting

---

## 📄 Implementation Proof

Detailed execution screenshots and validation outputs:

👉 [Download Implementation PDF](02-efs-multi-os-shared-storage-proof.pdf)

---

## 📚 Course Reference

Completed as part of:

**AWS Solutions Architect – DevOps Architect Master’s Program (Intellipaat)**

Certificate available in main repository.
