# 🚀 EC2 Web Server Deployment using NGINX

---

## 📌 Project Context

As part of AWS infrastructure implementation for XYZ Corporation, a web-based application environment was required using Amazon EC2 virtual machines.

The objective was to deploy a production-ready web server instance in AWS and customize it to serve a static application page.

---

## 🏗 Architecture Overview

- Cloud Provider: Amazon Web Services (AWS)
- Region: US-East-1 (N. Virginia)
- Service Used: Amazon EC2
- Operating System: Ubuntu
- Web Server: NGINX
- Access: Public Internet via Security Group rules

---

## 🎯 Implementation Objectives

### ✅ 1. Launch EC2 Instance
- Deployed an Ubuntu EC2 instance
- Configured Security Group to allow HTTP (Port 80)
- Enabled public access via Internet Gateway

### ✅ 2. Install and Configure NGINX
- Installed NGINX web server on the instance
- Verified service status
- Ensured service runs on system boot

### ✅ 3. Customize Web Application
- Replaced default NGINX page
- Deployed custom static webpage displaying:

Hello World

---

## 🔐 Security & Configuration Considerations

- Controlled inbound access via Security Groups
- Allowed only required ports (SSH & HTTP)
- Used key-based authentication for secure login
- Followed least privilege principle

---

## 📈 Skills Demonstrated

- Amazon EC2 provisioning
- Linux server configuration
- Web server installation (NGINX)
- AWS Security Group configuration
- Public IP networking in AWS
- Production-style server setup

---

## 🧠 Real-World Application

This implementation reflects how organizations:

- Deploy production web servers
- Host static websites on EC2
- Rapidly provision compute infrastructure
- Prepare environments for scalable application hosting

---

## 📸 Validation & Evidence

Execution Documentation (Screenshots & Proof):
Google Drive: (Documentation link will be updated)

---

## 📚 Course Reference

Module: Introduction to EC2, EBS, EFS & FSx  
Course: DevOps Course  
Program: DevOps Architect Master’s Program – Intellipaat

---

Successfully deployed and configured an AWS EC2-based web server environment.
