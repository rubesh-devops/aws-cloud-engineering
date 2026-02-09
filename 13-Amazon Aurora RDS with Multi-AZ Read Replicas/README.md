# 🗄️ Amazon Aurora RDS with Multi-AZ Read Replicas

---

## 📌 **Project Overview**

Designed and implemented a **highly available and scalable relational database architecture** using **Amazon Aurora**, AWS’s cloud-native database engine.

This assignment demonstrates how Aurora provides **high availability, fault tolerance, and read scalability** by deploying **multiple read replicas across different Availability Zones**, making it ideal for production-grade workloads.

---

## 🏗 **Architecture Components**

- **Amazon Aurora (RDS Engine)**
- **Aurora Primary DB Instance**
- **Aurora Read Replicas**
- **Multi-AZ Deployment**
- **VPC & Subnets**
- **Security Groups**
- **Database Replication Architecture**

---

## 🎯 **Objective**

To implement a database solution that:

- Uses **Amazon Aurora** for managed SQL workloads
- Improves **availability and fault tolerance**
- Scales read operations using **read replicas**
- Distributes replicas across **multiple Availability Zones**
- Supports enterprise-grade database reliability

---

## ⚙️ **Implementation Steps**

### 1️⃣ **Aurora Database Cluster Creation**

- Created an **Amazon Aurora RDS cluster**
- Selected Aurora-compatible SQL engine
- Configured primary (writer) DB instance
- Deployed cluster inside a **VPC**
- Verified successful database provisioning

---

### 2️⃣ **Read Replica Configuration**

- Created **two Aurora Read Replicas**
- Deployed replicas in **different Availability Zones**
- Verified replica synchronization with the primary instance
- Ensured replicas are available for read operations

---

### 3️⃣ **High Availability Validation**

- Confirmed:
  - Primary instance handles write operations
  - Read replicas handle read traffic
- Validated Aurora’s automatic replication and failover capabilities
- Ensured infrastructure resilience across AZ failures

---

## 🔐 **Security & Availability Configuration**

- Restricted database access using **security groups**
- Avoided unnecessary public exposure
- Used **Multi-AZ architecture** for fault tolerance
- Leveraged Aurora’s **managed replication and self-healing features**

---

## 📈 **Key Learning Outcomes**

- Amazon Aurora architecture understanding
- Multi-AZ database deployment
- Read replica configuration and usage
- High availability and fault tolerance design
- Managed database scaling strategies
- Enterprise-grade SQL database architecture

---

## 🏆 **Real-World Use Case**

Amazon Aurora is widely used in:

- High-traffic web applications
- Enterprise backend systems
- SaaS platforms
- Read-intensive workloads
- Mission-critical production databases
- Cloud-native database migrations

---

## 📊 **Outcome**

Successfully deployed an **Amazon Aurora database cluster** with **two read replicas across different Availability Zones**, achieving:

- Improved availability
- Read scalability
- Fault tolerance
- Production-ready database architecture

---

## 🛠 **Skills Demonstrated**

- Amazon Aurora RDS
- Multi-AZ Database Architecture
- Read Replica Configuration
- High Availability Design
- Cloud Database Scaling
- AWS Managed Database Services
- SQL Database Architecture

---

## 📸 **Proof of Implementation**

📄 Consolidated Assignment Execution PDF:  
👉 *https://drive.google.com/file/d/1Aopc81XUoMjifhf1qX3B9_YtQfaGcpE5/view?usp=drive_link*

---

## 📚 **Course Reference**

Assignment completed as part of:

**AWS Solutions Architect – DevOps Architect Master’s Program (Intellipaat)**  

Certificate available in the main repository.
