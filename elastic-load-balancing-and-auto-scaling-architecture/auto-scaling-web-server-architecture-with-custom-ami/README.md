# 📈 Auto Scaling Web Server Architecture with Custom AMI

## 📌 Project Overview

A dynamic scaling architecture was implemented using Amazon EC2 Auto Scaling to automatically adjust compute capacity based on workload demand.

The solution involved creating a reusable custom Amazon Machine Image (AMI) with Apache web server pre-installed, configuring a launch configuration, and deploying an Auto Scaling Group (ASG) with defined scaling boundaries.

This implementation demonstrates elastic infrastructure provisioning and cost-efficient compute management in AWS.

---

## 🎯 Business Requirement

XYZ Corporation required:

- Dynamic scaling of web servers based on traffic demand  
- Reduction in manual infrastructure provisioning  
- Cost optimization through automated scaling  
- High availability for web-based application  

---

## 🏗 Architecture Implemented

- EC2 instance with Apache web server  
- Custom Amazon Machine Image (AMI)  
- Launch Configuration  
- Auto Scaling Group (ASG)  
- Minimum capacity: 1 instance  
- Maximum capacity: 3 instances  

---

## ⚙️ Implementation Summary

### 1️⃣ Custom Web Server AMI Creation

- Launched EC2 instance  
- Installed Apache2 web server  
- Configured sample web page  
- Verified HTTP access  
- Created custom AMI from configured instance  

This ensured consistent environment replication.

---

### 2️⃣ Launch Configuration Setup

- Created Launch Configuration using custom AMI  
- Selected instance type  
- Attached appropriate security group  
- Configured key pair and storage settings  

Launch Configuration acts as the blueprint for scaling instances.

---

### 3️⃣ Auto Scaling Group Deployment

- Created Auto Scaling Group using Launch Configuration  
- Set Minimum capacity to 1  
- Set Maximum capacity to 3  
- Configured desired capacity  
- Associated with appropriate VPC subnet  

Validated instance scaling behavior and replication capability.

---

## 🔐 Security Configuration

- Configured security group to allow HTTP access (port 80)  
- Restricted SSH access appropriately  
- Ensured instances are deployed within controlled VPC environment  
- Followed least privilege principle  

---

## 📊 Outcome Achieved

- Implemented elastic compute infrastructure  
- Enabled automated scaling between 1–3 instances  
- Reduced manual provisioning effort  
- Improved application availability  
- Established scalable cloud architecture foundation  

---

## 🛠 Skills Demonstrated

- Amazon EC2 Configuration  
- Custom AMI Creation  
- Launch Configuration Setup  
- Auto Scaling Group Deployment  
- Elastic Infrastructure Design  
- High Availability Strategy  
- AWS Compute Optimization  

---

## 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(Documentation link will be updated)*  

---

## 🎓 Course Reference

Program: AWS Solutions Architect Track  
Track: Cloud Engineering & Architecture Implementation
