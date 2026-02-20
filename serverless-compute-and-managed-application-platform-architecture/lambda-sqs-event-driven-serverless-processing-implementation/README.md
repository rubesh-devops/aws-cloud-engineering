# ⚡ Lambda Event-Driven Processing with SQS Trigger Integration

## 📌 Project Overview

A serverless, event-driven compute architecture was implemented using AWS Lambda integrated with Amazon SQS.

The objective was to build a Python-based Lambda function and configure Amazon SQS as an event source trigger to enable automatic invocation based on queue messages.

This implementation demonstrates serverless application design, asynchronous event processing, and managed compute architecture without persistent servers.

---

## 🎯 Business Requirement

XYZ Corporation required:

- Serverless compute solution  
- No continuously running servers  
- Event-driven architecture  
- Automated message processing  
- Fully managed infrastructure  

---

## 🏗 Architecture Implemented

- AWS Lambda (Python Runtime)  
- Amazon SQS Queue  
- Event Source Mapping (SQS → Lambda)  
- IAM Execution Role for Lambda  

---

## ⚙️ Implementation Summary

### 1️⃣ Lambda Function Creation

- Created AWS Lambda function  
- Selected Python runtime  
- Defined handler function  
- Configured execution role with required permissions  
- Deployed sample processing logic  

---

### 2️⃣ SQS Queue Setup

- Created Amazon SQS queue  
- Configured queue properties  
- Verified queue availability  

---

### 3️⃣ Event Trigger Configuration

- Configured SQS as Lambda trigger  
- Created event source mapping  
- Defined batch size and trigger behavior  
- Granted Lambda permission to poll SQS  

---

### 4️⃣ Invocation Testing

- Sent test message to SQS queue  
- Verified automatic Lambda invocation  
- Checked CloudWatch Logs for execution output  
- Confirmed successful message processing  

---

## 🔐 Security Configuration

- IAM execution role with least privilege permissions  
- Controlled SQS access  
- Restricted Lambda permissions  
- No publicly exposed endpoints  

---

## 📊 Outcome Achieved

- Successfully implemented serverless compute solution  
- Enabled asynchronous event-driven processing  
- Eliminated need for continuously running servers  
- Validated automated invocation through SQS  
- Built scalable, cost-efficient compute architecture  

---

## 🛠 Skills Demonstrated

- AWS Lambda Deployment  
- Python-Based Serverless Function Development  
- Amazon SQS Integration  
- Event-Driven Architecture Design  
- IAM Role Configuration  
- CloudWatch Logs Monitoring  
- Serverless Compute Strategy  

---

## 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(https://drive.google.com/file/d/1HLfRd8WNN7hAzZtaVtmZM1S34jMDF7TB/view?usp=drive_link)*  

---

## 🎓 Course Reference

Program: AWS Solutions Architect Track  
Track: Cloud Engineering & Architecture Implementation
