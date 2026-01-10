# Automated Web Server with CloudFormation

## Overview
This project demonstrates how to deploy a web server using AWS CloudFormation. The infrastructure including the EC2 instance, security groups, and web server setup—is fully automated using a CloudFormation template, minimizing manual configuration.

## AWS Services Used
- AWS CloudFormation
- Amazon EC2 (provisioned by CloudFormation)
- Security Groups
- Nginx/Apache (installed via user-data script)
- SSH (for verification)

## Architecture
User → Internet → EC2 Instance (provisioned via CloudFormation) → Nginx Web Server

## Steps Performed
1. Created a CloudFormation template to launch an EC2 instance with security group configuration with assist
2. Automated Nginx installation using a user-data script
3. Deployed the stack in AWS
4. Verified the EC2 instance and security group creation
5. Confirmed the web server was accessible via the EC2 public IP

## Outcome
The web server was successfully deployed using CloudFormation, demonstrating automated infrastructure provisioning and secure server setup with minimal manual intervention.

## Skills Demonstrated
- Infrastructure as Code (CloudFormation)  
- Automated EC2 provisioning  
- Security group configuration for SSH and HTTP  
- User-data scripting for server setup  
- Verification of deployed infrastructure
