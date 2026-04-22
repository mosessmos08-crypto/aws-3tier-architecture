AWS 3-Tier Architecture Deployment

Overview

This project demonstrates a basic 3-tier architecture on AWS.

Architecture

- VPC with public & private subnets
- Application Load Balancer
- EC2 instances
- RDS (MySQL)

Flow

User → ALB → EC2 → RDS

Deployment Steps

1. Created VPC and subnets
2. Launched EC2 instances
3. Configured Load Balancer
4. Deployed application
5. Connected RDS database

Screenshots

- EC2 Instances → screenshots/ec2-instances.png
- Target Group → screenshots/target-group.png
- Application Output → screenshots/app-output-1.png
- Database → screenshots/database.png

Key Learnings

- Basic high availability setup
- Load balancing concept
- Importance of private subnet for database
