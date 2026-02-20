# 🚨 CloudWatch Billing and EC2 CPU Alarm with SNS Notification Implementation

## 📌 Project Overview

A proactive monitoring and alerting mechanism was implemented using Amazon CloudWatch and Amazon SNS to track infrastructure costs and EC2 performance thresholds.

The objective was to configure automated alarms that trigger notifications when predefined billing and CPU utilization thresholds are exceeded.

This implementation demonstrates cost governance, performance monitoring, and real-time alert automation within AWS.

---

## 🎯 Business Requirement

XYZ Corporation required:

- Automated monitoring of AWS estimated billing charges  
- Real-time alerting for high EC2 CPU utilization  
- Immediate notification to responsible personnel  
- Prevention of unexpected cost overruns and performance degradation  

---

## 🏗 Architecture Implemented

- Amazon CloudWatch Alarms  
- AWS Billing Metrics Integration  
- EC2 CPU Utilization Monitoring  
- Amazon SNS Topic for notifications  
- Email subscription for alert delivery  

---

## ⚙️ Implementation Summary

### 1️⃣ Billing Alarm Configuration

Enabled billing metrics in AWS and created a CloudWatch alarm with:

- Metric: EstimatedCharges  
- Threshold: Greater than $500  
- Evaluation Period: Defined monitoring interval  
- Action: Trigger SNS notification  

This ensures financial visibility and cost control.

---

### 2️⃣ EC2 CPU Utilization Alarm

Created a CloudWatch alarm for a specific EC2 instance:

- Metric: CPUUtilization  
- Threshold: Greater than 65%  
- Statistic: Average  
- Evaluation Period: Configured monitoring window  
- Alarm State: Triggered when threshold exceeded  

This enables proactive performance management.

---

### 3️⃣ SNS Notification Setup

- Created an SNS Topic  
- Subscribed email endpoint  
- Attached SNS topic as alarm action  
- Confirmed subscription via email  
- Validated notification triggering mechanism  

---

## 🔐 Security Configuration

- Restricted SNS topic access through IAM policies  
- Controlled alarm configuration permissions  
- No public exposure of monitoring endpoints  
- Applied least privilege access model  

---

## 📊 Outcome Achieved

- Implemented automated cost monitoring  
- Enabled real-time EC2 performance alerting  
- Reduced risk of unexpected billing spikes  
- Improved operational response time  
- Established event-driven monitoring architecture  

---

## 🛠 Skills Demonstrated

- Amazon CloudWatch Alarm Configuration  
- AWS Billing Metric Monitoring  
- EC2 Performance Monitoring  
- SNS Topic Creation and Subscription  
- Event-Driven Alert Automation  
- Cost Governance Implementation  

---

## 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(https://drive.google.com/file/d/1kDjlPuI6cZNd5YQg_v90UEeRevoyi9pI/view?usp=drive_link)*  

---

## 🎓 Course Reference

Module: AWS Identity and Monitoring  
Program: AWS Solutions Architect Track  
Track: Cloud Engineering & Architecture Implementation
