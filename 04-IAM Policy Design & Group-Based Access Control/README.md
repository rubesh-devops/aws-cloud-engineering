# 🔐 IAM Policy Design & Group-Based Access Control

---

## 📌 **Project Overview**

Designed and implemented **custom AWS IAM policies** to control access to AWS services based on team responsibilities within XYZ Corporation.

This assignment demonstrates how **fine-grained IAM policies** can be created and attached to IAM groups to enforce **role-based access control (RBAC)** and improve security governance.

---

## 🏗 **Architecture Components**

- **AWS IAM Policies**
- **AWS IAM Groups**
- **AWS Services Access Control**
  - Amazon S3
  - Amazon EC2
  - Amazon RDS
  - Amazon CloudWatch
  - AWS Billing
- **Role-Based Access Control (RBAC)**

---

## 🎯 **Objective**

To design and implement IAM policies that:

- Enforce service-level access control
- Separate permissions based on team roles
- Simplify access management using group-based policies
- Improve security visibility and monitoring

---

## ⚙️ **Implementation Steps**

### 1️⃣ **IAM Policy 1 – Dev Team Access Policy**

Created **Policy 1** with the following permissions:

- **Full access to Amazon S3**
- **Permission to create EC2 instances only**
- **Full access to Amazon RDS**

This policy is designed to support application development and database operations.

---

### 2️⃣ **IAM Policy 2 – Ops Team Access Policy**

Created **Policy 2** with the following permissions:

- **Full access to CloudWatch**
- **Full access to AWS Billing**
- **Read-only (list) access to EC2 resources**
- **Read-only (list) access to S3 resources**

This policy enables monitoring, auditing, and cost management without allowing resource modification.

---

### 3️⃣ **Policy Assignment to IAM Groups**

Attached policies to IAM groups as follows:

#### 🔹 Dev Team
- Attached **IAM Policy 1**

#### 🔹 Ops Team
- Attached **IAM Policy 2**

This ensures permissions are applied at the group level rather than individual users.

---

### 4️⃣ **Access Verification**

Validated that:

- Dev Team users can create EC2 instances and manage S3 & RDS
- Ops Team users can monitor CloudWatch and billing
- Ops Team users can only list EC2 and S3 resources
- No unauthorized access is permitted

---

## 🔐 **Security Configuration**

- Implemented **least privilege access**
- Avoided direct policy attachment to individual users
- Centralized permission control using IAM groups
- Separated operational and development responsibilities
- Followed AWS IAM best practices

---

## 📈 **Key Learning Outcomes**

- IAM policy creation and customization
- Service-level permission control
- Group-based access management
- Least privilege access enforcement
- Secure monitoring and billing access
- IAM policy testing and validation

---

## 🏆 **Real-World Use Case**

This access model is widely used in:

- Enterprise DevOps teams
- Organizations with Dev & Ops separation
- Secure production environments
- Cost and usage monitoring teams
- Compliance-driven cloud infrastructures

---

## 📊 **Outcome**

Successfully implemented **two custom IAM policies** and enforced group-based access control that:

- Restricts access based on role
- Improves security and visibility
- Simplifies permission management
- Scales easily with new users

---

## 🛠 **Skills Demonstrated**

- AWS IAM Policies
- Identity & Access Management
- Role-Based Access Control (RBAC)
- Cloud Security Best Practices
- Permission Boundary Design
- AWS Service Access Governance

---

## 📸 **Proof of Implementation**

📄 Consolidated Assignment Execution PDF:  
👉 *https://drive.google.com/file/d/1dMjlECwSiZUEQNknesvhMlEPw0maCmdh/view?usp=drive_link*

---

## 📚 **Course Reference**

Assignment completed as part of:

**AWS Solutions Architect – DevOps Architect Master’s Program (Intellipaat)**  

Certificate available in the main repository.
