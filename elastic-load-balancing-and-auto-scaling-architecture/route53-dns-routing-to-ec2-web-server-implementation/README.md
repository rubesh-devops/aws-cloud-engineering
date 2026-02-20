# 🌐 Route 53 DNS Routing to EC2 Web Server Implementation

## 📌 Project Overview

A DNS-based traffic routing solution was implemented using Amazon Route 53 to direct internet traffic to an Apache web server hosted on an EC2 instance.

The objective was to configure domain-based access instead of relying on raw public IP addresses, enabling a scalable and professional web access model.

This implementation demonstrates DNS configuration, hosted zone management, and public web traffic routing within AWS.

---

## 🎯 Business Requirement

XYZ Corporation required:

- Domain-based access to web applications  
- Replacement of direct IP-based access  
- Scalable DNS routing solution  
- Improved application accessibility  

---

## 🏗 Architecture Implemented

- Amazon Route 53 Hosted Zone  
- Public DNS Record Configuration  
- EC2 Instance running Apache Web Server  
- A Record mapping to EC2 Public IP  

---

## ⚙️ Implementation Summary

### 1️⃣ Hosted Zone Utilization

- Used existing Route 53 Hosted Zone  
- Verified domain ownership and DNS configuration  

---

### 2️⃣ EC2 Web Server Deployment

- Launched EC2 instance  
- Installed Apache web server  
- Configured sample web page  
- Verified access via public IP  

---

### 3️⃣ DNS Record Configuration

- Created an A Record inside hosted zone  
- Mapped domain name to EC2 public IP address  
- Configured TTL and routing policy  
- Validated DNS propagation  

---

### 4️⃣ Traffic Routing Validation

- Accessed application using domain name  
- Confirmed successful routing to Apache web server  
- Verified removal of direct IP dependency  

---

## 🔐 Security Configuration

- Restricted inbound traffic to HTTP (port 80)  
- Controlled SSH access  
- Configured proper security group rules  
- Ensured DNS configuration aligned with secure web access practices  

---

## 📊 Outcome Achieved

- Successfully implemented DNS-based routing  
- Enabled user-friendly domain access  
- Improved infrastructure scalability  
- Established foundation for future load balancing integration  
- Eliminated direct IP exposure dependency  

---

## 🛠 Skills Demonstrated

- Amazon Route 53 Configuration  
- Hosted Zone Management  
- DNS Record Creation (A Record)  
- EC2 Web Server Deployment  
- Public Traffic Routing  
- AWS Networking Fundamentals  

---

## 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(Documentation link will be updated)*  

---

## 🎓 Course Reference

Program: AWS Solutions Architect Track  
Track: Cloud Engineering & Architecture Implementation
