# 🌍 Dynamic Scaling Architecture using ELB, Auto Scaling & Route 53

## 📌 Business Scenario

XYZ Corporation was operating on limited on-premise infrastructure. As application traffic increased, the organization had to frequently purchase new hardware to handle the load.

To reduce infrastructure cost and improve scalability, the company migrated to AWS and implemented an automated, highly available architecture using:

• Elastic Load Balancer  
• Auto Scaling Group  
• Route 53  

This solution enables automatic scaling based on CPU utilization and ensures traffic is evenly distributed across compute resources.

---

## 🎯 Objective

Design and implement a scalable AWS architecture that:

• Automatically adds EC2 instances when CPU utilization exceeds 80%  
• Automatically removes EC2 instances when CPU utilization falls below 60%  
• Distributes incoming traffic using a Load Balancer  
• Routes traffic to the company domain using Route 53  

---

## 🏗 Architecture Overview

The implemented architecture includes:

• EC2 instances running web servers  
• Launch Template / Launch Configuration  
• Auto Scaling Group (Min, Desired, Max capacity defined)  
• Scaling Policies based on CPU thresholds  
• Application Load Balancer  
• Route 53 Hosted Zone pointing domain to ALB  

Traffic Flow:

User → Route 53 → Application Load Balancer → Auto Scaling EC2 Instances  

---

## ⚙ Implementation Summary

### 1️⃣ Auto Scaling Configuration

• Created Launch Configuration with pre-configured web server AMI  
• Created Auto Scaling Group  
• Configured scaling policies:

  - Scale Out: CPU > 80%  
  - Scale In: CPU < 60%  

• Enabled CloudWatch alarms to trigger scaling actions  

---

### 2️⃣ Load Balancer Configuration

• Created Application Load Balancer  
• Configured Target Group  
• Registered Auto Scaling Group instances automatically  
• Enabled health checks for instance monitoring  

---

### 3️⃣ DNS Configuration

• Used Route 53 Hosted Zone  
• Created Alias record pointing to Application Load Balancer  
• Verified domain-based traffic routing  

---

## 📈 Key Outcomes

✔ Automatic infrastructure scaling  
✔ Reduced manual provisioning  
✔ Improved availability  
✔ Even traffic distribution  
✔ Cost optimization through scale-in policy  
✔ Domain-based production routing  

---

## 🛠 Skills Demonstrated

• Elastic Load Balancing (ALB)  
• Auto Scaling Groups  
• CloudWatch Scaling Policies  
• Route 53 DNS Routing  
• High Availability Architecture Design  
• Infrastructure Cost Optimization  
• Performance-Based Scaling Strategy  

---

## 🏆 Business Impact

• Eliminated need for constant hardware procurement  
• Achieved elastic cloud scalability  
• Improved uptime and performance  
• Reduced operational overhead  
• Enabled production-grade scalable deployment  

---

## 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: (Execution screenshots link will be updated)

---

## 📚 Module Reference

Module: Elastic Load Balancing & Auto Scaling  
Course: DevOps Course  
Program: DevOps Architect Master’s Program – Intellipaat
