# 📣 CloudFormation Stack Notification Automation Using SNS

## 📌 Project Overview

An automated infrastructure notification mechanism was implemented using AWS CloudFormation integrated with Amazon SNS.

The objective was to enhance an existing CloudFormation template by configuring stack-level notifications so that email alerts are triggered during every stage of stack creation and execution.

This implementation demonstrates infrastructure monitoring automation, event-driven notification design, and improved operational visibility.

---

## 🎯 Business Requirement

XYZ Corporation required:

- Automated notifications during infrastructure deployment  
- Real-time visibility into stack creation events  
- Email-based alerting mechanism  
- Improved DevOps monitoring and governance  

---

## 🏗 Architecture Implemented

- AWS CloudFormation Stack  
- Existing S3 Template (from previous task)  
- Amazon SNS Topic  
- Email Subscription Endpoint  
- Stack Notification Configuration  

---

## ⚙️ Implementation Summary

### 1️⃣ SNS Topic Creation

- Created Amazon SNS topic  
- Configured email subscription  
- Confirmed subscription via verification link  
- Validated topic readiness  

---

### 2️⃣ CloudFormation Stack Notification Configuration

- Used existing CloudFormation template (S3 bucket template)  
- Added SNS topic ARN to stack notification settings  
- Configured stack to publish events to SNS  

---

### 3️⃣ Deployment and Validation

- Initiated stack creation  
- Monitored stack events  
- Verified receipt of email notifications for:
  - Stack creation start  
  - Resource creation events  
  - Stack completion status  

---

## 🔐 Security Configuration

- Restricted SNS topic access  
- Confirmed only verified email endpoint receives notifications  
- Maintained secure stack execution permissions  
- Enforced least privilege IAM policies  

---

## 📊 Outcome Achieved

- Successfully integrated CloudFormation with SNS  
- Enabled real-time deployment monitoring  
- Automated stack lifecycle notifications  
- Improved operational transparency  
- Strengthened infrastructure governance  

---

## 🛠 Skills Demonstrated

- AWS CloudFormation Stack Management  
- Amazon SNS Configuration  
- Infrastructure Event Monitoring  
- Event-Driven Architecture Design  
- Deployment Automation  
- DevOps Monitoring Practices  

---

## 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(Documentation link will be updated)*  

---

## 🎓 Course Reference

Program: AWS Solutions Architect Track  
Track: Cloud Engineering & Architecture Implementation
