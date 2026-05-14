# AWS Static Website Project

Hosted a static website using:
- AWS S3
- GitHub
- VS Code

Concepts Learned:
- S3 bucket hosting
- IAM bucket policies
- Static website hosting
- Public access permissions

aws-static-website/
│
├── index.html
├── style.css
└── README.md

Deployment Steps
Created website files in VS Code
Initialized Git repository
Pushed project to GitHub
Created S3 bucket in AWS
Uploaded website files
Enabled static website hosting
Configured bucket policy for public access
Accessed website using S3 website endpoint
🎯 Key Learning Outcomes
Learned how static websites are hosted in AWS
Understood the difference between server-based and serverless hosting
Practiced real-world AWS architecture concepts
Gained hands-on experience with S3 permissions and policies
Improved GitHub and deployment workflow skills
📖 AWS Concepts Covered
S3 Storage Classes
Static Website Hosting
IAM Policies
Bucket Policies
Public Access Configuration
Cloud Architecture Basics
Scalability & High Availability
🔐 Security Note

Public access was enabled only for:

s3:GetObject

User
 ↓
CloudFront CDN
 ↓
S3 Static Website

# Kathaverse Nova 🚀

My first AWS Solutions Architect Associate hands-on cloud project.

## 🌐 Live Demo
https://d3sgnt16r5fnfz.cloudfront.net

---

# 📌 Project Overview

This project demonstrates how to host a static website using AWS cloud services with global content delivery using Amazon CloudFront CDN.

The website was built using:
- HTML
- CSS
- AWS S3
- AWS CloudFront
- GitHub
- VS Code

---

# 🏗️ AWS Architecture

User  
↓  
CloudFront CDN  
↓  
S3 Static Website Hosting  

---

# ☁️ AWS Services Used

## 1. Amazon S3
Used for:
- Static website hosting
- Storing HTML and CSS files

## 2. Amazon CloudFront
Used for:
- Global CDN delivery
- Faster website loading
- Low latency access
- Website caching

---

# 📂 Project Files

```bash
index.html
style.css
README.md

This allows users to view website files while preventing upload, delete, or modification actions.

📌

Built as part of AWS Solutions Architect Associate learning journey and cloud portfolio development.
