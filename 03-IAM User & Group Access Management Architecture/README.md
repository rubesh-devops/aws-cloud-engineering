# 🔐 IAM User & Group Access Management Architecture

---

## 📌 **Project Overview**

Designed and implemented a structured **AWS Identity and Access Management (IAM)** model to organize and monitor users efficiently within an AWS account.

This assignment demonstrates user segmentation using IAM Users and IAM Groups to enforce structured access control and improve security governance.

---

## 🏗 **Architecture Components**

- **AWS IAM Users**
- **AWS IAM Groups**
- **User-Group Mapping**
- **Role-Based Access Control (RBAC)**

---

## 🎯 **Objective**

To design an IAM structure that:

- Organizes users based on functional roles
- Simplifies permission management using groups
- Enhances account security and visibility
- Follows **Least Privilege Access Principles**

---

## ⚙️ **Implementation Steps**

### 1️⃣ **IAM User Creation**

Created four IAM users:

- **Dev1**
- **Dev2**
- **Test1**
- **Test2**

Each user represents a team member within the organization.

---

### 2️⃣ **IAM Group Creation**

Created two IAM groups:

- **Dev Team**
- **Ops Team**

Groups allow centralized permission management instead of assigning policies directly to individual users.

---

### 3️⃣ **User-Group Association**

Configured group membership as follows:

#### 🔹 Dev Team
- Dev1  
- Dev2  

#### 🔹 Ops Team
- Dev1  
- Test1  
- Test2  

This demonstrates **multi-group membership**, where Dev1 belongs to both teams.

---

### 4️⃣ **Validation**

Verified:

- Users are correctly assigned to respective groups
- IAM console reflects proper group associations
- Group-based management simplifies monitoring

---

## 🔐 **Security Configuration**

- Centralized access control using IAM Groups  
- Avoided direct policy attachment to users  
- Implemented structured access governance  
- Designed according to AWS security best practices  

---

## 📈 **Key Learning Outcomes**

- IAM user lifecycle management  
- Role-Based Access Control (RBAC)  
- Multi-group membership configuration  
- AWS account security governance  
- Structured cloud access management  

---

## 🏆 **Real-World Use Case**

This IAM model is commonly used in:

- Software development teams (Dev vs Ops segregation)  
- Enterprises implementing least privilege access  
- Multi-team cloud projects  
- Organizations requiring structured access auditing  

---

## 📊 **Outcome**

Successfully implemented a structured IAM user-group hierarchy that enables:

- Organized access control  
- Simplified permission management  
- Scalable user governance  
- Improved cloud security visibility  

---

## 🛠 **Skills Demonstrated**

- AWS IAM  
- Identity & Access Management  
- Role-Based Access Control (RBAC)  
- Cloud Security Architecture  
- User Segmentation Strategy  

---

## 📸 **Proof of Implementation**

📄 Consolidated Assignment Execution PDF:  
👉 *https://drive.google.com/file/d/1uAzTeiNNxVDZY5H-modZEM_xudRbo44w/view?usp=drive_link*

---

## 📚 **Course Reference**

Assignment completed as part of:  

**AWS Solutions Architect – DevOps Architect Master’s Program (Intellipaat)**  

Certificate available in the main repository.
