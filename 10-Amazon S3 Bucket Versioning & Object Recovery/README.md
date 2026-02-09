# 🗂️ Amazon S3 Bucket Versioning & Object Recovery

---

## 📌 **Project Overview**

Designed and implemented **Amazon S3 bucket versioning** to protect application data against **accidental overwrites and deletions**.

This assignment demonstrates how S3 versioning enables **object-level change tracking**, improves data durability, and supports recovery of previous object versions—critical for production storage systems.

---

## 🏗 **Architecture Components**

- **Amazon S3**
- **S3 Bucket Versioning**
- **Versioned S3 Objects**
- **Object Metadata & History**

---

## 🎯 **Objective**

To enhance an existing S3 storage solution by:

- Enabling **bucket-level versioning**
- Maintaining **multiple versions of objects**
- Verifying version creation through re-uploads
- Improving data protection and recoverability

---

## ⚙️ **Implementation Steps**

### 1️⃣ **Enable S3 Bucket Versioning**

- Selected the existing **Amazon S3 bucket**
- Enabled **Bucket Versioning**
- Verified versioning status as **Enabled**

---

### 2️⃣ **Object Re-Upload & Version Creation**

- Re-uploaded **two existing objects** to the same bucket
- Confirmed that new versions were created for each object
- Verified multiple object versions using the S3 console

---

### 3️⃣ **Version Validation**

- Checked **Version ID** for each object
- Confirmed previous versions are retained
- Validated ability to access older versions if required

---

## 🔐 **Security & Data Protection Configuration**

- Enabled versioning to protect against accidental data loss
- Ensured object history is preserved
- Maintained access control at bucket and object level
- Followed AWS data durability best practices

---

## 📈 **Key Learning Outcomes**

- S3 bucket versioning concepts
- Object version lifecycle management
- Data protection and recovery strategies
- Handling object overwrites safely
- AWS storage durability mechanisms

---

## 🏆 **Real-World Use Case**

S3 versioning is widely used in:

- Production application storage
- Data recovery and rollback scenarios
- Compliance and audit requirements
- Backup and archival systems
- Collaboration environments with frequent updates

---

## 📊 **Outcome**

Successfully enabled **S3 bucket versioning** and verified correct behavior by creating multiple versions of existing objects.

Improved data safety by ensuring previous object versions remain accessible after updates.

---

## 🛠 **Skills Demonstrated**

- Amazon S3 Versioning
- Object Lifecycle Management
- Data Protection & Recovery
- Cloud Storage Best Practices
- AWS Storage Governance

---

## 📸 **Proof of Implementation**

📄 Consolidated Assignment Execution PDF:  
👉 *https://drive.google.com/file/d/1LKgqCpQIjcOfVHA013ZdJXBAyfUbS_rZ/view?usp=drive_link*

---

## 📚 **Course Reference**

Assignment completed as part of:

**AWS Solutions Architect – DevOps Architect Master’s Program (Intellipaat)**  

Certificate available in the main repository.
