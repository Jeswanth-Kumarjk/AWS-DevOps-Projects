# Terraform AWS Infrastructure

Infrastructure as Code (IaC) project using Terraform to provision and manage AWS resources.

## Technologies Used

- Terraform
- AWS S3
- Git
- GitHub

## Project Overview

This project demonstrates how to provision and manage AWS infrastructure using Terraform instead of manually creating resources through the AWS Management Console.

The project currently provisions an Amazon S3 bucket and manages its configuration using Terraform.

## AWS Resources

### Amazon S3

- S3 bucket creation
- S3 bucket versioning
- AWS region configuration
- Bucket name managed through Terraform variables

## Project Structure

```text
terraform-aws-infrastructure/
├── main.tf
├── variables.tf
├── README.md
├── .gitignore
└── .terraform.lock.hcl

## Deployment Verification

The Terraform configuration was successfully used to provision an AWS EC2
instance and deploy a web server.

### Application Test

The deployed web server was successfully accessed through the EC2 public IP:

`http://3.111.169.30`

The browser displayed:

**Terraform AWS Infrastructure Project**

This confirms that the EC2 instance and web server were successfully provisioned and are accessible over the internet.
