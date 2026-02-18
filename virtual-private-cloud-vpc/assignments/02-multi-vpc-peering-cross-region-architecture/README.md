# 🔗 Multi-VPC Peering Architecture (Intra & Cross-Region)

## 📌 Project Overview

Designed and implemented a multi-VPC networking architecture to enable secure communication between isolated AWS environments across both same-region and cross-region deployments.

This implementation demonstrates enterprise-grade VPC peering strategies for scalable and distributed cloud environments.

---

## 🎯 Problem Statement

The organization required multiple isolated network environments that could securely communicate with each other within the same region and across different regions.

---

## 🏗 Architecture Implemented

• VPC: MYVPC1 (us-east-1 – North Virginia)  
• VPC: MYVPC2 (us-east-1 – North Virginia)  
• VPC: VPCOregon1 (us-west-2 – Oregon)  
• Intra-region VPC Peering (MYVPC1 ↔ MYVPC2)  
• Cross-region VPC Peering (MYVPC2 ↔ VPCOregon1)  
• Updated Route Tables for bi-directional communication  

---

## ⚙️ Implementation Summary

### 1️⃣ VPC Deployment
• Created MYVPC1 and MYVPC2 in North Virginia region  
• Created VPCOregon1 in Oregon region  
• Defined appropriate CIDR blocks to avoid overlap  

### 2️⃣ Intra-Region Peering
• Established peering connection between MYVPC1 and MYVPC2  
• Accepted peering request  
• Updated route tables in both VPCs for mutual communication  

### 3️⃣ Cross-Region Peering
• Established cross-region peering between MYVPC2 (Virginia) and VPCOregon1 (Oregon)  
• Accepted peering request from target region  
• Updated route tables for cross-region traffic routing  

---

## 🔐 Security & Network Design Strategy

• Maintained isolated CIDR ranges  
• Enabled controlled inter-VPC communication  
• Ensured no overlapping IP ranges  
• Updated route tables carefully to avoid asymmetric routing  

---

## 📈 Key Learning Outcomes

• Designing multi-VPC network architecture  
• Implementing intra-region VPC peering  
• Configuring cross-region VPC peering  
• Route table management for peered networks  
• Understanding AWS regional networking boundaries  

---

## 🛠 Skills Demonstrated

• AWS VPC Architecture  
• VPC Peering Configuration  
• Cross-Region Networking  
• Route Table Engineering  
• Secure Inter-Network Communication  

---

## 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: (Execution screenshots link will be updated)

---

## 📚 Course Reference

Module: Virtual Private Cloud (VPC)  
Course: DevOps Course  
Program: DevOps Architect Master’s Program – Intellipaat

