# Project Documentation: AWS Infrastructure Setup

This document serves as a guide for setting up the AWS infrastructure for the project. It includes instructions for configuring various components such as VPC, subnet, security group, gateway, route tables, IAM role for EC2 instance, S3 bucket creation, and connecting EC2 instance to the VPC.


## Table of Contents
1. [VPC Setup](#vpc-setup)

---

## 1. VPC Setup <a name="vpc-setup"></a>
- Go to the VPC dashboard in the AWS Management Console.
- Click on "Create VPC" and provide the necessary details such as name, CIDR block, etc.
- Ensure to enable DNS hostname and DNS resolution for the VPC.
- Click on "Create" to create the VPC.