# 🌐 Multi-Tier VPC Architecture & Cross-VPC Peering (Production & Development)

## 📌 Project Overview

Designed and implemented a secure, multi-tier Amazon VPC architecture for both Production and Development environments, including cross-VPC peering for controlled inter-network communication.

The solution separates workloads, enforces subnet-level isolation, enables selective internet access, and establishes secure database connectivity between environments.

---

## 🎯 Business Requirement

Build isolated Production and Development VPC environments with structured tier architecture, controlled internet access, and secure VPC peering connectivity.

---

# 🏗 Production Network Architecture (4-Tier Design)

## 🔹 Subnet Design

• 1 Public Subnet → **web**  
• 4 Private Subnets → **app1, app2, dbcache, db**

## 🔹 EC2 Deployment Strategy

• Launched instances in all subnets  
• Instances named according to subnet purpose  
  - web-instance  
  - app1-instance  
  - app2-instance  
  - dbcache-instance  
  - db-instance  

## 🔹 Internet Access Strategy

• Public subnet (web) connected to Internet Gateway  
• NAT Gateway deployed for controlled outbound access  
• Enabled internet access for:
  - dbcache subnet  
  - app1 subnet  

## 🔹 Security Architecture

• Implemented Security Groups for tier-based access control  
• Configured NACLs for subnet-level traffic filtering  
• Restricted database subnet from public internet  
• Allowed only required application-to-database communication  

---

# 🏗 Development Network Architecture (2-Tier Design)

## 🔹 Subnet Design

• Public Subnet → web  
• Private Subnet → db  

## 🔹 EC2 Deployment

• Launched web-instance in web subnet  
• Launched db-instance in db subnet  

## 🔹 Internet Control

• Only web subnet allowed outbound internet access  
• Database subnet restricted from public exposure  

---

# 🔗 VPC Peering Architecture

## 🔹 Peering Configuration

• Created VPC Peering connection between:
  - Production VPC  
  - Development VPC  

## 🔹 Route Table Updates

• Updated route tables in both VPCs  
• Enabled cross-VPC communication  

## 🔹 Database Connectivity

• Allowed secure communication between:
  - Production DB subnet  
  - Development DB subnet  

• Implemented Security Group rules to allow controlled DB-level access  

---

# 🔐 Security Design Strategy

• Environment isolation (Prod vs Dev separation)  
• Tier-based subnet segmentation  
• Controlled internet access via NAT & IGW  
• Restricted database exposure  
• Secure cross-environment connectivity  
• Principle of least privilege networking  

---

# 📈 Key Learning Outcomes

• Designing multi-tier VPC architecture  
• Subnet isolation strategies  
• NAT Gateway and Internet Gateway implementation  
• Security Groups & NACL configuration  
• Cross-VPC peering setup  
• Route table management  
• Environment segregation best practices  

---

# 🛠 Skills Demonstrated

• Amazon VPC Architecture Design  
• Multi-Tier Infrastructure Planning  
• Private & Public Subnet Configuration  
• VPC Peering Implementation  
• Secure Network Segmentation  
• AWS Routing & Connectivity Management  
• Production-Grade Cloud Networking  

---

# 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: (Execution screenshots link will be updated)

---

# 📚 Course Reference

Module: Virtual Private Cloud (VPC)  
Course: DevOps Course  
Program: DevOps Architect Master’s Program – Intellipaat
