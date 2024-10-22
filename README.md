# EKS provisioning using Terraform

This repository provides Terraform code for creating an EKS cluster on AWS.

## Features

The Terraform code provisions the following:

- **EKS**:
    - An EKS cluster with Kubernetes version of 1.31
    - Access entry to the cluster using your IAM User ARN
    - EKS managed node groups
- **VPC**:
    - A VPC to deploy the EKS cluster in

## Prerequisites

- AWS CLI (version used is 2.17.13)
- Terraform (version used is 1.9.2)
- AWS Credentials (access key and secret key)
- An AWS account and a user with credentials for programmatic access
- Basic knowledge of AWS and Terraform

## Usage

To make use of the Terraform code, I have added a step-by-step instruction on my website [here](https://www.adnanalshar.com/projects/terraform-eks/setting-up).