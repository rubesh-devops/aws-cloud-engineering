# 💾 Amazon EBS Volume Deployment, Attachment & Storage Expansion Validation

## 📌 Project Overview

As part of AWS storage implementation, a scalable block storage solution was provisioned using Amazon Elastic Block Store (EBS) and attached to a Linux EC2 instance.

The objective was to demonstrate persistent storage attachment, dynamic volume resizing, and in-instance storage validation without downtime.

This implementation showcases enterprise-level storage management and elasticity capabilities within AWS.

---

## 🎯 Business Requirement

XYZ Corporation required:

- Deployment of a Linux EC2 instance
- Persistent block storage attachment
- 20 GB EBS volume configuration
- Storage resizing capability
- Validation of volume expansion at OS level

---

## 🏗 Architecture Implemented

- Amazon EC2 (Linux)
- Amazon EBS (20 GB General Purpose Volume)
- Volume attachment via same Availability Zone
- In-instance filesystem extension
- Secure SSH-based administration

---

## ⚙️ Implementation Summary

### 1️⃣ EC2 Instance Deployment

- Launched a Linux EC2 instance
- Configured SSH access
- Verified instance operational status

---

### 2️⃣ EBS Volume Creation & Attachment

- Created a 20 GB EBS volume
- Ensured same Availability Zone as EC2 instance
- Attached volume to running EC2 instance
- Verified block device mapping
- Formatted and mounted the volume inside the instance

---

### 3️⃣ Volume Resize & Storage Validation

- Modified EBS volume size (expanded storage capacity)
- Extended filesystem within Linux OS
- Verified increased disk capacity using OS-level disk inspection
- Confirmed no data loss during expansion

---

## 🔐 Security Configuration

- Volume attached only within same AZ
- Access controlled via EC2 security group
- SSH key-based authentication enforced
- No public storage exposure
- IAM-controlled administrative permissions

---

## 📊 Outcome Achieved

- Successfully provisioned Linux EC2 instance
- Attached 20 GB EBS volume
- Expanded volume size dynamically
- Validated filesystem extension
- Demonstrated scalable persistent storage implementation

---

## 🛠 Skills Demonstrated

- Amazon EBS Provisioning
- Block Storage Management
- Volume Attachment & Mounting
- Linux Filesystem Expansion
- EC2 & Storage Integration
- Cloud Storage Scalability Implementation

---

## 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(Documentation link will be updated)*

---

## 🎓 Course Reference

Module: Introduction to EC2, EBS, EFS and Amazon FSx  
Program: AWS Solutions Architect Course  
Track: DevOps Architect Master’s Program – Intellipaat
