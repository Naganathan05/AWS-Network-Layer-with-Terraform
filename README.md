# AWS Network Layer with Terraform

This repository contains Terraform code to deploy a basic AWS network layer, including a Virtual Private Cloud (VPC) and associated subnets.

## Architecture Overview

![Architectural_Diagram](https://github.com/Naganathan05/AWS-Network-Layer-with-Terraform/assets/116747452/1005d531-abc1-4a96-9526-5e944e2ee21f)

## Steps Undergone


- **VPC Configuration:** Define a customizable VPC with specific CIDR blocks.
- **Subnets:** Create public and private subnets distributed across multiple availability zones.
- **Internet Gateway and NAT Gateway:** Attach an Internet Gateway for public subnet internet access and set up NAT Gateways for private subnets.
- **Customization:** Easily customize parameters such as CIDR blocks, subnet sizes, and availability zones.
- **Terraform Best Practices:** Follows best practices for Terraform, including modularization and variable usage.

## Get it Local:

1. Clone the repository:

    ```bash
    git clone https://github.com/Naganathan05/AWS-Network-Layer-with-Terraform.git
    cd aws-network-layer-terraform
    ```
