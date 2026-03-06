# AWS Resource Tracker (Shell Script)

## Overview

This project contains a **Bash automation script** that retrieves and reports AWS resource usage using the **AWS CLI** and **jq**.

The script collects information about key AWS services including:

- S3 Buckets
- EC2 Instances
- Lambda Functions
- IAM Users

This script is useful for **quick infrastructure visibility, monitoring, and automation**.

---

## Technologies Used

- Bash / Shell Scripting
- AWS CLI
- jq (JSON Processor)
- Cron (for scheduling automation)

---

## Features

The script reports the following AWS resources:

### S3 Buckets
Lists all S3 buckets in the AWS account.

### EC2 Instances
Displays:
- Instance ID
- Instance Name
- Public IP Address
- Key Pair

### Lambda Functions
Lists all deployed Lambda functions.

### IAM Users
Displays IAM users and their user IDs.

---

## Author 
**Arti Semwal**
