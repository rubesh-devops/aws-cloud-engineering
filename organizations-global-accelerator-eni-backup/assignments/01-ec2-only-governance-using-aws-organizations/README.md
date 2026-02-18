# 🏢 Enterprise Governance using AWS Organizations & Service Control Policies  

## 🎯 Objective  

Implement centralized multi-account governance using AWS Organizations and enforce service-level restrictions using Service Control Policies (SCP).

---

## 🧩 Problem Statement  

You are required to:

1. Create an AWS Organization.  
2. Create 3 Organizational Units – OU1, OU2 and OU3.  
3. Attach a Service Control Policy that only allows EC2 access.  

---

## 🏗 Architecture Overview  

- AWS Organization (All Features Enabled)  
- 3 Organizational Units (OU1, OU2, OU3)  
- Service Control Policy (EC2-Only Access)  
- Centralized Governance Model  

---

## 🛠 Implementation Execution  

### 1️⃣ Organization Setup  

- Created AWS Organization with **All Features Enabled**  
- Established centralized governance model  

---

### 2️⃣ Organizational Units Design  

- Created:
  - OU1  
  - OU2  
  - OU3  
- Structured multi-account hierarchy  

---

### 3️⃣ Service Control Policy Implementation  

- Created SCP named **EC2-Only-Access**  
- Allowed actions: `ec2:*`  
- Denied implicit access to all other AWS services  
- Attached SCP to OU1, OU2 and OU3  

---

### 4️⃣ Governance Validation  

- Verified EC2 service accessibility  
- Confirmed restricted access to S3, RDS, and other services  
- Ensured enforcement at Organizational Unit level  

---

## 🏆 Outcome  

- Implemented centralized multi-account governance  
- Enforced service-level restrictions using SCP  
- Designed enterprise-grade AWS Organization hierarchy  
- Strengthened cloud security posture  

---

## 🧠 Key Skills Demonstrated  

- AWS Organizations  
- Organizational Units (OU)  
- Service Control Policies (SCP)  
- Multi-Account Governance  
- Enterprise Cloud Security Architecture  

---

## 📸 Validation & Evidence  

📄 **Consolidated Execution Documentation**  
👉 Google Drive: *(Documentation link will be updated)*  

---

## 📚 Course Reference  

This implementation is part of:  

**Module 10 – Organizations, Global Accelerator, ENI & Backup**  
**AWS Cloud Engineering**  
**DevOps Architect Master’s Program – Intellipaat**

---

