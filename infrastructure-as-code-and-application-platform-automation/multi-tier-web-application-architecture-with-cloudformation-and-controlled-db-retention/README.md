# 🏗 Multi-Tier Web Application Architecture with CloudFormation and Controlled DB Retention

## 📌 Project Overview

A production-grade multi-tier web application architecture was designed and deployed to support a secure and scalable testing environment for development teams.

The objective was to implement a three-tier architecture consisting of Web, Application, and Database layers with strict network isolation, controlled access policies, DNS routing, and automated provisioning using Infrastructure-as-Code principles.

Additionally, a governance mechanism was implemented to ensure that database resources are retained even if the application stack is deleted.

This implementation demonstrates enterprise architecture design, secure network segmentation, automation strategy, and controlled resource lifecycle management.

---

## 🎯 Business Requirement

XYZ Corporation required:

- Secure three-tier web architecture  
- Public-facing web layer  
- Private application and database layers  
- Controlled inter-tier communication  
- Domain-based traffic routing  
- Self-service infrastructure for development team  
- Database protection during stack deletion  

---

## 🏗 Architecture Implemented

- Amazon VPC  
- Public Subnet (Web Tier)  
- Private Subnet (Application Tier)  
- Private Subnet (Database Tier)  
- EC2 Instances (Web & Application)  
- Amazon RDS MySQL (DB Tier)  
- Security Groups for Tier Isolation  
- Route 53 Hosted Zone  
- CloudFormation Stack Automation  
- Deletion Policy for RDS Retention  

---

## ⚙️ Implementation Summary

### 1️⃣ Web Tier Deployment

- Launched EC2 instance in public subnet  
- Allowed inbound:
  - HTTP (Port 80) from internet  
  - SSH (Port 22) from internet  
- Associated public IP  
- Installed web server  

---

### 2️⃣ Application Tier Deployment

- Launched EC2 instance in private subnet  
- Restricted inbound SSH access only from Web Tier security group  
- Prevented direct internet access  
- Configured internal application communication  

---

### 3️⃣ Database Tier Deployment

- Created Amazon RDS MySQL instance in private subnet  
- Configured DB Subnet Group  
- Allowed inbound Port 3306 only from Application Tier security group  
- Disabled public accessibility  
- Enabled automated backups  

---

### 4️⃣ DNS Configuration

- Created Route 53 Hosted Zone  
- Created A/Alias record  
- Mapped domain to Web Tier EC2 instance  
- Validated domain resolution  

---

### 5️⃣ Automation and Governance Solution

- Implemented CloudFormation template for full architecture  
- Enabled self-service stack deployment for development team  
- Applied **DeletionPolicy: Retain** for RDS instance  
- Ensured database persists even after stack deletion  
- Reduced dependency on system administrators  

---

## 🔐 Security Configuration

- Strict tier-based security group isolation  
- No direct internet access to Application or DB tier  
- Database accessible only from Application tier  
- Private subnet isolation  
- RDS retention protection  

---

## 📊 Outcome Achieved

- Designed secure multi-tier application architecture  
- Enabled self-service infrastructure deployment  
- Implemented DNS-based routing  
- Ensured database protection from accidental deletion  
- Built production-grade scalable web architecture  

---

## 🛠 Skills Demonstrated

- Multi-Tier Architecture Design  
- VPC Network Segmentation  
- Security Group Isolation Strategy  
- Amazon RDS Secure Deployment  
- Route 53 DNS Configuration  
- CloudFormation Infrastructure Automation  
- Resource Lifecycle Governance  
- Production Architecture Best Practices  

---

## 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(https://drive.google.com/file/d/1-F6uNehOLDD18LJS3PfyPucLy2PRlQy_/view?usp=drive_link)*  

---

## 🎓 Course Reference

Program: AWS Solutions Architect Track  
Track: Cloud Engineering & Architecture Implementation
