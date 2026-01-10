# Secure Static Website Hosting on AWS

## Overview
 This project solves the problem of hosting a static website securely and reliably in the cloud. The setup follows AWS best practices for security, performance, and reliability. This project demonstrates how to securely host a static website on AWS using Amazon S3 and CloudFront, with HTTPS enabled.

## AWS Services Used
- Amazon S3
- Amazon CloudFront

## Architecture
User → CloudFront (HTTPS) → S3 Static Website Bucket

## Steps Performed
1. Created an S3 bucket for static website hosting
2. Enabled static website hosting on the S3 bucket
3. Uploaded HTML and CSS files to the bucket
4. Created a CloudFront distribution pointing to the S3 bucket
5. Configured CloudFront to serve the site over HTTPS

## Outcome
The static website was successfully deployed and served securely over HTTPS using CloudFront - http://static-site-portfolio-01.s3-website.eu-north-1.amazonaws.com/

## Potential Issues & Fixes
- Website not loading - Check S3 bucket permissions and static website hosting settings
- HTTPS not working - Verify CloudFront distribution and ACM certificate configuration
- Access denied errors - Ensure S3 bucket policy allows CloudFront to read objects
