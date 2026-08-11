# EC2 Instance Automation using User Data

## Project Overview
This project demonstrates automated provisioning and configuration of an Amazon EC2 instance using User Data scripts.

## What I Implemented
- Launched a Linux-based EC2 instance
- Configured Security Groups to allow HTTP (port 80)
- Used EC2 User Data script to:
  - Install Apache HTTP Server
  - Start and enable Apache service
  - Deploy a sample web page automatically

## User Data Script Example
#!/bin/bash
yum update -y
yum install httpd -y
systemctl start httpd
systemctl enable httpd
echo "DevOps Project Deployed Successfully" > /var/www/html/index.html

## Services Used
- Amazon EC2
- AWS IAM
- Security Groups
- Linux
- Bash Scripting
- Apache HTTP Server
