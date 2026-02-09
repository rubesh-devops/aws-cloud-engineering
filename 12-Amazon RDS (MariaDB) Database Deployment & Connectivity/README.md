# 🗄️ Amazon RDS (MariaDB) Database Deployment & Connectivity

---

## 📌 **Project Overview**

Designed and implemented a **managed relational database solution using Amazon RDS (MariaDB)** to support XYZ Corporation’s application requirements for **reliable SQL-based data storage and retrieval**.

This assignment demonstrates how to deploy a managed database service in AWS and validate connectivity from both **Windows-based SQL clients** and **Linux-based EC2 instances**, simulating real-world migration and access scenarios.

---

## 🏗 **Architecture Components**

- **Amazon RDS (MariaDB Engine)**
- **Amazon EC2 (Linux)**
- **SQL Client (Windows)**
- **VPC & Subnets**
- **Security Groups**
- **Database Connectivity Architecture**

---

## 🎯 **Objective**

To implement a database solution that:

- Uses a **managed SQL database engine (MariaDB)**
- Provides secure and reliable data storage
- Supports access from both Windows and Linux environments
- Simplifies database administration using AWS RDS

---

## ⚙️ **Implementation Steps**

### 1️⃣ **RDS MariaDB Instance Creation**

- Created an **Amazon RDS instance** using the **MariaDB engine**
- Configured database settings:
  - DB instance identifier
  - Master username and password
  - Instance size and storage
- Deployed RDS within a **VPC**
- Ensured database availability and successful provisioning

---

### 2️⃣ **Security Group Configuration**

- Configured **security groups** to allow:
  - Database port access (MariaDB – 3306)
- Restricted access to:
  - Authorized IPs / EC2 instances only
- Ensured database is protected from public exposure

---

### 3️⃣ **Database Connectivity – Windows SQL Client**

- Installed a **SQL client on Windows**
- Connected to the RDS MariaDB endpoint
- Verified successful authentication and database access
- Executed basic SQL queries to validate connectivity

---

### 4️⃣ **Database Connectivity – Linux EC2 Instance**

- Launched a **Linux-based EC2 instance**
- Installed MariaDB/MySQL client packages
- Connected to the RDS endpoint from EC2
- Verified database access and query execution

---

## 🔐 **Security & Availability Configuration**

- Used **AWS-managed RDS** for automated maintenance
- Restricted database access via security groups
- Avoided unnecessary public access
- Leveraged AWS RDS features for reliability and durability

---

## 📈 **Key Learning Outcomes**

- Amazon RDS database provisioning
- MariaDB engine configuration
- Secure database connectivity
- Cross-platform database access
- VPC-based database security
- Managed database service benefits
- SQL client integration in cloud environments

---

## 🏆 **Real-World Use Case**

Amazon RDS with MariaDB is commonly used in:

- Enterprise web applications
- Migration from on-premise databases
- Production SQL workloads
- Applications requiring high availability
- Managed database environments
- Cost-optimized relational database solutions

---

## 📊 **Outcome**

Successfully deployed an **Amazon RDS MariaDB database** and validated secure connectivity from:

- A **Windows-based SQL client**
- A **Linux-based EC2 instance**

Demonstrated a reliable, scalable, and managed SQL database solution suitable for production workloads.

---

## 🛠 **Skills Demonstrated**

- Amazon RDS
- MariaDB Engine
- SQL Database Management
- Database Connectivity & Networking
- Linux Administration
- Windows SQL Client Usage
- Cloud Database Security
- Managed Database Architecture

---

## 📸 **Proof of Implementation**

📄 Consolidated Assignment Execution PDF:  
👉 *https://drive.google.com/file/d/1RNjfKyDCph-XoPuzN6mXzWCp1XrVtUzF/view?usp=drive_link*

---

## 📚 **Course Reference**

Assignment completed as part of:

**AWS Solutions Architect – DevOps Architect Master’s Program (Intellipaat)**  

Certificate available in the main repository.
