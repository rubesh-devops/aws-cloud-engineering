# ☁️ S3 Versioning, Lifecycle Management and Static Website Hosting with Domain Integration

## 📌 Business Scenario

XYZ Corporation requires a highly durable, scalable and publicly accessible storage solution to host application assets and static web content.

The organization also needs:

- Automatic data lifecycle management  
- Version recovery capability  
- Public website hosting using custom domain  
- Custom error handling  

This implementation ensures scalable storage, version protection and production-grade website hosting.

---

## 🎯 Implementation Objectives

- Store unlimited data securely on Amazon S3  
- Enable versioning for data recovery  
- Configure lifecycle policy for automatic deletion after 75 days  
- Host static website using S3  
- Integrate custom domain (Route 53)  
- Configure custom error page handling  

---

## 🏗 Architecture Components Used

- Amazon S3  
- S3 Versioning  
- Lifecycle Policies  
- S3 Static Website Hosting  
- Route 53 Hosted Zone  
- Custom Domain Mapping  
- Error Document Configuration  

---

## ⚙️ Execution Summary

### 1️⃣ Scalable Cloud Storage Implementation
- Created S3 bucket for application storage  
- Enabled public accessibility for website hosting  
- Verified global access capability  

### 2️⃣ Versioning for Data Protection
- Enabled S3 Versioning  
- Uploaded multiple versions of same file  
- Retrieved older version to simulate accidental overwrite recovery  
- Verified version restore functionality  

### 3️⃣ Lifecycle Management
- Configured lifecycle rule:
  - Automatically delete objects after **75 days**
- Ensured cost optimization and automated storage cleanup  
- Verified lifecycle rule activation  

### 4️⃣ Static Website Hosting
- Enabled S3 Static Website Hosting  
- Uploaded:
  - `index.html` (default page)
  - `error.html` (custom error page)  
- Validated website accessibility via S3 endpoint  

### 5️⃣ Custom Domain Integration
- Used Route 53 hosted zone created in Module 3  
- Mapped domain name to S3 website endpoint  
- Verified domain-based access  

### 6️⃣ Error Handling Configuration
- Configured custom error page  
- Ensured invalid domain access displays `error.html`  
- Validated DNS and website routing behavior  

---

## 🔐 Security & Governance Controls

- Managed bucket policies for public website hosting  
- Applied access controls at bucket level  
- Enabled version protection for accidental deletion  
- Implemented automated retention enforcement  

---

## 📈 Key Learning Outcomes

- S3 Versioning and Data Recovery  
- Lifecycle Rule Automation  
- Static Website Hosting on S3  
- Route 53 Domain Integration  
- Custom Error Page Configuration  
- Cloud Storage Scalability Design  
- Cost Optimization Strategy  

---

## 🛠 Skills Demonstrated

- Amazon S3 Configuration  
- Data Version Management  
- Lifecycle Policy Automation  
- DNS Routing with Route 53  
- Static Web Hosting Architecture  
- Cloud Governance & Cost Control  

---

## 📸 Validation & Evidence

📄 **Consolidated Execution Documentation**  
👉 Google Drive: *(Documentation link will be updated)*  

---

## 📚 Course Reference

**Module:** Simple Storage Service (S3)  
**Course:** DevOps Course  
**Program:** DevOps Architect Master’s Program – Intellipaat  
