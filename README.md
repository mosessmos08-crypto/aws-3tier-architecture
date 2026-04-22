# AWS 3-Tier Architecture

This project demonstrates a 3-tier architecture on AWS.

## Architecture
- VPC with public & private subnets
- Application Load Balancer (ALB)
- EC2 instances (Web/App layer)
- RDS (Database layer)

## Features
- Secure backend in private subnet
- Traffic handled via Load Balancer
- Basic high availability setup

## Flow
User → ALB → EC2 → RDS
