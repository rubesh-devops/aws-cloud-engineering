# 🚀 Web AMI Creation & Auto Scaling Infrastructure Deployment

---

## 📌 Project Overview

Designed and implemented a **scalable web infrastructure architecture on AWS** using:

- Custom Amazon Machine Image (AMI)
- Launch Configuration
- Auto Scaling Group

This solution enables dynamic scaling of EC2 instances based on demand, eliminating manual server provisioning and improving cost efficiency.

---

## 🏗 Architecture Components Implemented

- Amazon EC2
- Custom Web Server AMI (Apache2 Installed)
- Launch Configuration
- Auto Scaling Group
- Dynamic Scaling Configuration

---

## 🎯 Business Objective

XYZ Corporation required:

- Automated web server provisioning
- Ability to scale infrastructure based on load
- Reduced dependency on on-premise hardware
- High availability with minimal manual intervention

---

## ⚙️ Implementation Summary

### 🔹 Step 1: Custom Web Server AMI Creation

- Launched EC2 instance
- Installed Apache2 Web Server
- Configured web server environment
- Created a custom AMI from the configured instance

Outcome:
Reusable golden image for automated infrastructure deployment.

---

### 🔹 Step 2: Launch Configuration Setup

- Created Launch Configuration using the custom AMI
- Defined:
  - Instance type
  - Security group
  - Key pair
  - Storage configuration

Outcome:
Standardized deployment template for scaling.

---

### 🔹 Step 3: Auto Scaling Group Configuration

- Created Auto Scaling Group using Launch Configuration
- Configured:
  - Minimum Instances: 1
  - Maximum Instances: 3
  - Desired Capacity: 1
- Enabled automatic scaling behavior

Outcome:
Infrastructure dynamically scales based on demand.

---

## 📊 Final Architecture Behavior

- Minimum of 1 web server always running
- Automatically scales up to 3 instances during high traffic
- Reduces to minimum capacity when demand decreases
- Eliminates manual server provisioning

---

## 🔐 Infrastructure Benefits Achieved

- High Availability
- Elastic Scalability
- Cost Optimization
- Infrastructure Automation
- Reduced Operational Overhead

---

## 📈 Skills Demonstrated

- EC2 Image Management
- Amazon AMI Creation
- Launch Configuration Design
- Auto Scaling Architecture
- AWS High Availability Patterns
- Infrastructure Automation

---

## 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: (Documentation link will be updated)

---

## 🎓 Course Reference

Module 4 – Elastic Load Balancing & Auto Scaling  
DevOps Course  
Part of DevOps Architect Master’s Program – Intellipaat

---

## 🏆 Execution Status

✔ Successfully Implemented  
✔ Scalable Web Infrastructure Deployed  
✔ Production-Ready Architecture Model
