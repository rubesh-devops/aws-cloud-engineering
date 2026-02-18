# Database Migration from MySQL to PostgreSQL using AWS DMS

## 📌 Objective
Migrate a relational database workload from **Amazon RDS MySQL** to **Amazon RDS PostgreSQL** using **AWS Database Migration Service (DMS)**.

This demonstrates cloud-native database modernization and cross-engine migration.

---

## 🏗 Migration Scenario

XYZ Corporation is modernizing its infrastructure and wants to:

- Move from MySQL to PostgreSQL
- Ensure minimal downtime
- Use managed AWS services
- Improve scalability and availability

---

## 🛠 AWS Services Used

- Amazon RDS (MySQL)
- Amazon RDS (PostgreSQL)
- AWS Database Migration Service (DMS)
- AWS DMS Replication Instance
- AWS IAM
- Amazon VPC

---

## 🚀 Implementation Steps

### Step 1 – Launch RDS MySQL Database

1. Navigate to **RDS → Create Database**
2. Choose:
   - Engine: **MySQL**
   - Deployment: Dev/Test
3. Configure:
   - DB instance identifier: `mysql-source-db`
   - Master username & password
4. Enable public access (for testing)
5. Create DB

After creation:

Connect using:
- MySQL Workbench (Windows)
- EC2 + MySQL CLI (Linux)

Insert sample data:

```sql
CREATE DATABASE migrationdb;
USE migrationdb;

CREATE TABLE employees (
  id INT PRIMARY KEY,
  name VARCHAR(50),
  department VARCHAR(50)
);

INSERT INTO employees VALUES
(1,'Rubesh','DevOps'),
(2,'Arun','Cloud'),
(3,'Meena','Security');
```

---

### Step 2 – Launch RDS PostgreSQL Database

1. Create new RDS instance
2. Choose:
   - Engine: **PostgreSQL**
   - DB identifier: `postgres-target-db`
3. Configure credentials
4. Ensure same VPC as MySQL

Wait until instance is available.

---

### Step 3 – Create DMS Replication Instance

1. Go to **DMS → Replication Instances**
2. Create new instance:
   - Name: `dms-replication-instance`
   - Instance class: dms.t2.micro (or suitable)
   - Same VPC as databases

Wait for status: **Available**

---

### Step 4 – Create Source and Target Endpoints

#### Source Endpoint (MySQL)
- Endpoint type: Source
- Engine: MySQL
- Server name: MySQL endpoint
- Username & password
- Test connection

#### Target Endpoint (PostgreSQL)
- Endpoint type: Target
- Engine: PostgreSQL
- Server name: PostgreSQL endpoint
- Credentials
- Test connection

Both must show:
```
successful
```

---

### Step 5 – Create DMS Migration Task

1. Create task:
   - Replication instance: `dms-replication-instance`
   - Source: MySQL
   - Target: PostgreSQL
   - Migration type: **Migrate existing data**
2. Select database and tables
3. Start task

Monitor until status becomes:
```
Load complete
```

---

### Step 6 – Verify Migration

Connect to PostgreSQL:

```sql
\c migrationdb;

SELECT * FROM employees;
```

Expected Output:

| id | name   | department |
|----|--------|------------|
| 1  | Rubesh | DevOps     |
| 2  | Arun   | Cloud      |
| 3  | Meena  | Security   |

Migration verified successfully.

---

## 🎯 Outcome

Successfully migrated database from:

- MySQL → PostgreSQL
- Using AWS managed DMS
- Without manual dump/restore

---

## 📁 Consolidated Documentation

Drive Link: <ADD-YOUR-DRIVE-LINK-HERE>  

Course Reference: Intellipaat AWS Architect Program  

---

## ✅ Skills Demonstrated

- RDS MySQL provisioning
- RDS PostgreSQL provisioning
- DMS replication instance configuration
- Endpoint configuration & connectivity validation
- Cross-engine database migration
- Data validation post migration
- Cloud modernization strategy
