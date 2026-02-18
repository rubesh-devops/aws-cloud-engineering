# 💾 Amazon EBS Volume Attachment & Resize Implementation

---

## 📌 Project Context

XYZ Corporation required persistent and scalable storage for their web-based application hosted on AWS EC2 instances.

To support application data growth and ensure storage flexibility, Amazon Elastic Block Store (EBS) was implemented and configured dynamically.

---

## 🏗 Architecture Overview

- Cloud Provider: Amazon Web Services (AWS)
- Compute Service: Amazon EC2 (Linux)
- Storage Service: Amazon Elastic Block Store (EBS)
- Initial Volume Size: 20 GB
- Volume Type: General Purpose SSD
- Attachment Type: Block Storage

---

## 🎯 Implementation Objectives

### ✅ 1. Launch Linux EC2 Instance
- Deployed Linux-based EC2 instance
- Configured necessary Security Groups
- Verified instance connectivity

### ✅ 2. Create & Attach EBS Volume
- Created a new 20 GB EBS volume
- Ensured volume was created in same Availability Zone
- Attached volume to the EC2 instance
- Mounted volume to the Linux file system

### ✅ 3. Resize EBS Volume
- Increased storage capacity of the existing EBS volume
- Rescanned block device on Linux
- Extended file system to reflect new storage size
- Verified updated disk size inside EC2 instance

---

## 🔐 Storage & Security Considerations

- Volume attached only within same Availability Zone
- Controlled access via EC2 security policies
- Used persistent block storage separate from root disk
- Ensured safe resizing without data loss

---

## 📈 Skills Demonstrated

- Amazon EC2 provisioning
- Amazon EBS volume creation
- Block storage attachment in AWS
- Linux disk mounting & file system expansion
- Live volume resizing in production
- Storage scalability implementation

---

## 🧠 Real-World Application

This implementation mirrors real production scenarios where:

- Applications require additional storage after deployment
- Storage must scale without downtime
- Data persistence is separated from compute lifecycle
- Cloud infrastructure adapts dynamically to business growth

---

## 📸 Validation & Evidence

Execution Documentation (Screenshots & Proof):
Google Drive: (Documentation link will be updated)

---

## 📚 Course Reference

Module: Introduction to EC2, EBS, EFS & FSx  
Course: DevOps Course  
Program: DevOps Architect Master’s Program – Intellipaat

---

Successfully implemented scalable block storage architecture using Amazon EBS.
