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
