# 🚨 Cost Governance & Performance Alerting using Amazon CloudWatch

---

## 📌 Project Overview

Designed and implemented a **proactive alerting system** using **Amazon CloudWatch Alarms and Amazon SNS** to monitor:

- 💰 AWS Billing thresholds
- 📈 EC2 CPU utilization spikes

This implementation strengthens **cost governance**, **infrastructure monitoring**, and **automated incident notification mechanisms** within the AWS environment.

---

## 🎯 Business Objective

XYZ Corporation required:

- Real-time visibility into AWS spending
- Immediate notification if billing crosses defined limits
- Automated alerts for abnormal CPU utilization
- Integration with notification services for operational response

This ensures **financial control and performance risk mitigation**.

---

## 🏗 Architecture Components

- **Amazon CloudWatch Metrics**
- **CloudWatch Billing Alerts**
- **CloudWatch CPU Alarms**
- **Amazon SNS (Simple Notification Service)**
- **Amazon EC2**

---

## ⚙️ Implementation Summary

### 1️⃣ Billing Alarm Configuration

Created a **CloudWatch Billing Alarm** configured to:

- Monitor **EstimatedCharges**
- Trigger when cost exceeds **$500**
- Send alert notification through SNS

This enables cost visibility and prevents unexpected budget overruns.

---

### 2️⃣ EC2 CPU Utilization Alarm

Configured a **CloudWatch Alarm** for:

- Metric: `CPUUtilization`
- Threshold: **Above 65%**
- Evaluation Period: Defined monitoring interval
- Alarm State: Triggered when threshold is breached

This allows proactive detection of:

- High workload spikes
- Resource exhaustion
- Potential scaling requirements

---

### 3️⃣ SNS Notification Integration

Created and configured:

- 📩 SNS Topic
- 📬 Email subscription endpoint
- Alarm action mapped to SNS topic

When threshold is crossed:

- Alarm transitions to **ALARM state**
- SNS triggers real-time notification
- Responsible personnel are alerted immediately

---

## 📊 Monitoring & Governance Impact

✔ Real-time cost monitoring  
✔ Automated budget protection  
✔ CPU spike detection  
✔ Incident alerting automation  
✔ Operational risk reduction  
✔ Improved financial governance  

---

## 🔐 Security & Operational Benefits

- Reduces unexpected AWS billing exposure
- Enables proactive scaling decisions
- Strengthens monitoring discipline
- Supports DevOps operational maturity

---

## 🚀 Outcome

Successfully implemented a **Cost & Performance Alerting Architecture** using CloudWatch and SNS.

This enhances the **Monitoring & Governance layer** of the AWS Cloud Portfolio and demonstrates enterprise-ready alert automation capability.

---

## 🏷 Skills Demonstrated

- Amazon CloudWatch Alarms
- AWS Billing Monitoring
- EC2 Performance Monitoring
- Amazon SNS Integration
- Cloud Cost Governance
- Infrastructure Observability
- Incident Notification Automation

---

## 📸 Validation & Evidence

📄 **Execution Screenshots & Alarm Trigger Evidence**  
👉 Google Drive: *(Documentation link will be updated)*

---

## 📚 Module Reference

**Module: Introduction to IAM and CloudWatch**  
**Course: DevOps Course**  
**Program: DevOps Architect Master’s Program – Intellipaat**

---
