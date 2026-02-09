# 🔐 IAM Role-Based Access Control & Role Switching

---

## 📌 **Project Overview**

Designed and implemented an **IAM Role–based access control (RBAC)** model to provide **temporary and controlled access** to AWS resources without assigning permanent permissions to IAM users.

This assignment demonstrates how **IAM Roles and role switching** can be used to securely grant elevated privileges to specific users while maintaining strong security governance.

---

## 🏗 **Architecture Components**

- **AWS IAM Users**
- **AWS IAM Roles**
- **IAM Trust Policy**
- **Amazon VPC**
- **Amazon DynamoDB**
- **Role Switching Mechanism**

---

## 🎯 **Objective**

To design an IAM Role that:

- Grants **full access to Amazon VPC and DynamoDB**
- Allows **only specific users (user1 & user2)** to assume the role
- Enables **temporary privilege escalation**
- Improves security, monitoring, and access governance

---

## ⚙️ **Implementation Steps**

### 1️⃣ **IAM Role Creation**

- Created a custom **IAM Role**
- Attached permissions for:
  - **Full access to Amazon VPC**
  - **Full access to Amazon DynamoDB**
- Configured a **trust policy** allowing only:
  - **user1**
  - **user2**
to assume the role

---

### 2️⃣ **Restricting Role Access**

- Restricted role assumption to specific IAM users
- Prevented unauthorized users from accessing the role
- Avoided assigning permanent permissions directly to users

---

### 3️⃣ **Role Switching & Validation**

- Logged in as **user1**
- Switched from IAM user to the created role
- Verified successful role assumption
- Confirmed access to:
  - **VPC resources**
  - **DynamoDB services**

---

### 4️⃣ **Access Verification**

Validated that:

- Only **user1 and user2** can assume the role
- Other users are denied role access
- Permissions are available **only during the active role session**

---

## 🔐 **Security Configuration**

- Used **IAM Roles** instead of permanent user permissions
- Applied **least privilege principle**
- Restricted role assumption via **trust policies**
- Enabled **temporary, session-based access**
- Improved auditability and access control

---

## 📈 **Key Learning Outcomes**

- IAM Role creation and configuration
- Trust policy design
- Secure role assumption
- Role switching mechanism
- Temporary access management
- AWS security best practices

---

## 🏆 **Real-World Use Case**

IAM Roles are commonly used in:

- DevOps and cloud operations teams
- Temporary administrative access
- Secure production environments
- Cross-account access scenarios
- Compliance-driven organizations

---

## 📊 **Outcome**

Successfully implemented a **secure IAM Role** that grants controlled access to Amazon VPC and DynamoDB only to authorized users.

Validated role functionality through successful role switching and access testing.

---

## 🛠 **Skills Demonstrated**

- AWS IAM Roles
- Trust Policy Configuration
- Role-Based Access Control (RBAC)
- Secure Privilege Escalation
- Amazon VPC Access Management
- Amazon DynamoDB Permissions
- Cloud Security Best Practices

---

## 📸 **Proof of Implementation**

📄 Consolidated Assignment Execution PDF:  
👉 *https://drive.google.com/file/d/1sno3slZKdwYI2P8jLcB4fa4aKzelTrju/view?usp=drive_link*

---

## 📚 **Course Reference**

Assignment completed as part of:

**AWS Solutions Architect – DevOps Architect Master’s Program (Intellipaat)**  

Certificate available in the main repository.

