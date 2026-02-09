# Multi-OS Shared Storage Architecture using Amazon EFS

## 📌 Project Overview

Designed and implemented a shared file storage architecture using Amazon Elastic File System (EFS) connected to three EC2 instances running different operating systems:

- Ubuntu
- Red Hat Enterprise Linux
- Amazon Linux 2

This project demonstrates cross-platform shared storage configuration in AWS using a highly available and scalable NFS-based solution.

---

## 🏗 Architecture Components

- Amazon EC2 (Ubuntu, RHEL, Amazon Linux 2)
- Amazon EFS
- Mount Targets (Multi-AZ)
- Security Groups
- NFS (Network File System)
- VPC & Subnets

---

## 🎯 Objective

To implement centralized, persistent, and scalable shared storage across multiple EC2 instances running different Linux distributions.

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
- Installed NFS client packages on all instances

---

### 3️⃣ EFS Configuration
- Created Amazon EFS
- Configured Mount Targets in respective Availability Zones
- Attached appropriate Security Group allowing NFS traffic

---

### 4️⃣ Mounting EFS on All Instances

Installed NFS utilities:

Ubuntu:
sudo apt install nfs-common -y

Amazon Linux:
sudo yum install nfs-utils -y

Red Hat:
sudo yum install nfs-utils -y

Mounted EFS:
sudo mount -t nfs4 <efs-dns-name>:/ /mnt/efs

Made mount persistent using `/etc/fstab`.

---

### 5️⃣ Validation

- Created file from Ubuntu instance
- Verified same file visible in:
  - Red Hat instance
  - Amazon Linux 2 instance
- Confirmed centralized shared storage working successfully

---

## 🔐 Security Configuration

- Restricted NFS access to Security Group
- Controlled inbound access via SSH
- EFS accessible only within VPC

---

## 📈 Key Learning Outcomes

- Understanding distributed shared storage architecture
- Cross-OS file system mounting
- NFS protocol configuration in AWS
- Multi-AZ high availability storage design
- Security Group configuration for storage access
- Persistent mount configuration using fstab
- Cloud-based centralized storage implementation

---

## 🏆 Real-World Use Case

This architecture is commonly used in:

- Web server clusters
- Containerized workloads
- Shared application logs
- Microservices architecture
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
- High Availability Design
- Infrastructure Troubleshooting

---

## 📸 Proof of Implementation

Detailed execution screenshots, validation outputs, and configuration steps:
- EFS creation
- Mount target configuration
- EC2 instances dashboard
- Terminal mounting commands
- Cross-instance file validation


👉 [Download Implementation PDF](02-efs-multi-os-shared-storage-proof.pdf)


---

## 📚 Course Reference

Assignment completed as part of:
AWS Solutions Architect – DevOps Architect Master’s Program (Intellipaat)

Certificate available in main repository.

