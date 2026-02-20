# 📊 CloudWatch EC2 Performance Monitoring Dashboard Implementation

## 📌 Project Overview

A centralized monitoring dashboard was implemented using Amazon CloudWatch to track real-time performance metrics of an EC2 instance.

The objective was to create visibility into compute resource utilization, specifically CPU usage and network activity, enabling proactive monitoring and operational awareness.

This implementation demonstrates observability design, metric visualization, and infrastructure monitoring best practices.

---

## 🎯 Business Requirement

XYZ Corporation required:

- Centralized monitoring for EC2 instances  
- Real-time visibility into CPU utilization  
- Monitoring of inbound and outbound network traffic  
- Quick detection of performance anomalies  

---

## 🏗 Architecture Implemented

- Amazon CloudWatch  
- EC2 instance metrics integration  
- Custom CloudWatch Dashboard  
- CPU Utilization metric visualization  
- Network In & Network Out metric visualization  

---

## ⚙️ Implementation Summary

### 1️⃣ EC2 Metric Collection

Verified that default EC2 metrics were enabled in CloudWatch, including:

- CPUUtilization  
- NetworkIn  
- NetworkOut  

These metrics are automatically published by AWS at regular intervals.

---

### 2️⃣ Dashboard Creation

Created a new CloudWatch Dashboard and added widgets to display:

- CPU Utilization graph  
- Network In traffic graph  
- Network Out traffic graph  

Configured appropriate time ranges and visualization types for clarity.

---

### 3️⃣ Instance-Level Monitoring

Selected the specific EC2 instance to monitor.

Configured metrics filtering to ensure the dashboard reflected data only for the targeted instance.

Validated metric updates in near real-time.

---

## 🔐 Security Configuration

- Monitoring configured without exposing sensitive data  
- Access to dashboard restricted through IAM policies  
- No public exposure of monitoring endpoints  
- Followed principle of least privilege for dashboard access  

---

## 📊 Outcome Achieved

- Enabled real-time infrastructure visibility  
- Improved operational monitoring capability  
- Simplified performance troubleshooting  
- Established centralized observability framework  
- Prepared environment for future alarm integration  

---

## 🛠 Skills Demonstrated

- Amazon CloudWatch Dashboard Creation  
- EC2 Performance Monitoring  
- Metric Selection and Visualization  
- Infrastructure Observability Design  
- IAM-Controlled Monitoring Access  
- AWS Operational Best Practices  

---

## 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(https://drive.google.com/file/d/1xX6Oof7YSeG633IXfzLcWHiyn_-hGdoW/view?usp=drive_link)*  

---

## 🎓 Course Reference

Module: AWS Identity and Monitoring  
Program: AWS Solutions Architect Track  
Track: Cloud Engineering & Architecture Implementation
