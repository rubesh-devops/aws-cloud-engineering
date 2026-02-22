# 🚀 VM Export to AWS and Custom AMI EC2 Migration Implementation

## 📌 Project Overview

A full infrastructure migration workflow was implemented by exporting an on-premise Ubuntu virtual machine and importing it into AWS as a custom Amazon Machine Image (AMI).

The objective was to transition a locally hosted VM into AWS Cloud, store the exported image in Amazon S3, convert it into a usable AMI, and launch an EC2 instance from the migrated image.

This implementation demonstrates real-world lift-and-shift migration strategy and custom AMI provisioning.

---

## 🎯 Business Requirement

XYZ Corporation required:

- Migration of on-premise Ubuntu server to AWS  
- Improved performance and availability  
- Reusable custom AMI for scalable deployments  
- Seamless transition from local to cloud infrastructure  

---

## 🏗 Architecture Implemented

- Exported Ubuntu VM (OVA/OVF format)  
- Amazon S3 for image storage  
- VM Import/Export Service  
- Custom AMI Creation  
- Amazon EC2 Instance Launch  

---

## ⚙️ Implementation Summary

### 1️⃣ VM Export from VirtualBox

- Shut down Ubuntu VM  
- Exported VM in OVA format  
- Verified image integrity  
- Prepared image for cloud upload  

---

### 2️⃣ S3 Upload and Import Process

- Created S3 bucket for migration assets  
- Uploaded exported VM image  
- Configured IAM role for VM import  
- Initiated VM import task  
- Converted uploaded image into custom AMI  

---

### 3️⃣ EC2 Instance Creation

- Launched EC2 instance using custom AMI  
- Configured security groups  
- Verified SSH access  
- Validated system functionality  

---

## 🔐 Security Configuration

- Configured IAM roles for VM Import  
- Restricted S3 bucket access  
- Secured EC2 instance with appropriate security groups  
- Controlled SSH access  

---

## 📊 Outcome Achieved

- Successfully migrated on-premise VM to AWS  
- Created reusable custom AMI  
- Launched EC2 instance from imported image  
- Validated lift-and-shift migration strategy  
- Established scalable cloud-ready architecture  

---

## 🛠 Skills Demonstrated

- VM Export and Image Management  
- Amazon S3 Storage Configuration  
- AWS VM Import/Export  
- Custom AMI Creation  
- EC2 Deployment from Custom Images  
- Cloud Migration Execution  
- Lift-and-Shift Strategy Implementation  

---

## 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(Documentation link will be updated)*  

---

## 🎓 Course Reference

Program: AWS Solutions Architect Track  
Track: Cloud Migration & Infrastructure Modernization
