I was bored, so I created a project leveraging two popular technologies in the DevOps Space:

1.)Terraform

2.)AWS Cloud

Project Prompt:

You are apply for XYZ technologies as a Devops Engineer, and have reached the technical phase of your interview process. The Sr. DevOps Engineer has tasked you to create an infrastructure deployment project using Terraform on AWS. This project will assess your knowledge and skills in setting up and managing cloud resources, utilizing Infrastructure as Code (IaC) principles, and ensuring best practices in the DevOps domain.

Here are the guidelines of the Project:

1. Terraform Configuration
    - Set up a Terraform configuration that defines the infrastructure you'll be deploying on AWS.
    - Define the following AWS resources:
    - Virtual Private Cloud (VPC) with appropriate CIDR blocks.
    - Two public and two private subnets spread across different availability zones.
    - An Internet Gateway for the public subnet to enable outbound internet access.
    - A Route Table for the public subnet with the necessary routes.
    - Security Groups for controlling inbound/outbound traffic for instances.
    - Launch Configuration or Auto Scaling Group to launch EC2 instances in the private subnet.
    - Use variables and data sources wherever applicable for flexibility.

2. Networking:
   - Ensure proper communication between public and private subnets.
   - Configure Network Address Translation (NAT) for instances in the private subnet to access the internet.

3. Instance Provisioning:
   - Launch two EC2 instances (Amazon Linux or Ubuntu) in the private subnet.
   - Install a basic web server (e.g., Nginx or Apache) on both instances.
   - Demonstrate the ability to use user data for automated software provisioning.



Good Luck!
