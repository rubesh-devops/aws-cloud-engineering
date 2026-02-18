# Assignment-2 – IAM Policy Design & Role-Based Access Governance Implementation

---

## 📌 Project Overview

Implemented a **role-based access control (RBAC) strategy** in AWS using custom IAM policies to enforce least privilege access across development and operations teams within XYZ Corporation.

The objective was to design **segmented access policies** aligned with business responsibilities while ensuring secure governance and controlled resource interaction.

---

## 🏢 Business Requirement

XYZ Corporation required a structured IAM policy framework that:

- Enables development teams to manage application infrastructure
- Allows operations teams to monitor resources and billing
- Prevents unauthorized modification of production infrastructure
- Follows the **Principle of Least Privilege**
- Improves visibility and access traceability

---

## 🛠 Implementation Summary

### 🔹 Custom Policy 1 – Development Infrastructure Policy

Designed a policy granting:

- ✅ Full access to Amazon S3
- ✅ Permission to create EC2 instances (restricted to instance creation only)
- ✅ Full access to Amazon RDS
- ❌ No permission to delete or modify unrelated AWS services

This policy was attached to:

> **Dev Team IAM Group**

---

### 🔹 Custom Policy 2 – Operations Monitoring Policy

Designed a policy granting:

- ✅ Full access to CloudWatch
- ✅ Full access to AWS Billing & Cost Explorer
- ✅ Read-only access to EC2 resources
- ✅ Read-only access to S3 resources
- ❌ No resource creation or deletion permissions

This policy was attached to:

> **Ops Team IAM Group**

---

## 🏗 Access Control Architecture

IAM Group-Based Access Model:

- Users inherit permissions via group membership
- Policies are attached at the group level (not directly to users)
- Simplifies scalability and user onboarding
- Enables centralized governance control

Access Distribution Model:

- Dev Team → Infrastructure deployment capabilities
- Ops Team → Monitoring and financial oversight

---

## 🔐 Security & Governance Strategy

✔ Enforced least privilege access  
✔ Separated infrastructure deployment from monitoring roles  
✔ Avoided direct policy attachment to users  
✔ Reduced risk of accidental resource deletion  
✔ Enabled audit-friendly permission structuring  

---

## 📊 Outcome

- Secure IAM governance model implemented  
- Clear separation of development and operations responsibilities  
- Scalable identity management architecture  
- Reduced blast radius of compromised credentials  
- Improved compliance posture  

---

## 🧠 Skills Demonstrated

- IAM Policy Design
- JSON-based Access Control Configuration
- Role-Based Access Control (RBAC)
- AWS Security Governance
- Identity Segmentation Strategy
- Cloud Cost Monitoring Access Structuring

---

## 📸 Validation & Evidence

📄 **Execution Documentation & Screenshots**  
👉 Google Drive: *(Documentation link will be updated)*

---

## 📚 Course Reference

Module 3 – Introduction to IAM and CloudWatch  
DevOps Course  
Part of DevOps Architect Master’s Program – Intellipaat
