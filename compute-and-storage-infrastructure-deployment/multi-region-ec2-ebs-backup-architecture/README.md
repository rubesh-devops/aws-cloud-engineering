# 🖥 Multi-Region Web Server Deployment with EBS Lifecycle Management & Backup Strategy

## 📌 Project Overview

As part of enterprise infrastructure expansion, a secure Linux-based web server architecture was deployed using Amazon EC2, EBS, and AMI replication strategies.

The objective was to:

- Deploy secured Linux web servers
- Create reusable machine images (AMI)
- Replicate infrastructure across regions
- Implement EBS storage lifecycle management
- Configure backup strategy for data durability

This implementation demonstrates production-ready infrastructure provisioning, cross-region replication, and storage optimization in AWS.

---

## 🎯 Business Requirement

XYZ Corporation required:

- Secure Linux-based web servers
- High availability through regional replication
- Storage scalability and lifecycle control
- Data backup strategy for disaster recovery
- Optimized and manageable block storage

---

## 🏗 Architecture Implemented

- Amazon EC2 Linux Instance (US-East-1)
- Custom Amazon Machine Image (AMI)
- Cross-Region AMI Replication (US-West-2)
- Amazon EBS Volumes
- EBS Volume Resize & Snapshot Backup
- Security Groups for Controlled Access

---

## ⚙️ Implementation Summary

### 1️⃣ Primary EC2 Web Server Deployment (US-East-1)

- Launched Linux EC2 instance in N. Virginia region
- Installed and configured web server (Apache/Nginx)
- Configured security groups for HTTP and SSH access
- Validated application accessibility

---

### 2️⃣ AMI Creation & Cross-Region Replication

- Created custom AMI from configured EC2 instance
- Copied AMI to US-West-2 (Oregon) region
- Launched new EC2 instance from replicated AMI
- Validated identical web server deployment in second region

---

### 3️⃣ EBS Volume Deployment

- Created two EBS volumes
- Attached both volumes to EC2 instance
- Mounted volumes and verified availability
- Confirmed block storage integration

---

### 4️⃣ EBS Lifecycle Management

- Detached one EBS volume
- Deleted detached volume successfully
- Resized the remaining EBS volume
- Extended file system at OS level
- Verified updated storage capacity

---

### 5️⃣ EBS Backup Strategy

- Created snapshot of resized EBS volume
- Verified snapshot availability
- Confirmed backup retention capability

---

## 🔐 Security Configuration

- Restricted inbound access via security groups
- SSH access limited to authorized IPs
- No unnecessary public exposure
- IAM access policies enforced
- Snapshot-based backup for recovery readiness

---

## 📊 Outcome Achieved

- Successfully deployed secured Linux web server
- Replicated infrastructure across regions
- Implemented EBS volume lifecycle operations
- Extended block storage dynamically
- Established reliable snapshot-based backup mechanism
- Demonstrated multi-region production-ready architecture

---

## 🛠 Skills Demonstrated

- Amazon EC2 Deployment
- AMI Creation & Cross-Region Copy
- Amazon EBS Volume Management
- Volume Resize & File System Extension
- EBS Snapshot Backup Strategy
- Multi-Region Infrastructure Design
- Secure Cloud Architecture Implementation

---

## 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(https://drive.google.com/file/d/16nSjm5kKh73-ZDqKi19UnOy7w8eVb33N/view?usp=drive_link)*

---

## 🎓 Course Reference

Module: Introduction to EC2, EBS, EFS and Amazon FSx  
Program: AWS Solutions Architect Course  
Track: DevOps Architect Master’s Program – Intellipaat
