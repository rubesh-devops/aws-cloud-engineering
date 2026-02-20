# 🏗 CloudFormation VPC and EC2 Infrastructure Automation

## 📌 Project Overview

An Infrastructure-as-Code (IaC) solution was implemented using AWS CloudFormation to automate the provisioning of networking and compute resources.

The objective was to design a reusable template capable of deploying a Virtual Private Cloud (VPC), a public subnet, and an Amazon Linux EC2 instance tagged appropriately.

This implementation demonstrates automated infrastructure provisioning, standardized network architecture deployment, and repeatable environment creation.

---

## 🎯 Business Requirement

XYZ Corporation required:

- Repeatable network architecture deployment  
- Standardized VPC and subnet creation  
- Automated EC2 provisioning  
- Infrastructure consistency across environments  
- Tag-based resource identification  

---

## 🏗 Architecture Implemented

- AWS CloudFormation Template  
- Amazon VPC  
- Public Subnet  
- Internet Gateway (if configured)  
- Route Table Association  
- Amazon Linux EC2 Instance  
- Resource Tag: `CFinstance`  

---

## ⚙️ Implementation Summary

### 1️⃣ CloudFormation Template Design

- Created YAML/JSON template  
- Defined `AWS::EC2::VPC` resource  
- Defined `AWS::EC2::Subnet` (Public Subnet)  
- Configured CIDR blocks  
- Added Internet Gateway and route table (if required)  
- Defined `AWS::EC2::Instance` resource  
- Selected Amazon Linux AMI  
- Added tag: `Name = CFinstance`  

---

### 2️⃣ Stack Deployment

- Uploaded template to CloudFormation  
- Created stack  
- Monitored stack events  
- Validated successful creation of:
  - VPC  
  - Public Subnet  
  - EC2 Instance  

---

### 3️⃣ Validation

- Verified EC2 instance launched in public subnet  
- Confirmed tag `CFinstance` applied  
- Validated instance network configuration  
- Tested instance reachability (if public IP enabled)  

---

## 🔐 Security Configuration

- Applied Security Group for controlled access  
- Restricted inbound SSH (Port 22) as needed  
- Ensured least privilege network access  
- Maintained isolated VPC environment  

---

## 📊 Outcome Achieved

- Successfully automated VPC provisioning  
- Deployed EC2 instance via Infrastructure-as-Code  
- Ensured consistent environment creation  
- Reduced manual provisioning errors  
- Demonstrated scalable infrastructure automation  

---

## 🛠 Skills Demonstrated

- AWS CloudFormation Template Design  
- Infrastructure-as-Code (IaC)  
- VPC Architecture Automation  
- EC2 Deployment Automation  
- Networking Configuration  
- Resource Tagging Strategy  
- Stack Monitoring and Validation  

---

## 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(Documentation link will be updated)*  

---

## 🎓 Course Reference

Program: AWS Solutions Architect Track  
Track: Cloud Engineering & Architecture Implementation
