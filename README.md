AWS 3-Tier Architecture Deployment

📌 Overview

This project demonstrates a basic 3-tier architecture on AWS using core cloud services with a focus on scalability and high availability.

---

🏗️ Architecture Diagram

"Architecture" (architecture-diagram.png)

---

⚙️ Architecture Components

- VPC with public and private subnets
- Application Load Balancer (ALB)
- EC2 instances (Web/Application layer)
- RDS MySQL (Database layer in private subnet)

---

🔄 Workflow

User request → Application Load Balancer → EC2 instances → RDS database

---

🚀 Deployment Steps

1. Created VPC with public & private subnets
2. Launched EC2 instances in public subnet
3. Configured Application Load Balancer
4. Deployed application on EC2 instances
5. Connected backend database (RDS in private subnet)

---

📸 Screenshots

EC2 Instances

"EC2" (screenshots/ec2-instances.png)

Target Group / Load Balancer

"Target" (screenshots/target-group.png)

Application Output

"App" (screenshots/app-output-1.png)

Database (RDS)

"DB" (screenshots/database.png)

---

💡 Key Learnings

- Understood how load balancing distributes traffic
- Learned importance of private subnets for databases
- Gained hands-on experience in designing a basic high availability architecture
