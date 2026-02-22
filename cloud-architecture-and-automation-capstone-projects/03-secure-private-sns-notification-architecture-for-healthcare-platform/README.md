# 🏥 Secure Private SNS Notification Architecture for Healthcare Platform

## 📌 Project Overview

A secure and private messaging architecture was implemented using Amazon SNS within a controlled Amazon VPC environment to enable confidential healthcare report distribution.

The objective was to design a platform where patient reports could be securely published and delivered through private SNS messaging, with the application hosted on EC2 inside a VPC. Infrastructure provisioning was automated using AWS CloudFormation.

This implementation demonstrates secure notification architecture, private service communication, and infrastructure-as-code deployment in a healthcare use case.

---

## 🎯 Business Requirement

The healthcare organization required:

- Secure online delivery of patient reports  
- Private message publishing mechanism  
- Mobile-accessible notification platform  
- Encrypted and controlled communication  
- Infrastructure automation using CloudFormation  

---

## 🏗 Architecture Implemented

- AWS CloudFormation (Infrastructure as Code)  
- Amazon VPC (Isolated Network Environment)  
- Amazon EC2 (Application Hosting)  
- Amazon SNS (Private Notification Service)  
- Security Groups and Network Controls  
- IAM Roles for Secure Publishing  

---

## ⚙️ Implementation Summary

### 1️⃣ VPC Infrastructure Provisioning

- Created VPC using CloudFormation template  
- Configured subnets and route tables  
- Applied security groups  
- Ensured isolated and secure networking  

---

### 2️⃣ EC2 Application Deployment

- Launched EC2 instance inside VPC  
- Hosted application responsible for report publishing  
- Configured IAM role for SNS access  
- Verified application connectivity  

---

### 3️⃣ SNS Private Messaging Configuration

- Created SNS topic  
- Restricted access via IAM policies  
- Configured secure subscription endpoints  
- Enabled encryption (if configured)  
- Published messages privately from EC2  

---

### 4️⃣ Message Validation

- Triggered report publishing event  
- Verified SNS message delivery  
- Confirmed secure transmission  
- Validated private communication within VPC  

---

## 🔐 Security Configuration

- SNS access restricted via IAM role  
- EC2 instance placed inside private VPC  
- Security groups limited inbound/outbound traffic  
- No public exposure of sensitive data  
- Enforced least privilege access  

---

## 📊 Outcome Achieved

- Successfully implemented secure healthcare notification system  
- Enabled private message publishing using SNS  
- Automated infrastructure provisioning via CloudFormation  
- Ensured controlled and encrypted message delivery  
- Built compliance-ready communication architecture  

---

## 🛠 Skills Demonstrated

- AWS CloudFormation Infrastructure Automation  
- Amazon VPC Secure Architecture Design  
- EC2 Application Hosting  
- Amazon SNS Secure Messaging  
- IAM Policy Configuration  
- Private Service Integration  
- Healthcare-Grade Cloud Security Implementation  

---

## 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(Documentation link will

---

## 🎓 Course Reference

Program: AWS Solutions Architect Track  
Track: Secure Cloud Messaging & Infrastructure Automation
