# AWS Automation with Python (boto3)

This project showcases automation tasks built using Python and AWS SDK (boto3). It covers real-world cloud operations such as storage management, monitoring, backups, and reporting.

## 🚀 Technologies

* Python
* AWS SDK (boto3)
* Amazon S3
* Amazon EC2
* Amazon CloudWatch
* AWS IAM

---

## 📌 Features / Challenges Implemented

### 1. S3 File Automation

* Create S3 buckets
* Upload, list, and download files

### 2. Automated Backup System

* Scan local directories
* Upload files to S3 with date-based structure

### 3. EC2 Monitoring

* Retrieve instance details:

  * Instance ID
  * Status
  * Type
  * Public IP

### 4. S3 Cleanup Automation

* Identify and delete objects older than a defined threshold

### 5. CloudWatch Metrics

* Send custom metrics from Python to AWS CloudWatch

### 6. IAM Automation (Restricted Environment)

* Scripted creation of users, policies, and access keys
* Encountered permission constraints (expected in lab environments)

### 7. AWS Resource Inventory

* Generate inventory of:

  * EC2
  * S3
  * Lambda
* Export results to JSON

### 8. Data Pipeline (S3 Processing)

* Upload file → Read → Process → Store result in another bucket

### 9. EBS Snapshot Automation

* List volumes
* Create automated snapshots

### 10. Reporting System

* Generate EC2 usage report
* Store report in S3 as JSON

---

## 📊 Example Output

```json
{
  "EC2": [
    {
      "InstanceId": "i-123456",
      "Tipo": "t2.micro",
      "Estado": "running"
    }
  ]
}
```

---

## 🧠 Key Learnings

* AWS service integration via boto3
* IAM permissions and security constraints
* Automation of cloud operations
* Data processing pipelines
* Infrastructure monitoring and reporting

---

## ⚠️ Notes

* Some IAM operations may fail due to restricted lab permissions (expected behavior).
* All scripts were tested in a controlled AWS environment.

---

## 👩‍💻 Author

Anyelina Vilchis
Cloud Practicioner
