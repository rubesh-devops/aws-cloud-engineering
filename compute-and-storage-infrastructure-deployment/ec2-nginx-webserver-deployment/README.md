# 🖥️ EC2 Ubuntu Web Server Deployment with NGINX & Custom Web Page Configuration

## 📌 Project Overview

As part of AWS compute infrastructure implementation, an Amazon EC2 instance was provisioned in the US-East-1 (N. Virginia) region using Ubuntu OS.  

The objective was to deploy a web server using NGINX and customize the default web page to display a business-specific message.

This implementation demonstrates cloud-based virtual machine provisioning, web server configuration, and application hosting using AWS EC2.

---

## 🎯 Business Requirement

XYZ Corporation required:

- Deployment of a web-based application on AWS
- Ubuntu-based virtual machine provisioning
- Web server installation and configuration
- Custom web page deployment displaying “Hello World”
- Public accessibility for end users

---

## 🏗 Architecture Implemented

- Amazon EC2 (Ubuntu OS)
- NGINX Web Server
- Security Group allowing HTTP (Port 80) and SSH (Port 22)
- Public IP-based web access
- VPC default networking configuration (US-East-1)

---

## ⚙️ Implementation Summary

### 1️⃣ EC2 Instance Provisioning

- Launched an Ubuntu EC2 instance in US-East-1 (N. Virginia)
- Selected appropriate instance type
- Configured key pair for SSH access
- Configured security group:
  - Port 22 (SSH) for administrative access
  - Port 80 (HTTP) for web traffic
- Verified instance status and connectivity

---

### 2️⃣ NGINX Web Server Installation

- Connected to EC2 instance via SSH
- Installed NGINX web server
- Started and enabled NGINX service
- Verified successful installation by accessing public IP in browser

---

### 3️⃣ Custom Web Page Configuration

- Modified default NGINX index page
- Replaced default content with:

  **“Hello World”**

- Restarted NGINX service
- Validated updated web page through browser access

---

## 🔐 Security Configuration

- SSH access restricted via key-based authentication
- HTTP access allowed for public users
- No unnecessary ports exposed
- Default VPC isolation maintained
- IAM access controlled at account level

---

## 📊 Outcome Achieved

- Successfully deployed Ubuntu EC2 instance
- Installed and configured NGINX web server
- Hosted a customized web page
- Validated external web accessibility
- Demonstrated cloud-based web server deployment capability

---

## 🛠 Skills Demonstrated

- Amazon EC2 Provisioning
- Ubuntu Server Configuration
- NGINX Installation & Configuration
- Security Group Configuration
- Public Web Hosting on AWS
- Cloud Compute Architecture Fundamentals

---

## 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(Documentation link will be updated)*

---

## 🎓 Course Reference

Module: Introduction to EC2, EBS, EFS and Amazon FSx  
Program: AWS Solutions Architect Course  
Track: DevOps Architect Master’s Program – Intellipaat
