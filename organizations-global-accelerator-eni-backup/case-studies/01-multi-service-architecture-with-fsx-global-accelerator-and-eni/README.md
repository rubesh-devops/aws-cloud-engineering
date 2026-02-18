# 🏢 Multi-Service Infrastructure Deployment with AWS Organizations

## 📌 Objective
Designed and implemented a **multi-service AWS architecture** integrating FSx, EC2 Web Servers, Global Accelerator, and Elastic Network Interface (ENI) to demonstrate centralized governance and service orchestration.

---

## 🏗️ Architecture Overview
- 📁 Amazon FSx (Linux File System)
- 🖥️ 4 EC2 Linux Instances
- 🌐 Apache/Nginx Web Servers
- 🚀 AWS Global Accelerator
- 🔌 Elastic Network Interface (ENI)
- 🔐 Security Groups

---

## ⚙️ Implementation Steps

### 1️⃣ FSx for Linux & Multi-Instance Mount
- Created **Amazon FSx (Lustre or ONTAP for Linux)** file system.
- Configured VPC, subnets, and security groups.
- Launched 2 Ubuntu/Amazon Linux EC2 instances.
- Installed NFS utilities.
- Mounted FSx file system on both instances.
- Verified shared storage by creating files from both servers.

---

### 2️⃣ Launch Linux EC2 Web Servers
- Launched 2 additional Linux EC2 instances.
- Installed Apache/Nginx on all instances.
- Configured Security Group to allow HTTP (Port 80).
- Created distinct test web pages.
- Verified browser accessibility.

---

### 3️⃣ Configure AWS Global Accelerator
- Created a new Global Accelerator.
- Configured Listener on Port 80.
- Added Endpoint Group.
- Added both web server EC2 instances as endpoints.
- Enabled health checks.
- Verified traffic routing via Accelerator static IP.
- Tested failover by stopping one instance.

---

### 4️⃣ Create and Attach Elastic Network Interface (ENI)
- Created a new Elastic Network Interface.
- Attached ENI to one EC2 instance.
- Verified secondary private IP allocation.
- Used ENI private IP for SSH connection.
- Confirmed successful login via attached network interface.

---

## 🎯 Key Outcomes
✔️ Shared storage using FSx across multiple EC2 instances  
✔️ Multi-instance web server deployment  
✔️ Global traffic routing using AWS Global Accelerator  
✔️ Secondary network interface attachment and SSH validation  
✔️ Demonstrated multi-service orchestration within AWS  

---

## 📂 Evidence & Documentation
Screenshots, validation steps, and configuration proofs stored in project documentation folder.

---

## 🔗 Consolidated Drive Link
(Add consolidated Google Drive link here)

---

## 🎓 Course Reference
AWS DevOps / Solutions Architect Practical Implementation – Module 10
