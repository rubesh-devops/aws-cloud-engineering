# 🚀 Secured Multi-Region Web Server Deployment using AMI & EBS

---

## 📌 Project Overview

Designed and implemented a secured Linux web server infrastructure for XYZ Corporation with:

- Deployment in **US-East-1 (N. Virginia)**
- Cross-region replication to **US-West-2 (Oregon)**
- EBS volume lifecycle management
- Backup using EBS Snapshots
- AMI-based replication strategy

This project demonstrates **high availability, disaster recovery, storage management, and backup strategy implementation in AWS**.

---

## 🏗 Architecture Components

- Amazon EC2 (Linux)
- Amazon Machine Image (AMI)
- Amazon EBS Volumes
- EBS Snapshots
- VPC & Security Groups
- Multi-Region Deployment (us-east-1 & us-west-2)

---

## 🎯 Objective

To design a **secured, scalable, and replicable Linux web server architecture** with proper storage lifecycle management and backup strategy.

---

## ⚙️ Implementation Steps

### 1️⃣ EC2 Deployment (Primary Region – us-east-1)

- Launched Linux EC2 instance in **US-East-1 (N. Virginia)**
- Configured Security Group:
  - Port 22 (SSH)
  - Port 80 (HTTP)
- Installed and configured web server (Apache/Nginx)

---

### 2️⃣ AMI Creation & Cross-Region Replication

- Created custom **AMI** from running EC2 instance
- Copied AMI to **US-West-2 (Oregon)**
- Launched replicated instance in secondary region

✅ Achieved **Disaster Recovery Setup**

---

### 3️⃣ EBS Volume Management

- Created **two EBS volumes**
- Attached both volumes to EC2 instance
- Formatted and mounted volumes

---

### 4️⃣ Storage Lifecycle Operations

- Detached one EBS volume
- Deleted detached volume
- Extended size of remaining volume
- Resized filesystem to reflect new storage

✅ Demonstrated **live storage scaling**

---

### 5️⃣ Backup Strategy Implementation

- Created **EBS Snapshot** of active volume
- Verified successful snapshot creation
- Validated backup recovery capability

---

## 🔐 Security Configuration

- Restricted SSH access
- Allowed HTTP only for web traffic
- Controlled EBS access through instance-level permissions
- Maintained region-level isolation

---

## 📈 Key Learning Outcomes

- Multi-region deployment strategy
- AMI-based infrastructure replication
- EBS volume lifecycle management
- Online volume resizing
- Snapshot-based backup strategy
- Disaster recovery planning
- Secure web server deployment in AWS

---

## 🏆 Real-World Use Case

This architecture is commonly used in:

- Enterprise web applications
- Disaster recovery environments
- High-availability production systems
- Migration & replication strategies
- Cloud infrastructure scaling

---

## 📊 Outcome

Successfully deployed a secured Linux web server in the primary region and replicated it across regions using AMI.

Implemented complete **EBS storage lifecycle management** including creation, deletion, resizing, and backup.

Validated infrastructure replication and backup strategy successfully.

---

## 🛠 Skills Demonstrated

- Amazon EC2 Deployment
- AMI Creation & Cross-Region Copy
- Amazon EBS Management
- Snapshot & Backup Strategy
- Linux Server Administration
- Multi-Region Architecture Design
- Storage Scaling & Troubleshooting
- Cloud Security Best Practices

---

## 📄 Execution Proof

📥 **Download Full Execution Proof:**  
[View Assignment PDF](https://drive.google.com/file/d/16nSjm5kKh73-ZDqKi19UnOy7w8eVb33N/view?usp=drive_link)

---

## 📚 Course Reference

Assignment completed as part of:

**AWS Solutions Architect – DevOps Architect Master’s Program (Intellipaat)**

Certification available in main portfolio repository.
