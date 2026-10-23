AWS Three-Tier Architecture using Terraform
Overview
This project demonstrates the deployment of a production-style Three-Tier Architecture on AWS using Terraform.

The infrastructure consists of:

VPC
Public Subnets
Private Subnets
Database Subnets
Internet Gateway
NAT Gateway
Route Tables
Security Groups
Application Load Balancer (ALB)
Target Group
Listener
Launch Template
Auto Scaling Group (ASG)
MySQL RDS
Terraform Outputs
Architecture
Internet │ ▼ Application Load Balancer │ ▼ Target Group │ ▼ Auto Scaling Group │ ▼ EC2 Instances (Apache) │ ▼ MySQL RDS

Features
Infrastructure as Code (Terraform)
Multi-AZ Deployment
Highly Available Architecture
Load Balancing using ALB
Auto Scaling for EC2 Instances
Private Application Tier
Private Database Tier
Automated EC2 Configuration using User Data
Security Group Based Access Control
Skills Demonstrated
AWS Networking
Terraform
Infrastructure Automation
Load Balancing
Auto Scaling
Route Tables and NAT Gateway
Security Group Design
RDS Deployment
Troubleshooting ALB Health Checks
Cloud Infrastructure Operations
