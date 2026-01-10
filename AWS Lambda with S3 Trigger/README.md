# AWS Lambda with S3 Trigger

## Overview
This project demonstrates how to build a serverless function using AWS Lambda, log executions with CloudWatch, and automatically trigger the function when files are uploaded to an S3 bucket. It simulates a common real-world use case such as file processing or event-driven automation. This project solves the problem of manually processing files. By using Lambda with S3 triggers, files can be handled automatically, saving time and reducing errors.

## AWS Services Used
- AWS Lambda
- Amazon S3
- Amazon CloudWatch
- AWS IAM

## Architecture
S3 Bucket → Lambda Function → CloudWatch Logs

## Steps Performed
1. Created an AWS Lambda function
2. Wrote a simple handler function
3. Tested Lambda execution manually
4. Enabled CloudWatch Logs for monitoring and debugging
5. Configured an S3 trigger to invoke the Lambda function
6. Tested the trigger by uploading objects to the S3 bucket

## Outcome
The Lambda function executed successfully when files were uploaded to S3, and logs were captured in CloudWatch for monitoring and troubleshooting.

## Skills Demonstrated
- Serverless computing with AWS Lambda
- Event-driven architecture using S3 triggers
- CloudWatch logging and monitoring
- IAM permissions for Lambda execution
- Basic troubleshooting and testing

## Potential Issues & Fixes
- Lambda not triggering - Check S3 trigger and event type
- Permission errors - Make sure Lambda role has S3 & CloudWatch access
- Logs missing - Ensure logging is enabled and role can write to CloudWatch
- Function timeout - Increase Lambda timeout or memory for large files
