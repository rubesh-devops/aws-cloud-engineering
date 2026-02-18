# 🔐 Secure EC2 Access Control using VPC Security Groups

## 📌 Project Overview

Designed and implemented a controlled access architecture using AWS Security Groups to enforce strict SSH connectivity rules between EC2 instances.

This setup ensures that the Client instance is accessible only through the Master instance, following the principle of least privilege and secure bastion-based access.

---

## 🎯 Problem Statement

Deploy EC2 instances within a public subnet and configure security groups so that:

• The Master instance is accessible via SSH  
• The Client instance can only be accessed via SSH from the Master instance  
• Direct SSH access to the Client instance from the internet is blocked  

---

## 🏗 Architecture Implemented

• VPC with Public Subnet  
• EC2 Instance: Master (Bastion Host)  
• EC2 Instance: Client  
• Security Group: Master-SG  
• Security Group: Client-SG  

---

## ⚙️ Implementation Summary

### 1️⃣ EC2 Deployment
• Launched two EC2 instances in a public subnet  
• Named instances as Master and Client  

### 2️⃣ Security Group Configuration

**Master Security Group**
• Allowed SSH (Port 22) from trusted IP range  

**Client Security Group**
• Allowed SSH (Port 22) only from Master Security Group  
• No public SSH access allowed  

### 3️⃣ Access Validation
• Verified SSH access to Master from local machine  
• Confirmed SSH access to Client only via Master instance  
• Ensured direct internet SSH to Client was blocked  

---

## 🔐 Security Architecture Strategy

• Implemented Bastion Host pattern  
• Enforced least privilege access  
• Restricted direct internet exposure  
• Used Security Group referencing instead of open CIDR rules  

---

## 📈 Key Learning Outcomes

• Security Group rule engineering  
• Bastion-based secure access model  
• Controlled instance-to-instance communication  
• Network-level access hardening  

---

## 🛠 Skills Demonstrated

• AWS EC2 Deployment  
• VPC Security Groups Configuration  
• Bastion Host Architecture  
• Secure SSH Access Control  
• Principle of Least Privilege Implementation  

---

## 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: (Execution screenshots link will be updated)

---

## 📚 Course Reference

Module: Virtual Private Cloud (VPC)  
Course: DevOps Course  
Program: DevOps Architect Master’s Program – Intellipaat

