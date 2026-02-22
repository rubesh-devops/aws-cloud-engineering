# 🔄 Cross-Engine Database Migration Using AWS DMS Implementation

## 📌 Project Overview

A cross-engine database migration strategy was implemented using AWS Database Migration Service (DMS) to transition data from an Amazon RDS MySQL database to an Amazon RDS PostgreSQL database.

The objective was to provision a source MySQL database, insert sample data, configure DMS replication, and migrate the data seamlessly into a PostgreSQL database to demonstrate heterogeneous database migration.

This implementation reflects real-world cloud modernization and database engine transformation strategy.

---

## 🎯 Business Requirement

XYZ Corporation required:

- Migration of existing database workloads to AWS  
- Improved performance and availability  
- Cross-engine database compatibility  
- Minimal downtime during migration  
- Managed migration using AWS-native services  

---

## 🏗 Architecture Implemented

- Amazon RDS MySQL (Source Database)  
- Amazon RDS PostgreSQL (Target Database)  
- AWS Database Migration Service (DMS)  
- Replication Instance  
- Migration Task Configuration  
- VPC and Security Group Configuration  

---

## ⚙️ Implementation Summary

### 1️⃣ Source Database Setup (RDS MySQL)

- Launched Amazon RDS MySQL instance  
- Configured database credentials  
- Enabled public/private access as required  
- Connected to database  
- Created sample table  
- Inserted sample data records  

---

### 2️⃣ Target Database Setup (RDS PostgreSQL)

- Launched Amazon RDS PostgreSQL instance  
- Configured networking and security groups  
- Validated connectivity  

---

### 3️⃣ AWS DMS Configuration

- Created DMS replication instance  
- Configured source endpoint (MySQL)  
- Configured target endpoint (PostgreSQL)  
- Tested endpoint connections  
- Created migration task  
- Selected full load migration option  

---

### 4️⃣ Migration Validation

- Monitored DMS task status  
- Verified successful data transfer  
- Connected to PostgreSQL database  
- Validated migrated tables and records  

---

## 🔐 Security Configuration

- Configured security groups for database access  
- Restricted inbound access to specific IP ranges  
- Assigned IAM roles for DMS  
- Enforced least privilege access control  

---

## 📊 Outcome Achieved

- Successfully migrated MySQL database to PostgreSQL  
- Achieved cross-engine database transformation  
- Validated data integrity post-migration  
- Demonstrated near-zero downtime migration approach  
- Implemented enterprise-grade database modernization  

---

## 🛠 Skills Demonstrated

- Amazon RDS MySQL Deployment  
- Amazon RDS PostgreSQL Deployment  
- AWS Database Migration Service (DMS)  
- Cross-Engine Database Migration  
- Endpoint and Replication Configuration  
- Cloud Database Modernization  
- Migration Strategy Implementation  

---

## 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(Documentation link will be updated)*  

---

## 🎓 Course Reference

Program: AWS Solutions Architect Track  
Track: Cloud Migration & Database Modernization
