# AWS CodeCommit Private Repository Migration

## 📌 Project Overview

XYZ Corporation required a secure and private code repository within AWS to manage application source code. As part of the AWS DevOps implementation, the existing GitHub repository was migrated into AWS CodeCommit to ensure centralized, secure, and controlled version management within the AWS ecosystem.

This implementation demonstrates secure repository management and Git-based DevOps workflow integration inside AWS Cloud.

---

## 🎯 Objective

Migrate existing GitHub repository content into a private AWS CodeCommit repository to:

- Secure source code within AWS
- Enable IAM-based access control
- Prepare repository for CI/CD pipeline integration
- Establish AWS-native version control management

---

## 🏗️ Architecture Summary

- AWS CodeCommit (Private Repository)
- GitHub (Source Repository)
- IAM-based authentication
- Git CLI for repository cloning and push

---

## ⚙️ Implementation Summary

### 1️⃣ CodeCommit Repository Creation

- Created a private AWS CodeCommit repository.
- Configured IAM user with required permissions.
- Enabled HTTPS Git credentials for secure access.

### 2️⃣ GitHub Repository Migration

- Cloned the existing GitHub repository locally.
- Reconfigured remote origin to AWS CodeCommit.
- Pushed complete repository history and content to CodeCommit.

### 3️⃣ Validation

- Verified repository files in AWS Console.
- Confirmed commit history integrity.
- Ensured private access enforcement via IAM.

---

## 🔐 Security & Access Control

- Repository access restricted via IAM policies.
- Enforced secure authentication using AWS credentials.
- Removed public GitHub dependency for production code storage.

---

## 🚀 DevOps Impact

- Established private source control within AWS ecosystem.
- Enabled integration with AWS CodeBuild, CodeDeploy, and CodePipeline.
- Improved governance and auditability using AWS IAM and CloudTrail.

---

## 📊 Outcome

- Successfully migrated public GitHub repository to private AWS CodeCommit.
- Secured application source code within AWS infrastructure.
- Prepared foundation for CI/CD automation using AWS DevOps services.

---

## 📸 Validation & Evidence

📄 **Consolidated Execution Documentation**  
👉 Google Drive: (Documentation link will be updated)

---

## 🎓 Course Reference

DevOps Course  
DevOps Architect Master’s Program – Intellipaat  
AWS DevOps Module
