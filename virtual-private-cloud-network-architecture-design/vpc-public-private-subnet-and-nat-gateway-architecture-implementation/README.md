# 🌐 VPC Public-Private Subnet and NAT Gateway Architecture Implementation

## 📌 Project Overview

A secure and segmented Virtual Private Cloud (VPC) architecture was designed and implemented to provide controlled networking boundaries for application deployment.

The objective was to create a VPC with defined public and private subnets, ensuring secure internet access for public resources and controlled outbound connectivity for private resources through a NAT Gateway.

This implementation demonstrates network segmentation, secure connectivity design, and foundational cloud networking architecture in AWS.

---

## 🎯 Business Requirement

The organization required:

- A secure and isolated cloud networking environment  
- Separation of public-facing and private resources  
- Controlled outbound internet access for private subnets  
- Scalable network architecture for future expansion  

---

## 🏗 Architecture Implemented

- Custom Amazon VPC (CIDR: 120.0.0.0/16)  
- 1 Public Subnet  
- 2 Private Subnets  
- Internet Gateway (IGW)  
- NAT Gateway  
- Route Tables (Public & Private)  
- Subnet Associations  

---

## ⚙️ Implementation Summary

### 1️⃣ VPC Creation

- Created a custom VPC with CIDR block `120.0.0.0/16`  
- Enabled DNS resolution and DNS hostnames  
- Verified VPC configuration  

---

### 2️⃣ Subnet Design and Segmentation

- Created one Public Subnet  
- Created two Private Subnets  
- Distributed subnets appropriately within availability zones  

Public subnet intended for internet-facing resources.  
Private subnets reserved for backend or secure workloads.

---

### 3️⃣ Internet Gateway Configuration

- Created and attached Internet Gateway to the VPC  
- Configured Public Route Table  
- Added route to `0.0.0.0/0` via Internet Gateway  
- Associated Public Subnet with Public Route Table  

---

### 4️⃣ NAT Gateway Deployment

- Allocated Elastic IP  
- Created NAT Gateway in Public Subnet  
- Configured Private Route Table  
- Added route to `0.0.0.0/0` via NAT Gateway  
- Associated Private Subnets with Private Route Table  

Validated outbound internet connectivity from private subnet while maintaining inbound isolation.

---

## 🔐 Security Configuration

- Segregated public and private network layers  
- Restricted direct internet access to private subnets  
- Implemented controlled outbound traffic via NAT Gateway  
- Maintained principle of least exposure  
- Designed scalable network segmentation model  

---

## 📊 Outcome Achieved

- Successfully implemented secure VPC architecture  
- Established public and private subnet segregation  
- Enabled controlled outbound connectivity for private resources  
- Improved network security posture  
- Built foundation for multi-tier application architecture  

---

## 🛠 Skills Demonstrated

- Amazon VPC Design and Configuration  
- CIDR Block Planning  
- Public and Private Subnet Segmentation  
- Internet Gateway and NAT Gateway Configuration  
- Route Table Management  
- Secure Network Architecture Design  
- AWS Networking Best Practices  

---

## 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(Documentation link will be updated)*  

---

## 🎓 Course Reference

Program: AWS Solutions Architect Track  
Track: Cloud Engineering & Architecture Implementation
