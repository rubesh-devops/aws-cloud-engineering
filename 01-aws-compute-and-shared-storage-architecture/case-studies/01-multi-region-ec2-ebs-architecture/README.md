# 🌍 Highly Available Multi-Region Web Server Architecture with AMI & EBS Lifecycle Management

---

## 📌 Case Study Overview

Designed and implemented a secure, multi-region Linux web server architecture on AWS using:

- Amazon EC2
- Amazon Machine Images (AMI)
- Amazon EBS volumes
- Cross-region replication
- EBS volume lifecycle management

This solution ensures high availability, scalability, and backup reliability for enterprise web application deployment.

---

## 🏗 Infrastructure Components Used

- Amazon EC2 (Linux)
- Amazon Machine Image (AMI)
- Amazon EBS Volumes
- EBS Snapshots
- Multi-Region Deployment (US-East-1 & US-West-2)
- Security Groups
- VPC

---

## 🎯 Business Objective

To build a secured web server architecture that:

- Can be replicated across regions
- Supports scalable storage
- Enables volume lifecycle management
- Ensures backup & disaster recovery readiness

---

## ⚙️ Implementation Summary

### 1️⃣ Primary Web Server Deployment (US-East-1)

- Launched Linux EC2 instance in US-East-1 (N. Virginia)
- Configured web server stack
- Created custom AMI from configured instance for replication
- Ensured secure access via Security Groups

---

### 2️⃣ Cross-Region Replication (US-West-2)

- Copied AMI to US-West-2 (Oregon)
- Launched replica EC2 instance from copied AMI
- Validated identical environment configuration
- Achieved regional redundancy

---

### 3️⃣ EBS Volume Management

- Created two EBS volumes
- Attached both volumes to primary EC2 instance
- Mounted and validated storage availability

---

### 4️⃣ Volume Lifecycle Operations

- Detached one EBS volume
- Deleted the detached volume safely
- Resized the remaining volume
- Extended filesystem to reflect updated storage capacity

---

### 5️⃣ Backup & Recovery Strategy

- Created EBS snapshot of active volume
- Validated snapshot availability
- Ensured disaster recovery capability

---

## 🔐 Security & Reliability Configuration

- Restricted SSH and HTTP access using Security Groups
- Controlled regional replication using AMI copy
- Ensured safe detachment before volume deletion
- Verified storage extension at OS level
- Implemented snapshot-based backup

---

## 📈 Key Learning Outcomes

- AMI-based environment replication
- Multi-region AWS deployment strategy
- EBS volume attachment and detachment
- Live storage resizing in production systems
- Snapshot-based disaster recovery
- Storage lifecycle management best practices
- High availability cloud architecture design

---

## 🏆 Real-World Use Cases

This architecture is commonly used for:

- Enterprise web server replication
- Disaster recovery setups
- Production staging environments
- Backup-driven storage strategies
- Multi-region business continuity planning

---

## 📊 Outcome

Successfully deployed a production-ready, multi-region web server architecture with:

- AMI-based replication
- Dynamic storage management
- Backup and recovery validation
- Region-level redundancy

Demonstrated enterprise-level infrastructure lifecycle management.

---

## 🛠 Skills Demonstrated

- Amazon EC2 Administration
- AMI Creation & Cross-Region Copy
- Amazon EBS Volume Management
- Storage Scaling & Filesystem Expansion
- Snapshot-Based Backup
- Multi-Region Architecture Design
- Infrastructure High Availability
- Disaster Recovery Planning

---

## 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: (Documentation link will be updated)

---

## 📚 Course Reference

This case study is part of:

**Module 2 – Introduction to EC2, EBS, EFS and Amazon FSx**  
**AWS Solutions Architect Course**  
Part of **DevOps Architect Master’s Program – Intellipaat**
