# ⚖️ Elastic Load Balancing & Auto Scaling with Route 53

---

## 📌 **Project Overview**

Designed and implemented a **highly available, scalable web application architecture** on AWS to handle fluctuating traffic demands for XYZ Corporation.

This assignment demonstrates how **Elastic Load Balancer (ELB)**, **Auto Scaling Groups (ASG)**, and **Amazon Route 53** can be used together to **automatically scale compute resources**, distribute load efficiently, and route traffic to a company domain—reducing infrastructure cost and operational overhead.

---

## 🏗 **Architecture Components**

- **Amazon EC2**
- **Elastic Load Balancer (ELB / ALB)**
- **Auto Scaling Group (ASG)**
- **Launch Template / Launch Configuration**
- **Amazon CloudWatch**
- **Amazon Route 53**
- **VPC & Subnets**

---

## 🎯 **Objective**

To design a cloud-native architecture that:

- Automatically **scales compute resources** based on CPU utilization
- Efficiently **distributes traffic** across instances
- Routes traffic using a **custom domain**
- Reduces infrastructure cost compared to on-premise systems
- Improves availability, performance, and resilience

---

## ⚙️ **Implementation Steps**

### 1️⃣ **Auto Scaling Configuration**

- Created an **Auto Scaling Group (ASG)** for EC2 instances
- Configured scaling policies:
  - **Scale out** when CPU utilization exceeds **80%**
  - **Scale in** when CPU utilization falls below **60%**
- Defined minimum, desired, and maximum instance capacity

---

### 2️⃣ **Elastic Load Balancer Setup**

- Created an **Elastic Load Balancer**
- Attached Auto Scaling Group instances to the load balancer
- Configured listener rules to distribute incoming traffic
- Ensured health checks for instance availability

---

### 3️⃣ **Traffic Distribution & Validation**

- Verified load is evenly distributed across EC2 instances
- Confirmed new instances are automatically registered with ELB
- Validated traffic handling during scaling events

---

### 4️⃣ **Route 53 Domain Routing**

- Configured **Amazon Route 53**
- Created DNS record to route traffic to the Load Balancer
- Linked company domain to AWS infrastructure
- Verified domain-based access to the application

---

## 🔐 **Security & Availability Configuration**

- Used **security groups** to allow only required ports
- Deployed instances across **multiple Availability Zones**
- Enabled ELB health checks for fault tolerance
- Automated scaling reduced manual intervention

---

## 📈 **Key Learning Outcomes**

- Auto Scaling policy design
- CPU-based scaling strategies
- Load balancing concepts and configuration
- High availability architecture
- Domain routing using Route 53
- Cost optimization using cloud elasticity
- Migrating from on-premise to AWS

---

## 🏆 **Real-World Use Case**

This architecture is commonly used in:

- High-traffic web applications
- E-commerce platforms
- SaaS products
- Enterprise workload migration to cloud
- Applications with unpredictable traffic patterns
- Cost-optimized production environments

---

## 📊 **Outcome**

Successfully implemented a **scalable and highly available AWS architecture** that:

- Automatically scales resources based on load
- Distributes traffic efficiently across instances
- Routes traffic via a custom domain
- Reduces infrastructure cost compared to on-premise systems
- Improves application reliability and performance

---

## 🛠 **Skills Demonstrated**

- Elastic Load Balancing (ELB / ALB)
- Auto Scaling Groups (ASG)
- CloudWatch Metrics & Scaling Policies
- EC2 Compute Scaling
- High Availability Architecture
- Amazon Route 53 DNS Routing
- Cloud Cost Optimization
- AWS Infrastructure Design

---

## 📸 **Proof of Implementation**

📄 Consolidated Assignment Execution PDF:  
👉 *https://drive.google.com/file/d/1NJXLeRcc6sZEvxk5mRT2dy5QzVFZDoZh/view?usp=drive_link*

---

## 📚 **Course Reference**

Assignment completed as part of:

**AWS Solutions Architect – DevOps Architect Master’s Program (Intellipaat)**  

Certificate available in the main repository.
