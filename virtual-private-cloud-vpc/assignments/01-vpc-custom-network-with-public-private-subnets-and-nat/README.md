# 🌐 Custom VPC Architecture with Public & Private Subnets and NAT Gateway

## 📌 Project Overview

Designed and implemented a secure and production-ready AWS Virtual Private Cloud (VPC) architecture to provide isolated, scalable, and controlled networking for enterprise workloads.

The architecture includes public and private subnet segmentation along with a NAT Gateway to enable controlled internet access for private resources.

---

## 🎯 Problem Statement

An organization required a secure and flexible cloud networking environment capable of handling different connectivity needs while maintaining strict network isolation.

---

## 🏗 Architecture Implemented

• Custom VPC with CIDR block: 120.0.0.0/16  
• 1 Public Subnet  
• 2 Private Subnets  
• Internet Gateway attached to VPC  
• NAT Gateway deployed in Public Subnet  
• Route Tables configured for proper traffic flow  

---

## ⚙️ Implementation Summary

### 1️⃣ VPC Creation
• Created a custom VPC with CIDR 120.0.0.0/16  
• Enabled DNS hostnames and DNS support  

### 2️⃣ Subnet Design
• Created 1 Public Subnet for internet-facing resources  
• Created 2 Private Subnets for internal workloads  
• Associated appropriate route tables  

### 3️⃣ Internet Connectivity
• Attached Internet Gateway to VPC  
• Configured Public Route Table with route to Internet Gateway  

### 4️⃣ NAT Gateway Deployment
• Created NAT Gateway in Public Subnet  
• Allocated Elastic IP  
• Updated Private Subnet route table to route internet-bound traffic via NAT Gateway  

---

## 🔐 Security & Networking Strategy

• Isolated internal workloads in private subnets  
• Allowed outbound internet access through NAT Gateway  
• Prevented direct inbound internet access to private instances  
• Implemented structured route table associations  

---

## 📈 Key Learning Outcomes

• Designing enterprise-grade VPC architecture  
• Public vs Private subnet segregation  
• Implementing NAT-based secure internet access  
• Route table configuration and traffic management  
• Network isolation best practices  

---

## 🛠 Skills Demonstrated

• AWS VPC Design  
• Subnet Architecture Planning  
• Internet Gateway Configuration  
• NAT Gateway Deployment  
• Route Table Management  
• Secure Network Segmentation  

---

## 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: (Execution screenshots link will be updated)

---

## 📚 Course Reference

Module: Virtual Private Cloud (VPC)  
Course: DevOps Course  
Program: DevOps Architect Master’s Program – Intellipaat
