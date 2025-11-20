# AWS-Cloud-Infrastructure-with-VPC-s
A secure and scalable AWS infrastructure designed using VPC, ALB, and multi-AZ deployment to ensure high availability (99.9% uptime) and efficient traffic management.

⭐ Key Features

Designed a VPC with public and private subnets across multiple Availability Zones for high availability.
Configured NAT Gateways to provide controlled internet access for instances in private subnets.
Deployed an Application Load Balancer with HTTPS support and intelligent routing to distribute traffic.
Implemented Auto Scaling Groups for self-healing and automatic scaling based on application demand.
Applied least-privilege security using Security Groups and Network ACLs for network-level protection.

🛠️ Technology Stack

| Category     | Tools / Services                         |
| ------------ | ---------------------------------------- |
| AWS Services | VPC, EC2, ALB, NAT Gateway, Auto Scaling |
| Security     | Security Groups, Network ACLs            |
| Architecture | Multi-AZ Deployment, Load Balancing      |

🧩 Architecture Diagram
<img width="611" height="481" alt="image" src="https://github.com/user-attachments/assets/ded93f94-78b4-4707-bc0f-d93d45f3dc8b" />

▶️ Usage

Access the application via the ALB DNS endpoint (HTTPS enabled).
Monitor scaling activities and network traffic using AWS Console or CLI.
Review Security Group and Network ACL logs for compliance and auditing.

🌍 Real-World Benefits

Ensures high availability through multi-AZ deployment and automated scaling.
Strengthens network security by isolating application layers and enforcing strict firewall rules.

🎯 Certifications / Skills Demonstrated

