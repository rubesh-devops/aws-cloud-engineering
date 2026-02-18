# ⚡ Serverless Application Deployment using AWS Lambda & SQS

## 📌 Project Overview

Designed and implemented a **serverless architecture** using AWS Lambda and Amazon SQS to eliminate the need for continuously running servers.

This solution enables event-driven processing where compute resources are triggered only when required, optimizing cost and operational efficiency.

---

## 🎯 Business Requirement

XYZ Corporation required:

- A web-based backend process
- No continuously running servers
- Fully managed AWS-native architecture
- Event-driven execution model
- Automatic scaling based on workload

---

## 🏗 Architecture Implemented

**Event Flow:**

Amazon SQS Queue → AWS Lambda Function → Execution of Python Code

- Messages are sent to SQS
- SQS triggers Lambda automatically
- Lambda processes messages without server provisioning
- Fully managed and auto-scaled infrastructure

---

## ⚙️ Implementation Summary

### 1️⃣ Created a Python-based AWS Lambda Function
- Runtime: Python
- Event-driven execution model
- Stateless function execution
- Automatic scaling enabled

### 2️⃣ Configured SQS as Lambda Trigger
- Created an SQS queue
- Configured Lambda event source mapping
- Enabled automatic invocation upon message arrival

### 3️⃣ Tested Event Invocation
- Sent sample messages to SQS
- Verified Lambda execution logs in CloudWatch
- Confirmed successful event-driven processing

---

## 🔐 Security & Management

- IAM role attached to Lambda for secure execution
- Principle of least privilege followed
- CloudWatch logging enabled for monitoring
- No server management required

---

## 📈 Outcomes Achieved

- Eliminated need for EC2 instances
- Reduced infrastructure cost via serverless model
- Implemented event-driven processing architecture
- Achieved auto-scaling without manual configuration
- Improved operational efficiency

---

## 💼 Skills Demonstrated

- AWS Lambda (Serverless Compute)
- Amazon SQS (Event Messaging)
- Event Source Mapping
- CloudWatch Monitoring
- IAM Role Management
- Serverless Architecture Design

---

## 🏆 Real-World Use Case

This architecture is suitable for:

- Background job processing
- Order processing systems
- Asynchronous API workloads
- Event-based microservices
- Cost-optimized backend processing

---

## 📸 Validation & Evidence

📄 **Consolidated Execution Documentation**  
👉 Google Drive: *(Documentation link will be updated)*

---

## 📚 Module & Course Reference

**Module 9 – AWS Lambda, Elastic Beanstalk, AWS OpsWorks and API Gateway**  
**AWS Course**  
**Part of DevOps Architect Master’s Program – Intellipaat**
