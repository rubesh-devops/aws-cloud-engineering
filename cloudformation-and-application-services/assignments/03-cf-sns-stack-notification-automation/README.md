# 📢 CloudFormation – Stack Notifications with SNS Integration

## 📌 Project Overview

XYZ Corporation required enhanced visibility into infrastructure deployments across Development, Testing, and Production environments. To improve governance and monitoring, email notifications were integrated into the CloudFormation stack lifecycle using Amazon SNS.

This project extends the existing CloudFormation S3 template by enabling automated stack event notifications via SNS.

---

## 🎯 Business Objective

Enhance Infrastructure as Code deployment by:

- Reusing existing CloudFormation template
- Integrating Amazon SNS for stack lifecycle notifications
- Receiving email alerts for:
  - Stack creation
  - Resource creation
  - Update operations
  - Rollbacks and failures

---

## 🏗 Architecture Components

- AWS CloudFormation
- Amazon SNS (Simple Notification Service)
- Email Subscription
- S3 Bucket Template (from previous assignment)
- Stack Event Monitoring

---

## ⚙️ Implementation Strategy

### 1️⃣ Reuse Existing CloudFormation Template

- Used previously created S3 bucket template
- Maintained versioning capability
- Ensured stack reusability across environments

---

### 2️⃣ SNS Topic Creation

- Created Amazon SNS topic for stack notifications
- Configured email subscription
- Confirmed subscription via email verification

---

### 3️⃣ CloudFormation Stack Notification Integration

- Attached SNS Topic ARN to CloudFormation stack
- Enabled stack event publishing
- Monitored:
  - CREATE_IN_PROGRESS
  - CREATE_COMPLETE
  - UPDATE_IN_PROGRESS
  - UPDATE_COMPLETE
  - ROLLBACK events

---

### 4️⃣ Validation

- Triggered stack creation
- Verified email notifications received for each deployment stage
- Confirmed real-time infrastructure event visibility

---

## 🛡 Security & Best Practices

- Decoupled notification system from infrastructure template
- Used SNS subscription confirmation process
- Enabled transparent infrastructure monitoring
- Improved operational awareness

---

## 🚀 Outcomes Achieved

- Real-time CloudFormation deployment visibility
- Automated email notifications for stack lifecycle events
- Improved operational monitoring
- Reduced manual stack status checks
- Enterprise-ready infrastructure governance enhancement

---

## 💼 Skills Demonstrated

- CloudFormation Stack Management
- SNS Integration with Infrastructure
- Event-Driven Architecture
- Infrastructure Monitoring Automation
- AWS Governance Best Practices
- Deployment Lifecycle Observability

---

## 📸 Validation & Evidence

📄 **Consolidated Execution Documentation**  
👉 Google Drive: *(Documentation link will be updated)*

---

## 📚 Module & Course Reference

**Module 8 – CloudFormation and App Services**  
**AWS Course**  
**Part of DevOps Architect Master’s Program – Intellipaat**
