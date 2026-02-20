# 📦 DynamoDB Table Design, Backup and Data Recovery Implementation

## 📌 Project Overview

A fully managed NoSQL database solution was implemented using Amazon DynamoDB to support scalable and low-latency application workloads.

The objective was to design a DynamoDB table with a defined partition key, insert sample data, create a backup, and validate data recovery capability by deleting the table.

This implementation demonstrates serverless database provisioning, data durability strategy, and backup-based recovery architecture.

---

## 🎯 Business Requirement

XYZ Corporation required:

- A fully managed NoSQL database service  
- High scalability with low latency  
- Secure data storage and retrieval  
- Backup and recovery capability  

---

## 🏗 Architecture Implemented

- Amazon DynamoDB Table  
- Partition Key: `ID`  
- On-Demand / Provisioned Capacity Mode  
- DynamoDB Backup Service  
- Data Recovery Validation  

---

## ⚙️ Implementation Summary

### 1️⃣ DynamoDB Table Creation

- Created DynamoDB table  
- Defined Partition Key as `ID`  
- Selected capacity mode (On-Demand / Provisioned)  
- Enabled default encryption  

---

### 2️⃣ Data Insertion

- Added 5 items to the table  
- Validated successful write operations  
- Verified data retrieval using console query  

---

### 3️⃣ Backup and Table Deletion

- Created on-demand backup of DynamoDB table  
- Verified backup status completion  
- Deleted original DynamoDB table  
- Confirmed successful table removal  

---

### 4️⃣ Recovery Validation

- Validated backup availability  
- Confirmed recoverable state  
- Demonstrated database durability mechanism  

---

## 🔐 Security Configuration

- Encryption at rest enabled by default  
- IAM-controlled access to table operations  
- Backup secured under AWS-managed service  
- No public exposure  

---

## 📊 Outcome Achieved

- Successfully designed NoSQL table structure  
- Inserted and validated application data  
- Implemented backup strategy  
- Demonstrated table deletion and recovery readiness  
- Built scalable and serverless database architecture  

---

## 🛠 Skills Demonstrated

- Amazon DynamoDB Table Design  
- Partition Key Architecture  
- NoSQL Data Modeling  
- DynamoDB Backup and Recovery  
- Serverless Database Implementation  
- IAM-Based Access Control  
- Data Durability and Resilience Strategy  

---

## 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(https://drive.google.com/file/d/1mf3JcQvWLDUwxnZs98C9JEi6ASHVXEao/view?usp=drive_link)*  

---

## 🎓 Course Reference

Program: AWS Solutions Architect Track  
Track: Cloud Engineering & Architecture Implementation
