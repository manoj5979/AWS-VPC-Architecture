# AWS VPC Architecture Project

## Overview

This project was completed as part of my AWS Cloud training. The goal was to design and implement separate Production and Development environments using Amazon VPC while following networking and security best practices.

The architecture includes multiple subnets, EC2 instances, Internet and NAT Gateways, Security Groups, Network ACLs, and VPC Peering to enable secure communication between both environments.

---

## Project Architecture

![AWS VPC Architecture](architecture%20vpc.png)

---

## Production Environment

The Production VPC was designed using a 4-tier architecture.

It contains:

- Public Web Subnet
- Private App1 Subnet
- Private App2 Subnet
- Private DBCache Subnet
- Private Database Subnet

Resources used:

- Internet Gateway
- NAT Gateway
- Route Tables
- Security Groups
- Network ACLs
- EC2 Instances

---

## Development Environment

The Development VPC contains:

- Public Web Subnet
- Private Database Subnet

Resources used:

- EC2 Instances
- Route Tables
- Security Groups
- Network ACLs

---

## Networking

The following networking components were configured during this project:

- Amazon VPC
- Public and Private Subnets
- Internet Gateway
- NAT Gateway
- Route Tables
- Security Groups
- Network ACLs
- VPC Peering

The Production and Development VPCs were connected through VPC Peering, allowing communication between the database subnets.

---

## Skills Demonstrated

- AWS VPC
- EC2
- Subnet Design
- Internet Gateway
- NAT Gateway
- Route Tables
- Security Groups
- Network ACLs
- VPC Peering
- Cloud Networking

---

## Documentation

The complete assignment report is available in:

- **vpc assignment done.pdf**

The editable architecture diagram is included as:

- **vpc.drawio**

---

## Author

**Manoj Pallapu**
