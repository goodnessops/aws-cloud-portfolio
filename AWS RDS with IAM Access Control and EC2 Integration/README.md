# AWS RDS with IAM Access Control and EC2 Integration

## Overview
This project demonstrates how to deploy a managed relational database on AWS (RDS), integrate it securely with IAM roles and policies, enable automated backups, and connect it to an EC2 instance.  
It also shows snapshot creation for backup and recovery.

## AWS Services Used
- Amazon RDS (Relational Database Service)
- Amazon EC2
- AWS IAM

## Architecture
EC2 Instance → IAM Role → RDS Database → Automated Backups / Snapshots

## Steps Performed
1. Created an RDS database instance (e.g., MySQL or PostgreSQL)
3. Created IAM roles and policies for secure database access
4. Attached IAM role to EC2 instance
5. Connected the database to an EC2 instance and tested connectivity
6. Created manual snapshots of the database for point-in-time recovery

## Outcome
The RDS instance was deployed successfully with secure IAM access.  
Automated backups and snapshots were configured, ensuring data durability and recoverability.  
The EC2 instance was able to connect and interact with the database securely.

## Skills Demonstrated
- RDS deployment and management
- IAM roles and policies for database access
- Secure EC2-RDS integration
- Automated backups and snapshot management
- Cloud architecture and security best practices
