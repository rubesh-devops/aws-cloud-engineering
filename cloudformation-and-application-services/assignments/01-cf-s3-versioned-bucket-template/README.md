# ☁️ CloudFormation – Versioned S3 Bucket Template Automation

## 📌 Project Overview

As part of infrastructure standardization at XYZ Corporation, the requirement was to automate repetitive environment creation across Development, Testing, and Production.

To eliminate manual S3 bucket provisioning and ensure consistent configuration, AWS CloudFormation was used to create a reusable infrastructure template.

This project demonstrates Infrastructure as Code (IaC) principles by automating S3 bucket creation with versioning enabled.

---

## 🎯 Business Objective

Deploy a reusable CloudFormation template that:

- Creates an S3 bucket named:
  Intellipaat-<yourname>
- Automatically enables Versioning
- Can be reused across multiple environments
- Ensures consistent configuration across teams

---

## 🏗 Architecture Components

- AWS CloudFormation
- Amazon S3
- S3 Versioning
- Stack Lifecycle Management

---

## ⚙️ Implementation Strategy

### 1️⃣ Infrastructure as Code Approach

- Created CloudFormation template in YAML format
- Defined S3 bucket as a managed resource
- Enabled Versioning configuration within the template
- Parameterized bucket naming for environment flexibility

---

### 2️⃣ Versioning Configuration

S3 Versioning was enabled to:

- Maintain object history
- Recover accidentally deleted files
- Restore overwritten objects
- Improve data protection and compliance readiness

---

### 3️⃣ Stack Deployment Process

- Template uploaded to CloudFormation
- Stack created using template
- Resource creation verified via S3 console
- Versioning state validated

---

## 🛡 Security & Best Practices

- Infrastructure version controlled
- Repeatable environment provisioning
- Avoided manual configuration drift
- Naming standard aligned with enterprise conventions
- Stack-based deployment for audit traceability

---

## 🚀 Outcomes Achieved

- Automated S3 bucket provisioning
- Enforced versioning policy by default
- Eliminated configuration inconsistencies
- Reduced deployment time across environments
- Improved disaster recovery capability

---

## 💼 Skills Demonstrated

- Infrastructure as Code (IaC)
- AWS CloudFormation Template Design
- S3 Versioning Configuration
- Stack Deployment & Validation
- Cloud Governance Practices

---

## 📸 Validation & Evidence

📄 **Consolidated Execution Documentation**  
👉 Google Drive: *(Documentation link will be updated)*

---

## 📚 Module & Course Reference

**Module 8 – CloudFormation and App Services**  
**AWS Course**  
**Part of DevOps Architect Master’s Program – Intellipaat**
