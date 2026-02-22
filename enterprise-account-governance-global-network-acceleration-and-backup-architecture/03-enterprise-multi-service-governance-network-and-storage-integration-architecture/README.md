# 🏗 Enterprise Multi-Service Governance, Network and Storage Integration Architecture

## 📌 Project Overview

A multi-service AWS architecture was implemented integrating storage, networking, global traffic management, and compute services under an enterprise governance model.

The objective was to deploy shared file storage using FSx, provision Linux web servers, optimize global traffic routing using AWS Global Accelerator, and enhance network flexibility using Elastic Network Interfaces (ENI).

This implementation demonstrates enterprise-grade infrastructure integration across storage, compute, and global networking services.

---

## 🎯 Business Requirement

XYZ Corporation required:

- Shared file storage across Linux instances  
- Web server deployment on multiple EC2 instances  
- High-performance global traffic routing  
- Flexible network interface management  
- Secure administrative access control  

---

## 🏗 Architecture Implemented

- Amazon FSx (Linux-compatible file system)  
- 2 Linux EC2 Instances (Ubuntu/Amazon Linux)  
- Web Server Deployment (Apache/Nginx)  
- AWS Global Accelerator  
- Elastic Network Interface (ENI)  
- Multi-Service Integrated Architecture  

---

## ⚙️ Implementation Summary

### 1️⃣ FSx File System Deployment

- Created FSx file system  
- Configured networking and security groups  
- Mounted FSx to two Linux EC2 instances  
- Validated shared file accessibility across instances  

---

### 2️⃣ Web Server Deployment

- Launched two Linux EC2
