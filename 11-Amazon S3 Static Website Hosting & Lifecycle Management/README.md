# 🌐 Amazon S3 Static Website Hosting & Lifecycle Management

---

## 📌 **Project Overview**

Designed and implemented a **static website hosting solution using Amazon S3**, enabling XYZ Corporation to publicly serve application content without managing servers.

This assignment also demonstrates **S3 Lifecycle Management**, optimizing storage costs by automatically transitioning and expiring objects based on defined retention rules.

---

## 🏗 **Architecture Components**

- **Amazon S3**
- **S3 Static Website Hosting**
- **S3 Objects (HTML files)**
- **S3 Lifecycle Rules**
- **Public Access Configuration**

---

## 🎯 **Objective**

To implement an S3-based solution that:

- Hosts a **public static website**
- Serves content using `index.html` and `error.html`
- Optimizes storage costs using **lifecycle policies**
- Automates data transition and expiration

---

## ⚙️ **Implementation Steps**

### 1️⃣ **Static Website Hosting Configuration**

- Used the existing **Amazon S3 bucket**
- Enabled **Static Website Hosting**
- Configured:
  - **index.html** as the home page
  - **error.html** as the error page
- Uploaded website files to the bucket
- Verified public access to the website endpoint

---

### 2️⃣ **Public Access Setup**

- Configured bucket permissions to allow public read access
- Ensured website objects are accessible via HTTP
- Validated website accessibility using the S3 website URL

---

### 3️⃣ **Lifecycle Rule Configuration**

Created an **S3 Lifecycle Rule** with the following policies:

- **Transition objects**
  - From **Standard** to **Standard-IA** after **60 days**
- **Expire objects**
  - Automatically delete after **200 days**

This ensures cost-efficient storage management and automated data cleanup.

---

## 🔐 **Security & Cost Optimization Configuration**

- Enabled public access **only for website content**
- Followed least-privilege access principles
- Used lifecycle rules to reduce long-term storage cost
- Avoided unnecessary retention of outdated data

---

## 📈 **Key Learning Outcomes**

- Static website hosting using Amazon S3
- Public access configuration for S3 buckets
- Lifecycle rule creation and management
- Storage class transition strategies
- Cost optimization using S3 lifecycle policies
- Serverless web hosting concepts

---

## 🏆 **Real-World Use Case**

This architecture is commonly used for:

- Static websites and landing pages
- Documentation hosting
- Portfolio websites
- Error pages and maintenance pages
- Cost-optimized public content hosting

---

## 📊 **Outcome**

Successfully hosted a **public static website** using Amazon S3 and implemented **lifecycle rules** to transition and expire objects automatically.

Achieved a **serverless, cost-optimized, and scalable web hosting solution**.

---

## 🛠 **Skills Demonstrated**

- Amazon S3 Static Website Hosting
- Public Access Management
- HTML Content Hosting
- S3 Lifecycle Policies
- Storage Cost Optimization
- Serverless Architecture Concepts
- Cloud Storage Best Practices

---

## 📸 **Proof of Implementation**

📄 Consolidated Assignment Execution PDF:  
👉 *https://drive.google.com/file/d/1EDJ1Q6iBTeb7tBX0GjGd6JS01VC3Sf2I/view?usp=drive_link*

---

## 📚 **Course Reference**

Assignment completed as part of:

**AWS Solutions Architect – DevOps Architect Master’s Program (Intellipaat)**  

Certificate available in the main repository.
