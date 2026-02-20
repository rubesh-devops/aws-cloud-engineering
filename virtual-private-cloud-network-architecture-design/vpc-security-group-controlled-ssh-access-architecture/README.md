# 🔐 VPC Security Group Controlled SSH Access Architecture

## 📌 Project Overview

A secure access control architecture was implemented within a Virtual Private Cloud (VPC) to restrict SSH connectivity between EC2 instances.

The objective was to deploy two EC2 instances — **Master** and **Client** — and configure security groups so that the Client instance can only be accessed via SSH through the Master instance.

This implementation demonstrates secure instance-to-instance communication and layered access control using AWS Security Groups.

---

## 🎯 Business Requirement

The organization required:

- Deployment of two EC2 instances within a VPC  
- Controlled SSH access between instances  
- Restriction of direct public SSH access to internal resources  
- Improved network-level security posture  

---

## 🏗 Architecture Implemented

- Two EC2 Instances:
  - Master (Bastion-style access)
  - Client (Restricted backend access)
- Public Subnet Deployment  
- Separate Security Groups:
  - Master-SG
  - Client-SG  
- SSH Access Restriction via Security Group Rules  

---

## ⚙️ Implementation Summary

### 1️⃣ EC2 Instance Deployment

- Launched two EC2 instances in a public subnet  
- Named instances:
  - Master  
  - Client  
- Assigned appropriate key pair for SSH access  

---

### 2️⃣ Security Group Configuration

#### Master Security Group

- Allowed inbound SSH (Port 22) from trusted IP range  
- Allowed outbound traffic to Client instance  

#### Client Security Group

- Removed public SSH access (no 0.0.0.0/0 rule)  
- Allowed inbound SSH (Port 22) only from Master Security Group  
- Denied direct external SSH access  

---

### 3️⃣ Access Validation

- Successfully connected to Master instance via SSH  
- From Master, SSH access to Client was validated  
- Direct SSH access to Client from external network was blocked  

---

## 🔐 Security Configuration

- Implemented bastion-style architecture  
- Eliminated direct public exposure of backend instance  
- Applied security group referencing (SG-to-SG rule)  
- Enforced least privilege networking model  
- Maintained controlled internal communication  

---

## 📊 Outcome Achieved

- Successfully restricted SSH access to Client instance  
- Eliminated direct public exposure  
- Improved network isolation  
- Implemented layered security approach  
- Established secure administrative access pattern  

---

## 🛠 Skills Demonstrated

- AWS Security Group Configuration  
- EC2 Instance Deployment  
- Bastion Host Architecture  
- SSH Access Control  
- VPC Network Security Design  
- Secure Infrastructure Best Practices  

---

## 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(Documentation link will be updated)*  

---

## 🎓 Course Reference

Program: AWS Solutions Architect Track  
Track: Cloud Engineering & Architecture Implementation
