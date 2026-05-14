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

This allows users to view website files while preventing upload, delete, or modification actions.

📌

Built as part of AWS Solutions Architect Associate learning journey and cloud portfolio development.
