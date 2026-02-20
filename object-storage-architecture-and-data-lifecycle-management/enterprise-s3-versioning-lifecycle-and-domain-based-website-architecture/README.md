# 🌐 Enterprise S3 Versioning, Lifecycle and Domain-Based Website Architecture

## 📌 Project Overview

An enterprise-grade object storage and static website architecture was implemented using Amazon S3 with versioning, lifecycle automation, and custom domain integration.

The objective was to design a scalable cloud storage solution capable of storing unlimited data, enabling object recovery, optimizing storage lifecycle, and hosting a static website integrated with a custom domain and controlled error handling.

This implementation demonstrates production-ready S3 architecture, data governance, cost optimization, and DNS-integrated website hosting.

---

## 🎯 Business Requirement

XYZ Corporation required:

- Scalable cloud storage with unlimited capacity  
- High availability and global accessibility  
- Automated lifecycle management (auto-delete after 75 days)  
- Object version recovery capability  
- Domain-based static website hosting  
- Custom error handling for invalid access  

---

## 🏗 Architecture Implemented

- Amazon S3 Bucket  
- Versioning Enabled  
- Lifecycle Policy (75-Day Expiration)  
- Static Website Hosting Configuration  
- Custom Domain Integration (Route 53)  
- Custom Error Page Configuration  
- Bucket Policy for Controlled Public Access  

---

## ⚙️ Implementation Summary

### 1️⃣ Scalable Object Storage Implementation

- Created/used S3 bucket with globally unique name  
- Verified unlimited storage capability  
- Uploaded sample data for validation  
- Confirmed web-based accessibility  

---

### 2️⃣ Lifecycle Management Configuration

- Created lifecycle rule for bucket  
- Configured automatic object expiration after **75 days**  
- Applied rule to entire bucket  
- Validated lifecycle status  

---

### 3️⃣ Versioning Enablement and Recovery Validation

- Enabled S3 Versioning  
- Uploaded modified version of an existing file  
- Verified multiple version IDs  
- Successfully restored previous object version  

---

### 4️⃣ Static Website Hosting with Custom Domain

- Enabled static website hosting  
- Configured:
  - Index document (`index.html`)
  - Error document (`error.html`)  
- Updated bucket policy for public read access  
- Integrated custom domain from Route 53  
- Created DNS record pointing to S3 website endpoint  

---

### 5️⃣ Error Handling Validation

- Configured custom error page  
- Tested invalid domain access  
- Confirmed error page display behavior  

---

## 🔐 Security Configuration

- Applied least privilege bucket policies  
- Enabled versioning for data protection  
- Implemented automated lifecycle governance  
- Restricted write permissions  
- Controlled public access for static content  

---

## 📊 Outcome Achieved

- Designed scalable and durable cloud storage architecture  
- Enabled automated lifecycle management  
- Implemented object recovery mechanism  
- Hosted static website with custom domain  
- Integrated error handling for secure access  
- Built production-ready S3 solution  

---

## 🛠 Skills Demonstrated

- Amazon S3 Architecture Design  
- S3 Versioning and Object Recovery  
- Lifecycle Policy Configuration  
- Static Website Hosting  
- Route 53 DNS Integration  
- Bucket Policy Management  
- Cloud Storage Governance  
- Cost Optimization Strategy  

---

## 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(Documentation link will be updated)*  

---

## 🎓 Course Reference

Program: AWS Solutions Architect Track  
Track: Cloud Engineering & Architecture Implementation
