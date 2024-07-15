# AWS Static Website Hosting
This project demonstrates how to host a static website on AWS using S3 and CloudFront. The website is built using HTML and CSS and is deployed to an S3 bucket configured for static website hosting. A CloudFront distribution is set up to serve the website content, providing improved performance and security.

# Table of Contents
Prerequisites
Setup Instructions
 1. Upload Files to S3
 2. Configure S3 Bucket for Static Website Hosting
 3. Create a CloudFront Distribution
Architecture Diagram

# Prerequisites
Before you begin, ensure you have the following:

An AWS account
AWS CLI installed and configured
Basic knowledge of HTML and CSS

# Setup Instructions
Follow these steps to set up and deploy your static website:

# 1. Upload Files to S3
 Create an S3 bucket to store your website files.
 Upload your HTML and CSS files to the S3 bucket.
# 2. Configure S3 Bucket for Static Website Hosting
 Navigate to the S3 bucket in the AWS Management Console.
 Go to the "Properties" tab.
 Under "Static website hosting," select "Use this bucket to host a website."
 Specify the index document (e.g., index.html) and error document (e.g., error.html).
 Save the changes.
# 3. Create a CloudFront Distribution
 Open the CloudFront console.
 Create a new distribution.
 In the "Origin Settings," specify the S3 bucket URL as the origin.
 Configure other settings as needed, such as enabling HTTPS, setting default root object, etc.
 Create the distribution and note the CloudFront URL provided.
# Accessing Your Website
Once the CloudFront distribution is deployed, you can access your website using the CloudFront URL.
