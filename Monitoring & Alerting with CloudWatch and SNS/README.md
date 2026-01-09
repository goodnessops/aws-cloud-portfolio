# CloudWatch Monitoring & Alerting

## Overview
This project demonstrates how to set up basic monitoring and alerting for an EC2 instance using Amazon CloudWatch and SNS.  
It ensures proactive notifications when CPU utilization exceeds a threshold, simulating a real-world cloud support monitoring scenario.

## AWS Services Used
- Amazon CloudWatch
- Amazon SNS (Simple Notification Service)
- Amazon EC2

## Architecture
EC2 Instance → CloudWatch Alarm → SNS Topic → Email Notification

## Steps Performed
1. Created a CloudWatch CPU utilization alarm for an EC2 instance
2. Set threshold to trigger alarm when CPU > 70%
3. Created an SNS topic for notifications
4. Subscribed an email address to the SNS topic

## Outcome
CPU alerts were successfully sent via SNS email notifications, ensuring that system administrators are informed proactively of high CPU usage.

## Skills Demonstrated
- CloudWatch alarm configuration
- Threshold setting and evaluation periods
- SNS topic creation and subscription
- Real-time alerting for system monitoring
- Basic cloud operational monitoring
