# VM Export to AWS AMI Migration Execution

## 📌 Objective
Migrate an on-premises Ubuntu VM to AWS Cloud by:

- Exporting the Virtual Machine
- Uploading it to Amazon S3
- Converting it into an AMI
- Launching an EC2 instance from the migrated image

This simulates real-world infrastructure migration from on-prem to AWS.

---

## 🏗 Migration Scenario

XYZ Corporation wants to improve application performance and availability by migrating their infrastructure to AWS.

The previously created Ubuntu VM represents the on-premises server.  
This task migrates that VM into AWS EC2.

---

## 🛠 AWS Services Used

- Amazon S3
- AWS VM Import/Export
- Amazon EC2
- IAM (VM Import Role)

---

## 🚀 Implementation Steps

### Step 1 – Export Ubuntu VM from VirtualBox

1. Open VirtualBox
2. Select `onprem-ubuntu-server`
3. Click **File → Export Appliance**
4. Choose **OVA format**
5. Export the file locally (example: `onprem-ubuntu.ova`)

This creates a portable VM image file.

---

### Step 2 – Upload VM Image to Amazon S3

1. Create an S3 bucket (if not already created)
2. Upload the exported `.ova` file
3. Verify upload completion

Example:
```
onprem-ubuntu.ova
```

---

### Step 3 – Create IAM Role for VM Import

Create IAM Role named:

```
vmimport
```

Attach policy allowing:
- S3 read access
- EC2 import permissions

Trust relationship should allow:

```
vmie.amazonaws.com
```

---

### Step 4 – Import VM as AMI

Using AWS CLI:

```bash
aws ec2 import-image \
  --description "OnPrem Ubuntu Migration" \
  --disk-containers file://containers.json
```

Example `containers.json`:

```json
[
  {
    "Description": "OnPrem Ubuntu",
    "Format": "ova",
    "UserBucket": {
      "S3Bucket": "your-bucket-name",
      "S3Key": "onprem-ubuntu.ova"
    }
  }
]
```

Monitor import status:

```bash
aws ec2 describe-import-image-tasks
```

Wait until status becomes:

```
completed
```

---

### Step 5 – Create EC2 Instance from AMI

1. Navigate to EC2 → AMIs
2. Select the imported AMI
3. Click **Launch Instance**
4. Choose instance type (t2.micro or t2.medium)
5. Configure security group (allow SSH)
6. Launch instance

---

## 🔍 Validation

- EC2 instance boots successfully
- SSH access works
- Application/services from original VM are intact
- Migration verified successfully

---

## 🎯 Outcome

Successfully migrated on-premises Ubuntu VM to AWS EC2 using VM Import/Export.

This demonstrates:

- Lift-and-shift migration strategy
- Hybrid infrastructure transition
- Cloud migration workflow

---

## 📁 Consolidated Documentation

Drive Link: <ADD-YOUR-DRIVE-LINK-HERE>  

Course Reference: Intellipaat AWS Architect Program  

---

## ✅ Skills Demonstrated

- VM export and packaging
- S3 object storage usage
- AWS VM Import/Export service
- AMI creation from on-prem VM
- EC2 instance provisioning from custom AMI
- Infrastructure migration lifecycle
