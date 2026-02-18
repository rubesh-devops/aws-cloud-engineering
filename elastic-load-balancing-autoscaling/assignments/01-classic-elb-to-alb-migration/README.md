# ⚖️ elastic-load-balancer-migration-strategy

---

# 🚀 Classic ELB to Application Load Balancer Migration

## 📌 Business Scenario

XYZ Corporation is experiencing increasing application traffic. Their existing on-premises infrastructure requires frequent hardware purchases to handle load spikes, resulting in high operational costs.

To improve scalability and reduce infrastructure expenses, the organization decided to migrate to AWS and implement Elastic Load Balancing.

---

## 🎯 Objective

Design and implement a scalable load balancing solution by:

- Deploying a **Classic Load Balancer**
- Registering **3 EC2 instances** running different web pages
- Migrating the architecture to an **Application Load Balancer (ALB)**

---

## 🏗 Architecture Implemented

### 🔹 Phase 1 – Classic Load Balancer

- Launched 3 EC2 instances
- Installed web server on each instance
- Configured unique web page on each instance
- Created Classic Load Balancer
- Registered all 3 EC2 instances
- Verified traffic distribution across instances

### 🔹 Phase 2 – Migration to Application Load Balancer

- Created Target Group
- Registered EC2 instances to Target Group
- Configured Application Load Balancer
- Defined listener rules
- Tested load distribution and health checks
- Decommissioned Classic Load Balancer

---

## 🔄 Migration Strategy

The migration involved:

- Creating ALB alongside existing CLB
- Registering same instances to new Target Group
- Verifying health checks
- Testing traffic routing
- Switching traffic to ALB
- Safely removing Classic Load Balancer

This ensured **zero downtime migration**.

---

## 📊 Outcome

✔ Traffic distributed across 3 instances  
✔ Improved request routing efficiency  
✔ Layer 7 (HTTP/HTTPS) routing capability enabled  
✔ Better health monitoring  
✔ Future-ready scalable architecture  

---

## ⚙️ Key Concepts Demonstrated

- Classic Load Balancer vs Application Load Balancer
- Target Groups
- Listener configuration
- Health Checks
- Zero downtime migration
- Horizontal scaling architecture

---

## 🛡 High Availability Strategy

- Multi-instance deployment
- Health-based traffic routing
- Centralized entry point via Load Balancer
- Reduced dependency on single machine

---

## 📈 Skills Demonstrated

- AWS Elastic Load Balancing
- EC2 Web Server Configuration
- Load Balancer Migration Strategy
- High Availability Design
- Production-ready Infrastructure Deployment

---

## 📸 Validation & Evidence

📄 **Consolidated Execution Documentation**  
👉 Google Drive: *(Documentation link will be updated)*  

---

## 🎓 Course Reference

This project is part of:

**Elastic Load Balancing & Auto Scaling**  
**AWS Cloud Engineering Program**  
**DevOps Architect Master’s Program – Intellipaat**

---

