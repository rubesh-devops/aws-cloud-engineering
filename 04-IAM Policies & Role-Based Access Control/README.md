## 🔐 Assignment: IAM Policies & Role-Based Access Control (AWS)

### 📌 Objective
Design and implement **secure IAM policies** to manage **user access, monitoring, and cost visibility** across different teams using **AWS IAM best practices**.

---

### 🛠 Tools & Services Used
- **AWS IAM**
- **Amazon S3**
- **Amazon EC2**
- **Amazon RDS**
- **Amazon CloudWatch**
- **AWS Billing & Cost Management**

---

### 🔧 Implementation Overview
- Created **custom IAM policies** based on team responsibilities
- Implemented **least privilege access** using IAM groups
- Segregated **resource creation** and **monitoring/billing** access
- Attached policies at the **group level** for scalability and maintainability

---

### 📄 IAM Policy Design

#### 🟢 Policy 1 – Development Team Access
**Assigned To:** Dev Team  

**Permissions:**
- **Full access to Amazon S3**
- **Permission to create EC2 instances only**
- **Full access to Amazon RDS**

**Purpose:**  
Enable developers to provision and manage application resources while maintaining controlled access.

---

#### 🔵 Policy 2 – Operations Team Access
**Assigned To:** Ops Team  

**Permissions:**
- **Full access to Amazon CloudWatch**
- **Full access to AWS Billing & Cost Management**
- **Read-only (list) access to Amazon EC2 and Amazon S3**

**Purpose:**  
Allow operations team to monitor infrastructure health and costs without modifying resources.

---

### 🏗 Architecture & Access Flow
- IAM users assigned to **Dev Team** and **Ops Team**
- Policies attached to **IAM groups** (not individual users)
- Centralized permission management with improved auditability
- Clear separation between **development** and **operations** responsibilities

---

### 📈 Outcome & Key Learnings
- Implemented **real-world RBAC (Role-Based Access Control)** using AWS IAM
- Improved **security posture** through least privilege principles
- Learned **policy design and enforcement** in production-like environments
- Gained hands-on experience with **IAM governance and access control**

---

### 🧠 Skills Demonstrated (ATS-Friendly)
- **AWS IAM**
- **IAM Policies & Groups**
- **Role-Based Access Control (RBAC)**
- **Cloud Security Best Practices**
- **Least Privilege Access**
- **Monitoring & Cost Governance**

---

### 📸 Proof of Work
- IAM policy JSON files  
- Screenshots of policy creation and attachment  
- Access validation using test users  
- *https://drive.google.com/file/d/1dMjlECwSiZUEQNknesvhMlEPw0maCmdh/view?usp=drive_link* Google Drive documentation link
