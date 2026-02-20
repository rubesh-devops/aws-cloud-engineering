# 🏗 CloudFormation S3 Bucket Provisioning and Versioning Automation

## 📌 Project Overview

An Infrastructure-as-Code (IaC) solution was implemented using AWS CloudFormation to automate the provisioning of Amazon S3 storage resources.

The objective was to create a reusable CloudFormation template capable of deploying an S3 bucket with versioning enabled, ensuring consistent infrastructure deployment across development, testing, and production environments.

This implementation demonstrates automated resource provisioning, configuration standardization, and storage governance using declarative templates.

---

## 🎯 Business Requirement

XYZ Corporation required:

- Automated and repeatable infrastructure deployment  
- Standardized S3 bucket creation across environments  
- Built-in version control for object protection  
- Infrastructure-as-Code implementation  

---

## 🏗 Architecture Implemented

- AWS CloudFormation Template  
- Amazon S3 Bucket Resource  
- Versioning Configuration Enabled  
- Parameterized Naming Convention  
- Stack-Based Deployment Model  

---

## ⚙️ Implementation Summary

### 1️⃣ CloudFormation Template Design

- Created YAML/JSON template  
- Defined `AWS::S3::Bucket` resource  
- Configured bucket name as:
  `Intellipaat-<yourname>`  
- Added VersioningConfiguration block  
- Ensured template validation before deployment  

---

### 2️⃣ Stack Deployment

- Uploaded template to CloudFormation  
- Created stack with defined bucket name  
- Monitored stack creation events  
- Validated successful
