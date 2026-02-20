# 🌍 S3 Static Website Hosting and Lifecycle Policy Implementation

## 📌 Project Overview

A static website hosting solution was implemented using Amazon S3 along with automated lifecycle management to optimize storage costs.

The objective was to configure an existing S3 bucket for static website hosting, upload custom web pages, and apply lifecycle rules to transition and expire objects automatically.

This implementation demonstrates cloud-based website hosting, cost optimization strategy, and automated storage lifecycle management.

---

## 🎯 Business Requirement

XYZ Corporation required:

- Public hosting of static website content  
- Custom index and error handling pages  
- Automated storage cost optimization  
- Data lifecycle governance  

---

## 🏗 Architecture Implemented

- Amazon S3 Bucket (Existing)  
- Static Website Hosting Enabled  
- `index.html` (Main Page)  
- `error.html` (Error Page)  
- Lifecycle Rule Configuration  

---

## ⚙️ Implementation Summary

### 1️⃣ Static Website Hosting Configuration

- Enabled **Static Website Hosting** on existing S3 bucket  
- Configured:
  - Index document: `index.html`
  - Error document: `error.html`  
- Uploaded website files  
- Verified public endpoint URL access  

---

### 2️⃣ Public Access Configuration

- Updated bucket policy to allow public read access  
- Reviewed Block Public Access settings  
- Validated website accessibility via S3 endpoint  

---

### 3️⃣ Lifecycle Policy Configuration

Configured lifecycle rule:

- Transition from **S3 Standard** to **Standard-IA** after **60 days**  
- Expire objects automatically after **200 days**  
- Applied rule to entire bucket  

Validated lifecycle rule status after configuration.

---

## 🔐 Security Configuration

- Enabled controlled public read access  
- Maintained restricted write permissions  
- Applied lifecycle management for governance  
- Avoided unnecessary broad access policies  

---

## 📊 Outcome Achieved

- Successfully hosted static website using S3  
- Implemented custom index and error handling  
- Applied automated storage transition policy  
- Reduced long-term storage costs  
- Demonstrated cost-optimized cloud hosting solution  

---

## 🛠 Skills Demonstrated

- Amazon S3 Static Website Hosting  
- Bucket Policy Configuration  
- Public Access Management  
- Lifecycle Rule Implementation  
- Storage Cost Optimization  
- Cloud-Based Web Hosting Architecture  

---

## 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(https://drive.google.com/file/d/1EDJ1Q6iBTeb7tBX0GjGd6JS01VC3Sf2I/view?usp=drive_link)*  

---

## 🎓 Course Reference

Program: AWS Solutions Architect Track  
Track: Cloud Engineering & Architecture Implementation
