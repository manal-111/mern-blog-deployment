# MERN Stack Blog App Deployment with Terraform and Ansible
Scenario: Blog App Deployment
Deploy a MERN stack blog application on AWS. Backend will run on a single EC2 instance (Ubuntu 22.04),
frontend will be hosted via S3 static website hosting, and MongoDB Atlas will be used as the database. Media
uploads will be handled through a separate S3 bucket with proper IAM policies.

## ✅ Deployment Architecture
EC2 Instance (Ubuntu 22.04)
MongoDB Atlas
S3 Bucket (Frontend)
S3 Bucket (Media)
IAM User

## 🧱 Infrastructure Setup (Terraform)
 Navigate to terraform/ and create the following:
main.tf

variables.tf

outputs.tf

provider.tf







##🧹 Cleanup

terraform destroy

Delete MongoDB Atlas IP rule

Remove secrets from EC2 (rm ~/.env)

Deactivate IAM keys 
