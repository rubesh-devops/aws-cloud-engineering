# 🔐 Private S3 Access using VPC Endpoints

## 📌 Project Overview

Designed and implemented a secure, private connectivity model between an Amazon VPC and Amazon S3 using VPC Endpoints.

This architecture eliminates the need for Internet Gateway or NAT Gateway for accessing S3 resources, ensuring secure and controlled internal communication within the AWS network.

---

## 🎯 Problem Statement

Create a VPC Endpoint for an S3 bucket to enable secure, private access to files without exposing traffic to the public internet.

---

## 🏗 Architecture Implemented

• Amazon VPC  
• Private Subnet  
• EC2 Instance inside VPC  
• Amazon S3 Bucket  
• Gateway VPC Endpoint for S3  
• Route Table Configuration  

---

## ⚙️ Implementation Summary

### 1️⃣ VPC and Subnet Preparation
• Used an existing VPC with private subnet  
• Ensured no direct internet access was required  

### 2️⃣ S3 Bucket Configuration
• Created or used an existing S3 bucket  
• Uploaded sample files for validation  

### 3️⃣ VPC Endpoint Creation
• Created a Gateway type VPC Endpoint  
• Selected Amazon S3 service  
• Associated endpoint with the appropriate route table  

### 4️⃣ Route Table Integration
• Verified route entry automatically added for S3 prefix list  
• Confirmed traffic routing internally via AWS backbone  

### 5️⃣ Access Validation
• Accessed S3 bucket from EC2 instance inside private subnet  
• Verified no public internet routing was used  

---

## 🔐 Security Architecture Strategy

• Eliminated public internet dependency  
• Restricted S3 access within VPC boundary  
• Reduced attack surface  
• Followed secure private connectivity best practices  

---

## 📈 Key Learning Outcomes

• Understanding Gateway VPC Endpoints  
• Private service-to-service communication in AWS  
• Route table integration with VPC endpoints  
• Secure S3 access architecture design  

---

## 🛠 Skills Demonstrated

• Amazon VPC Configuration  
• VPC Endpoint Deployment  
• S3 Secure Access Design  
• Private Networking Architecture  
• Cloud Security Implementation  

---

## 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: (Execution screenshots link will be updated)

---

## 📚 Course Reference

Module: Virtual Private Cloud (VPC)  
Course: DevOps Course  
Program: DevOps Architect Master’s Program – Intellipaat
