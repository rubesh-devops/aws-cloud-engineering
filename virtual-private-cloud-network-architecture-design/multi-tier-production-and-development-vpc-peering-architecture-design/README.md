# 🏗 Multi-Tier Production and Development VPC Peering Architecture Design

## 📌 Project Overview

A secure, scalable, and segmented multi-VPC architecture was designed to support separate **Production** and **Development** environments.

The objective was to implement a 4-tier architecture for production, a 2-tier architecture for development, enforce subnet-level internet access controls, and establish secure VPC peering between environments for controlled database communication.

This implementation demonstrates enterprise-grade AWS network architecture, environment isolation, controlled connectivity, and secure inter-VPC communication.

---

## 🎯 Business Requirement

XYZ Corporation required:

- Separate Production and Development VPC environments  
- Multi-tier architecture for production workloads  
- Controlled internet access for specific subnets only  
- Secure database communication between environments  
- Strong network isolation using security groups and NACLs  

---

## 🏗 Architecture Implemented

### 🟢 Production VPC (4-Tier Architecture)

Subnets:
- Public Subnet: `web`
- Private Subnets:
  - `app1`
  - `app2`
  - `dbcache`
  - `db`

Components:
- Internet Gateway
- NAT Gateway
- Route Tables (Public & Private)
- Security Groups
- Network ACLs

---

### 🔵 Development VPC (2-Tier Architecture)

Subnets:
- Public Subnet: `web`
- Private Subnet: `db`

Components:
- Internet Gateway
- NAT Gateway (restricted use)
- Route Tables
- Security Groups
- Network ACLs

---

### 🔗 Inter-VPC Connectivity

- VPC Peering between Production and Development VPCs  
- Route table updates for cross-VPC communication  
- Secure DB-to-DB connectivity configuration  

---

## ⚙️ Implementation Summary

### 1️⃣ Production Network Deployment

- Created Production VPC with appropriate CIDR block  
- Designed 4-tier subnet architecture  
- Launched EC2 instances:
  - web
  - app1
  - app2
  - dbcache
  - db  
- Configured routing:
  - Public subnet via Internet Gateway  
  - Private subnets via NAT Gateway  
- Allowed internet access only for:
  - dbcache instance  
  - app1 subnet  

---

### 2️⃣ Development Network Deployment

- Created Development VPC  
- Designed 2-tier subnet architecture  
- Launched EC2 instances:
  - web
  - db  
- Configured routing:
  - Only web subnet allowed outbound internet access  
  - db subnet restricted from direct internet connectivity  

---

### 3️⃣ Security Management

- Configured security groups per tier  
- Restricted database access to specific subnets  
- Applied Network ACL rules for additional subnet-level control  
- Implemented least privilege communication rules  

---

### 4️⃣ VPC Peering Configuration

- Created VPC peering connection between Production and Development VPCs  
- Updated route tables on both sides  
- Ensured non-overlapping CIDR ranges  
- Configured DB subnet communication between environments  
- Validated cross-VPC connectivity  

---

## 🔐 Security Configuration

- Environment isolation between Production and Development  
- Controlled internet exposure per subnet  
- Secure DB-to-DB communication  
- SG-based and NACL-based layered security  
- Eliminated unnecessary public exposure  

---

## 📊 Outcome Achieved

- Successfully deployed 4-tier production architecture  
- Successfully deployed 2-tier development architecture  
- Implemented controlled internet access per subnet  
- Established secure cross-VPC peering  
- Designed enterprise-ready multi-environment cloud architecture  

---

## 🛠 Skills Demonstrated

- Multi-Tier VPC Architecture Design  
- Subnet Segmentation Strategy  
- Internet Gateway & NAT Gateway Configuration  
- Security Group and NACL Management  
- Cross-VPC Peering Setup  
- Secure Inter-Environment Connectivity  
- Enterprise Network Design Principles  

---

## 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(Documentation link will be updated)*  

---

## 🎓 Course Reference

Program: AWS Solutions Architect Track  
Track: Cloud Engineering & Architecture Implementation
