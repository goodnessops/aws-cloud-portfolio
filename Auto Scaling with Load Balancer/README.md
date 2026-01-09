# Auto Scaling with Application Load Balancer on AWS

## Overview
This project demonstrates how to deploy a highly available and scalable application on AWS using an Auto Scaling Group (ASG) and an Application Load Balancer (ALB).

## AWS Services Used
- Amazon EC2
- Application Load Balancer (ALB)
- Auto Scaling Group (ASG)

## Architecture
User → Application Load Balancer → Auto Scaling Group (EC2 Instances)

## Steps Performed
1. Created an EC2 launch template with application configuration
2. Created an Application Load Balancer
3. Created an Auto Scaling Group with a minimum of 1 and maximum of 2 instances
4. Attached the Application Load Balancer to the Auto Scaling Group


## Outcome
The application was successfully accessed through the Application Load Balancer, and the Auto Scaling Group ensured availability and automatic scaling.

## Skills Demonstrated
- EC2 launch templates
- Load balancing
- Auto scaling
- High availability architecture
