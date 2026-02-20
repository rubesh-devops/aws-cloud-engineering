# 🔗 VPC Cross-Region and Intra-Region Peering Architecture Implementation

## 📌 Project Overview

A multi-VPC architecture was designed to enable secure communication between isolated network environments across regions.

The objective was to implement both intra-region and cross-region VPC peering connections to allow private communication between workloads deployed in separate VPCs while maintaining network isolation and security boundaries.

This implementation demonstrates advanced AWS networking, inter-VPC communication, and scalable hybrid architecture design.

---

## 🎯 Business Requirement

The organization required:

- Multiple isolated VPC environments  
- Secure private connectivity between VPCs  
- Cross-region communication capability  
- Scalable and flexible network expansion  

---

## 🏗 Architecture Implemented

- VPC 1: **MYVPC1** (North Virginia – us-east-1)  
- VPC 2: **MYVPC2** (North Virginia – us-east-1)  
- VPC 3: **VPCOregon1** (Oregon – us-west-2)  
- Intra-region VPC Peering (MYVPC1 ↔ MYVPC2)  
- Cross-region VPC Peering (MYVPC2 ↔ VPCOregon1)  
- Route Table Updates for bidirectional communication  

---

## ⚙️ Implementation Summary

### 1️⃣ VPC Deployment

- Created two VPCs in **North Virginia (us-east-1)**  
  - MYVPC1  
  - MYVPC2  
- Created one VPC in **Oregon (us-west-2)**  
  - VPCOregon1  
- Configured unique CIDR blocks to avoid overlap  

---

### 2️⃣ Intra-Region Peering Configuration

- Initiated VPC Peering between MYVPC1 and MYVPC2  
- Accepted the peering request  
- Updated route tables in both VPCs  
- Added routes pointing to peer CIDR blocks  
- Validated private communication between resources  

---

### 3️⃣ Cross-Region Peering Configuration

- Initiated cross-region VPC peering between MYVPC2 (us-east-1) and VPCOregon1 (us-west-2)  
- Accepted peering request in target region  
- Updated route tables in both VPCs  
- Configured routes to enable cross-region private connectivity  
- Verified connectivity across regions  

---

## 🔐 Security Configuration

- Ensured non-overlapping CIDR ranges  
- Restricted access using security groups  
- Enabled only required inbound/outbound traffic  
- Maintained isolation while enabling controlled communication  
- Avoided public internet routing for internal traffic  

---

## 📊 Outcome Achieved

- Successfully implemented intra-region VPC peering  
- Successfully implemented cross-region VPC peering  
- Enabled secure private communication across regions  
- Built scalable multi-VPC architecture  
- Demonstrated enterprise-grade AWS networking design  

---

## 🛠 Skills Demonstrated

- Amazon VPC Architecture Design  
- Intra-Region VPC Peering  
- Cross-Region VPC Peering  
- Route Table Configuration  
- CIDR Planning and Network Segmentation
