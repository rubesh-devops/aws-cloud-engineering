# 🌐 S3 Static Website Hosting and Lifecycle Policy Implementation

## 📌 Problem Statement

XYZ Corporation requires a cost-effective solution to host static web content and manage long-term storage costs efficiently.

The objective is to implement static website hosting using Amazon S3 and configure lifecycle policies for cost optimization.

---

## 🎯 Implementation Objectives

- Enable static website hosting on an existing S3 bucket  
- Upload `index.html` and `error.html` pages  
- Configure lifecycle rules for automatic storage class transition  
- Implement automatic object expiration  

---

## 🏗 Architecture Components Used

- Amazon S3  
- S3 Static Website Hosting  
- Lifecycle Management Rules  
- Storage Classes (Standard → Standard-IA)  
- Object Expiration Policies  

---

## ⚙️ Execution Summary

- Enabled static website hosting on the existing S3 bucket  
- Uploaded `index.html` as default root document  
- Uploaded `error.html` as custom error document  
- Verified public website accessibility via S3 endpoint  
- Configured lifecycle rule to transition objects from:
  - **Standard → Standard-IA after 60 days**
- Configured expiration policy to:
  - **Automatically delete objects after 200 days**
- Validated lifecycle rule activation in bucket management settings  

---

## 💰 Cost Optimization Strategy

- Automated transition to lower-cost storage class  
- Implemented expiration policy to reduce long-term storage cost  
- Eliminated need for manual storage management  

---

## 🔐 Security & Governance

- Managed public access settings for website hosting  
- Applied bucket-level access controls  
- Ensured controlled public object exposure  

---

## 📈 Key Learning Outcomes

- Static website deployment using S3  
- Root and error document configuration  
- Lifecycle rule configuration  
- Storage cost optimization strategy  
- Automated data retention management  

---

## 🛠 Skills Demonstrated

- Amazon S3 Website Hosting  
- Lifecycle Rule Configuration  
- Storage Class Management  
- Cloud Cost Optimization  
- Object Expiration Strategy  

---

## 📸 Validation & Evidence

📄 **Consolidated Execution Documentation**  
👉 Google Drive: *(Documentation link will be updated)*  

---

## 📚 Course Reference

**Module:** Simple Storage Service (S3)  
**Course:** DevOps Course  
**Program:** DevOps Architect Master’s Program – Intellipaat  
