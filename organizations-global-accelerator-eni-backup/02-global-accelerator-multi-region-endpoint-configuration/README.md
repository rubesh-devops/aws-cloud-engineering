# 🚀 Implementing AWS Global Accelerator for Multi-Region Traffic Routing

## 📌 Objective
Configured **AWS Global Accelerator** to distribute global traffic across multi-region endpoints to improve availability, fault tolerance, and performance.

---

## 🏗️ Architecture Components
- 🌎 AWS Global Accelerator
- 🖥️ EC2 Instance (Region 1)
- ⚖️ Application Load Balancer (Region 2)
- 🔐 Security Groups
- 🎯 Target Groups

---

## ⚙️ Implementation Steps

### 1️⃣ Provision EC2 Endpoint (Region A)
- Launched an EC2 instance.
- Installed Apache/Nginx.
- Configured Security Group to allow HTTP (Port 80).
- Verified public accessibility.

### 2️⃣ Provision Load Balancer Endpoint (Region B)
- Launched EC2 instances in second region.
- Installed web server.
- Created Target Group.
- Created Application Load Balancer.
- Registered instances to target group.
- Verified ALB DNS URL accessibility.

### 3️⃣ Configure AWS Global Accelerator
- Created a new Global Accelerator.
- Configured Listener on Port 80.
- Added Endpoint Group for Region A → EC2 Instance.
- Added Endpoint Group for Region B → ALB.
- Configured health checks.
- Enabled traffic dial (100%).

### 4️⃣ Validation & Testing
- Accessed application using Accelerator Static IP.
- Verified routing behavior.
- Stopped one endpoint to test failover.
- Confirmed automatic traffic redirection.

---

## 🎯 Key Outcomes
✔️ Global Anycast IP for application access  
✔️ Improved application availability  
✔️ Automatic failover between regions  
✔️ Reduced latency using AWS edge network  

---

## 📂 Evidence & Documentation
Screenshots and validation proof stored in project documentation folder.

---

## 🔗 Consolidated Drive Link
(Add consolidated Google Drive link here)

---

## 🎓 Course Reference
AWS DevOps / Solutions Architect Practical Implementation – Module 10
