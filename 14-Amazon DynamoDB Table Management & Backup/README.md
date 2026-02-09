# 🗃️ Amazon DynamoDB Table Management & Backup

---

## 📌 **Project Overview**

Designed and implemented a **serverless NoSQL database solution using Amazon DynamoDB** to support XYZ Corporation’s application requirements for **highly scalable and low-latency data storage**.

This assignment demonstrates how DynamoDB can be used to **store structured data**, manage items efficiently, and ensure **data protection through backups**, followed by safe resource cleanup.

---

## 🏗 **Architecture Components**

- **Amazon DynamoDB**
- **DynamoDB Table**
- **Partition Key (ID)**
- **DynamoDB Items**
- **On-Demand Backup**
- **Serverless Database Architecture**

---

## 🎯 **Objective**

To implement a database solution that:

- Uses **Amazon DynamoDB** for fast and scalable data access
- Organizes data using a **partition key**
- Stores and retrieves items efficiently
- Ensures data safety through **backup before deletion**
- Demonstrates safe resource lifecycle management

---

## ⚙️ **Implementation Steps**

### 1️⃣ **DynamoDB Table Creation**

- Created a **DynamoDB table**
- Defined **Partition Key** as:
  - `ID`
- Selected appropriate capacity mode
- Verified successful table creation

---

### 2️⃣ **Item Insertion**

- Added **5 items** to the DynamoDB table
- Ensured each item contained a unique **ID**
- Verified item availability using the DynamoDB console

---

### 3️⃣ **Backup Creation**

- Created an **on-demand backup** of the DynamoDB table
- Verified backup status and availability
- Ensured data could be restored if required

---

### 4️⃣ **Table Deletion**

- Safely deleted the DynamoDB table
- Confirmed backup exists prior to deletion
- Completed resource cleanup to avoid unnecessary costs

---

## 🔐 **Security & Data Protection Configuration**

- Used DynamoDB’s **managed security model**
- Ensured data protection using **table backup**
- Followed safe deletion practices
- Avoided exposure of sensitive data

---

## 📈 **Key Learning Outcomes**

- DynamoDB table design fundamentals
- Partition key selection and usage
- Item creation and data modeling
- Backup and restore strategies
- Serverless database lifecycle management
- NoSQL database best practices

---

## 🏆 **Real-World Use Case**

Amazon DynamoDB is commonly used in:

- Serverless applications
- High-traffic web and mobile apps
- Real-time data processing systems
- Event-driven architectures
- Applications requiring millisecond latency
- Scalable cloud-native backends

---

## 📊 **Outcome**

Successfully implemented a **DynamoDB table** with structured items, created a **backup for data protection**, and safely deleted the table after validation.

Demonstrated DynamoDB’s ability to deliver **scalable, reliable, and serverless data storage**.

---

## 🛠 **Skills Demonstrated**

- Amazon DynamoDB
- NoSQL Database Design
- Partition Key Modeling
- Item Management
- Backup & Data Protection
- Serverless Architecture
- AWS Database Services

---

## 📸 **Proof of Implementation**

📄 Consolidated Assignment Execution PDF:  
👉 *https://drive.google.com/file/d/1mf3JcQvWLDUwxnZs98C9JEi6ASHVXEao/view?usp=drive_link*

---

## 📚 **Course Reference**

Assignment completed as part of:

**AWS Solutions Architect – DevOps Architect Master’s Program (Intellipaat)**  

Certificate available in the main repository.
