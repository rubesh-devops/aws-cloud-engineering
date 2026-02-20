# 🚀 Scalable Load-Balanced Auto Scaling Architecture with Domain Routing

## 📌 Project Overview

A highly available and dynamically scalable web architecture was implemented using Amazon EC2 Auto Scaling, Elastic Load Balancing, and Amazon Route 53.

The objective was to design an automated scaling strategy that provisions compute resources when CPU utilization exceeds 80% and scales down when utilization drops below 60%, while distributing traffic through a load balancer and routing user access via a custom domain.

This implementation demonstrates end-to-end high availability, elasticity, and DNS-based traffic routing within AWS.

---

## 🎯 Business Requirement

XYZ Corporation required:

- Automatic scaling based on CPU utilization  
- Cost optimization through dynamic resource management  
- Even traffic distribution across compute resources  
- Domain-based access to application  

---

## 🏗 Architecture Implemented

- EC2 Instances with Apache Web Server  
- Custom AMI for consistent scaling  
- Auto Scaling Group (ASG)  
- Target Tracking / Scaling Policies  
  - Scale out when CPU > 80%  
  - Scale in when CPU < 60%  
- Application Load Balancer (ALB)  
- Target Group Integration  
- Route 53 Hosted Zone and A Record  

---

## ⚙️ Implementation Summary

### 1️⃣ Auto Scaling Configuration

- Created custom AMI with Apache installed  
- Configured Launch Template / Launch Configuration  
- Deployed Auto Scaling Group  
- Defined scaling policies:
  - Scale-out threshold: CPU > 80%  
  - Scale-in threshold: CPU < 60%  
- Configured minimum and maximum instance limits  

Validated dynamic instance provisioning behavior.

---

### 2️⃣ Load Balancer Setup

- Created Application Load Balancer  
- Configured HTTP listener  
- Associated Target Group  
- Attached Auto Scaling Group to Target Group  
- Verified even traffic distribution  

Ensured high availability and fault tolerance.

---

### 3️⃣ Route 53 Domain Routing

- Configured hosted zone  
- Created Alias A Record pointing to ALB  
- Validated DNS propagation  
- Confirmed domain-based application access  

Eliminated dependency on public IP addresses.

---

## 🔐 Security Configuration

- Configured security groups for ALB and EC2  
- Restricted backend access only via load balancer  
- Applied least privilege access model  
- Secured SSH access appropriately  
- Enabled monitoring visibility via CloudWatch  

---

## 📊 Outcome Achieved

- Implemented automated scaling based on CPU metrics  
- Reduced manual infrastructure intervention  
- Improved application availability  
- Distributed traffic evenly across instances  
- Enabled domain-based access model  
- Established production-ready scalable architecture  

---

## 🛠 Skills Demonstrated

- EC2 Auto Scaling Configuration  
- Scaling Policy Design (Threshold-Based)  
- Application Load Balancer Setup  
- Target Group Integration  
- Route 53 DNS Routing  
- High Availability Architecture  
- Cost Optimization Through Elastic Scaling  

---

## 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(https://drive.google.com/file/d/1NJXLeRcc6sZEvxk5mRT2dy5QzVFZDoZh/view?usp=drive_link)*  

---

## 🎓 Course Reference

Program: AWS Solutions Architect Track  
Track: Cloud Engineering & Architecture Implementation
