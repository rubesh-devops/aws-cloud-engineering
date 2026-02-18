# Local Ubuntu VM Setup for Cloud Migration Simulation

## 📌 Objective
Simulate an on-premises environment by creating a local Ubuntu Server virtual machine.  
This VM represents the legacy infrastructure that will later be migrated to AWS.

---

## 🏗 Migration Scenario

XYZ Corporation plans to migrate their infrastructure to AWS to improve performance and availability.

As part of the migration preparation phase, an on-premises Ubuntu server must be provisioned locally using virtualization tools.

This server will later be used for migration testing and validation.

---

## 🛠 Tools Used

- Oracle VirtualBox
- Ubuntu Server 18.04 LTS ISO
- Local System (Windows / Linux Host)

---

## 🚀 Implementation Steps

### Step 1 – Install Oracle VirtualBox
Download and install VirtualBox from:

https://www.virtualbox.org/wiki/Downloads

Verify installation by launching VirtualBox Manager.

---

### Step 2 – Download Ubuntu Server ISO
Download Ubuntu Server 18.04.5 ISO from:

https://releases.ubuntu.com/18.04.5/ubuntu-18.04.5-live-server-amd64.iso

---

### Step 3 – Create New Virtual Machine

- Click **New**
- Name: `onprem-ubuntu-server`
- Type: Linux
- Version: Ubuntu (64-bit)
- RAM: Minimum 2 GB
- CPU: 2 Cores
- Storage: 20 GB (Dynamically Allocated)

---

### Step 4 – Attach Ubuntu ISO

- Go to VM Settings → Storage
- Attach Ubuntu ISO file to Optical Drive

---

### Step 5 – Install Ubuntu Server

- Start VM
- Select Install Ubuntu Server
- Configure:
  - Hostname: onprem-server
  - Username: ubuntu
  - Password: <secure-password>
- Select OpenSSH Server during installation
- Complete installation and reboot

---

### Step 6 – Verify Server Setup

Login and verify:

```bash
uname -a
ip a
```

Confirm:
- OS installed successfully
- Network connectivity working
- SSH service running

---

## 🔍 Validation

- VM boots successfully
- SSH access enabled
- Static or DHCP IP configured
- System ready for migration simulation

---

## 🎯 Outcome

Successfully created a simulated on-premises Ubuntu server environment.  

This VM will act as the source system for:

- Application migration
- Database migration
- AWS migration services testing

---

## 📁 Consolidated Documentation

Drive Link: <ADD-YOUR-DRIVE-LINK-HERE>  

Course Reference: Intellipaat AWS Architect Program  

---

## ✅ Skills Demonstrated

- On-premises infrastructure simulation
- Virtual machine provisioning
- Linux server installation
- Migration readiness preparation
