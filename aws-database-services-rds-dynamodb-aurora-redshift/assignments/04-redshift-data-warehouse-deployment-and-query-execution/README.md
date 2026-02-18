# 🏢 Amazon Redshift Data Warehouse Deployment & Query Execution

## 📌 Project Overview

To support analytical workloads and large-scale structured data processing, Amazon Redshift was implemented as the data warehousing solution for XYZ Corporation.

This project demonstrates provisioning a Redshift cluster, loading structured data, and performing SQL-based analytical queries using the Redshift Query Editor.

The implementation validates enterprise-grade data warehousing capabilities on AWS.

---

## 🎯 Business Requirement

XYZ Corporation required:

- A scalable data warehouse solution
- Ability to load structured datasets
- Execute analytical SQL queries
- Support reporting and business intelligence workloads

Amazon Redshift was selected due to its columnar storage architecture, performance optimization, and seamless AWS integration.

---

## 🏗 Architecture Overview

- **Amazon Redshift Cluster**
- **AWS IAM Role for Redshift**
- **Query Editor v2**
- **S3 (Optional Data Source)**
- **VPC & Security Groups**

Redshift cluster was deployed inside a VPC with controlled access.

---

## ⚙️ Implementation Summary

### 1️⃣ Redshift Cluster Deployment

- Created a Redshift cluster
- Selected node type based on workload requirements
- Configured database name, master username and password
- Attached IAM role for data access
- Configured VPC and security group rules

Cluster provisioning was validated after status became *Available*.

---

### 2️⃣ Data Loading via Query Editor

- Connected to Redshift using Query Editor v2
- Created database tables using SQL
- Loaded structured sample data
- Verified row counts after ingestion

Data load validation ensured the warehouse was operational.

---

### 3️⃣ Query Execution & Validation

Executed analytical queries such as:

- SELECT queries
- Aggregation queries (COUNT, SUM, GROUP BY)
- Filtering and sorting
- Performance validation of execution time

Verified expected results were returned successfully.

---

## 📊 Outcomes Achieved

- Successfully deployed a Redshift data warehouse
- Loaded structured data into cluster
- Executed analytical SQL queries
- Validated connectivity and performance
- Demonstrated reporting-ready data architecture

---

## 🛡 Security & Networking Considerations

- Cluster deployed inside VPC
- Security group restricted access
- IAM role attached for secure data access
- Credentials stored securely

---

## 💼 Skills Demonstrated

- Amazon Redshift cluster provisioning
- Data warehouse architecture
- SQL query execution
- AWS IAM integration
- Data ingestion workflows
- Cloud-based analytics setup
- Secure network configuration

---

## 📸 Validation & Evidence

📄 **Consolidated Execution Documentation**  
👉 Google Drive: *(Documentation link will be updated)*

---

## 📚 Module & Course Reference

**Module 7 – Database Services**  
**AWS Course**  
**Part of DevOps Architect Master’s Program – Intellipaat**
