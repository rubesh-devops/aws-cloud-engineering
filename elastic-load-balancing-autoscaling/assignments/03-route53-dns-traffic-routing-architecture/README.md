# 🌐 DNS Traffic Routing Architecture using Route 53

---

## 📌 Execution Overview

Implemented DNS-based traffic routing using Amazon Route 53 to direct web traffic to an EC2 instance running Apache Web Server.

This implementation demonstrates practical experience in:

- Route 53 Hosted Zone management  
- A Record configuration  
- Public IP mapping  
- Web server exposure via domain name  
- Cloud networking fundamentals  

---

## 🏗 Architecture Implemented

Client Request  
↓  
Amazon Route 53 Hosted Zone  
↓  
A Record (Mapped to Public IP)  
↓  
EC2 Instance (Apache Web Server)  

---

## 🎯 Business Objective

XYZ Corporation required domain-based traffic routing after migrating infrastructure to AWS.

Goal:

- Replace direct IP access with DNS-based routing  
- Improve production readiness  
- Enable scalable traffic management  

---

## ⚙️ Implementation Summary

### 1️⃣ Hosted Zone Utilization
- Used existing Route 53 Hosted Zone  
- Verified NS and SOA records  

### 2️⃣ Web Server Configuration
- Deployed Apache on EC2 instance  
- Configured Security Groups for HTTP access  
- Verified web server availability via Public IP  

### 3️⃣ DNS Record Creation
- Created A Record  
- Mapped domain to EC2 Public IP  
- Configured TTL settings  

### 4️⃣ Validation
- Accessed application via domain name  
- Verified successful traffic routing  
- Confirmed DNS resolution  

---

## 🔐 Security & Networking Considerations

- HTTP port exposed intentionally  
- Controlled inbound rules via Security Groups  
- No unnecessary port exposure  
- Domain-based abstraction instead of raw IP access  

---

## 📈 Skills Demonstrated

- Amazon Route 53 configuration  
- DNS record management  
- EC2 web server deployment  
- Domain-to-IP routing  
- Cloud networking fundamentals  
- Production-ready traffic redirection  

---

## 🏆 Outcome

Successfully configured DNS routing to EC2 instance.

✔ Domain resolves correctly  
✔ Apache server accessible via DNS  
✔ Secure and controlled traffic routing  
✔ Production-style cloud networking setup  

---

## 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: (Documentation link will be updated)

---

## 📚 Module Reference

Module 4 – Elastic Load Balancing & Auto Scaling  
AWS Cloud Engineering  
Part of DevOps Architect Master’s Program – Intellipaat
