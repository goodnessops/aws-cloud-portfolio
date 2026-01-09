# EC2 Backup to S3 Using IAM Role

## Overview
This project demonstrates how to securely back up files and logs from an EC2 instance to Amazon S3 using IAM roles instead of access keys.

## AWS Services Used
- EC2
- S3
- IAM

## Architecture
EC2 instance → IAM Role → S3 Backup Bucket

## Steps Performed
1. Created an S3 bucket for backups EC2 Backup to S3/created-S3-backup-bucket.jpeg
2. Created an IAM role with least-privilege S3 permissions
3. Attached IAM role to EC2 instance
4. Copied logs and files from EC2 to S3
5. Verified objects in S3 bucket

## Outcome
Files and logs were successfully backed up to S3 without storing AWS credentials on the EC2 instance.

## Skills Demonstrated
- Secure access using IAM roles
- EC2 administration
- S3 object storage
- AWS security best practices

