# s3-cloudfront-web-hosting
Hosting Static website using s3 and cloudfront
# AWS Static Website Hosting using S3 and CloudFront

## Project Overview

This project demonstrates hosting a static website on Amazon Web Services (AWS) using Amazon S3 and Amazon CloudFront.

The website files are stored in an S3 bucket and delivered globally through CloudFront CDN to improve performance, availability, and scalability.

## Architecture

User → CloudFront → Amazon S3 → Static Website Files

## Services Used

* Amazon S3
* Amazon CloudFront
* AWS IAM

## Project Steps

### 1. Create S3 Bucket

* Created an S3 bucket for website hosting.
* Uploaded website files including index.html.

### 2. Configure Static Website Hosting

* Enabled Static Website Hosting.
* Configured index.html as the default document.

### 3. Configure Bucket Policy

* Added bucket policy to allow public read access for website content.

### 4. Create CloudFront Distribution

* Created CloudFront distribution.
* Configured S3 website endpoint as origin.
* Set index.html as Default Root Object.

### 5. Validate Deployment

* Verified website accessibility through CloudFront URL.
* Confirmed successful content delivery.

## Website Content

The website contains:

* Welcome message
* AWS learning message
* Hosted using Amazon S3 and CloudFront

## Skills Demonstrated

* AWS S3
* Static Website Hosting
* CloudFront CDN
* IAM Policies
* Cloud Infrastructure
* Troubleshooting and Configuration

## Challenges Faced

* Configuring bucket permissions.
* Troubleshooting CloudFront origin settings.
* Setting Default Root Object in CloudFront.

## Outcome

Successfully deployed and delivered a static website using AWS S3 and CloudFront. Gained practical experience in cloud storage, content delivery networks, access management, and troubleshooting AWS services.
