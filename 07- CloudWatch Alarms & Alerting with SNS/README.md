# 🚨 CloudWatch Alarms & Alerting with SNS

---

## 📌 **Project Overview**

Designed and implemented **Amazon CloudWatch Alarms** to proactively monitor **cost usage and EC2 performance**, ensuring early detection of abnormal behavior, misconfigurations, and budget overruns.

This assignment demonstrates how **alerts and notifications** can be configured using CloudWatch and Amazon SNS to maintain operational and financial control in AWS environments.

---

## 🏗 **Architecture Components**

- **Amazon CloudWatch**
- **CloudWatch Alarms**
- **Amazon EC2**
- **AWS Billing Metrics**
- **Amazon SNS (Simple Notification Service)**
- **Email Notifications**

---

## 🎯 **Objective**

To implement an alerting solution that:

- Monitors **AWS billing charges** to avoid unexpected cost overruns  
- Tracks **EC2 CPU utilization** to detect performance issues  
- Sends **real-time notifications** when thresholds are breached  
- Improves operational awareness and cost governance  

---

## ⚙️ **Implementation Steps**

### 1️⃣ **CloudWatch Billing Alarm Creation**

- Enabled **AWS Billing metrics**
- Created a **CloudWatch Billing Alarm**
- Configured alarm condition:
  - Trigger when **Estimated Charges exceed $500**
- Set alarm to transition to **ALARM state** when threshold is crossed

---

### 2️⃣ **EC2 CPU Utilization Alarm**

- Selected a running **EC2 instance**
- Created a **CloudWatch Alarm** for:
  - **CPU Utilization > 65%**
- Configured evaluation period and datapoints
- Ensured alarm triggers accurately during high CPU usage

---

### 3️⃣ **SNS Topic & Notification Setup**

- Created an **SNS topic**
- Subscribed an **email endpoint** to the topic
- Integrated SNS topic with the EC2 CPU alarm
- Verified notification delivery when alarm state changes

---

### 4️⃣ **Alarm Validation**

Validated that:

- Billing alarm triggers when cost threshold is crossed
- CPU alarm enters **ALARM state** when utilization exceeds 65%
- SNS notifications are delivered successfully
- Alarms reset automatically when conditions normalize

---

## 🔐 **Security & Monitoring Configuration**

- Used **read-only monitoring metrics**
- Avoided direct access to billing modification settings
- Implemented alerting without impacting workloads
- Followed AWS monitoring and alerting best practices

---

## 📈 **Key Learning Outcomes**

- CloudWatch alarm configuration
- Billing and cost monitoring in AWS
- EC2 performance threshold management
- SNS-based alerting and notifications
- Proactive incident detection
- Cloud cost governance and observability

---

## 🏆 **Real-World Use Case**

CloudWatch alarms with SNS are widely used in:

- Production monitoring environments
- Cost control and budget enforcement
- Incident response systems
- DevOps and SRE operations
- Performance anomaly detection
- Compliance-driven organizations

---

## 📊 **Outcome**

Successfully implemented **cost and performance monitoring alarms** that:

- Alert when AWS spending exceeds defined limits
- Notify stakeholders during EC2 performance spikes
- Enable proactive response to operational issues
- Improve overall cloud governance and reliability

---

## 🛠 **Skills Demonstrated**

- Amazon CloudWatch Alarms
- AWS Billing & Cost Monitoring
- EC2 Performance Monitoring
- Threshold-Based Alerting
- Amazon SNS Integration
- Cloud Observability
- AWS Monitoring Best Practices

---

## 📸 **Proof of Implementation**

📄 Consolidated Assignment Execution PDF:  
👉 *https://drive.google.com/file/d/1kDjlPuI6cZNd5YQg_v90UEeRevoyi9pI/view?usp=drive_link*

---

## 📚 **Course Reference**

Assignment completed as part of:

**AWS Solutions Architect – DevOps Architect Master’s Program (Intellipaat)**  

Certificate available in the main repository.
