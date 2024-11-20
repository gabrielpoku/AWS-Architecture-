# AWS-Architecture-
# AWS Two-Tier Architecture
[Architecture Diagram] ![two-tier-architecture](https://github.com/user-attachments/assets/17d03bb0-3792-47ee-a453-cc14dcb94072)

## What is Iac?
**IaC** stands for Infrastructure as **Code**. It is a practice in IT where infrastructure (such as servers, networks, and databases) is managed and provisioned through code, rather than manual processes. IaC allows IT engineers to define, deploy, and manage infrastructure programmatically.
## Terraform
Terraform is an infrastructure as code tool that lets you define both cloud and on-prem resources in human-readable configuration files that you can version, reuse, and share.
## Terraform Modules
A Terraform module is a container for multiple resources that are used together. It organizes Terraform configurations into reusable, manageable, and shareable components.

**Modules can be:**<br>
1- **Root Modules:** The directory where you run `terraform init`, `apply`, etc.<br>
2- **Child Modules:** Reusable configurations called within another module using the `module` block.

## Key Highlights:
Route 53: Seamless DNS query management for efficient domain routing.<br>
CloudFront: Enhanced global performance with a powerful CDN.<br>
AWS Certificate Manager: Implemented secure SSL/TLS certificates for robust security.<br>
Application Load Balancer (ALB): Distributed traffic intelligently across web servers for high availability.<br>
📈 Auto Scaling Group: Enabled dynamic scaling to manage varying workloads effortlessly.<br>
📊 Database with Read Replica: Improved database performance by offloading read operations.<br>
