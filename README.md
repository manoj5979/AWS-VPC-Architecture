# AWS VPC Architecture Project

## Project Overview

This project demonstrates the design and implementation of a Production and Development VPC architecture on Amazon Web Services (AWS).

## Architecture

![Architecture](architecture%20vpc.png)

## Features

- Production VPC
- Development VPC
- Public and Private Subnets
- Internet Gateway
- NAT Gateway
- VPC Peering
- Route Tables
- Security Groups
- Network ACLs
- EC2 Instances
- Database Connectivity

## Production Network

- 4-tier architecture
- 1 Public subnet (Web)
- 4 Private subnets
  - App1
  - App2
  - DBCache
  - Database

## Development Network

- 2-tier architecture
- Public Web subnet
- Private Database subnet

## Connectivity

- Internet Gateway for public access
- NAT Gateway for private subnet internet access
- VPC Peering between Production and Development
- Database communication between both VPCs

## Technologies Used

- Amazon VPC
- EC2
- Internet Gateway
- NAT Gateway
- Route Tables
- Security Groups
- Network ACLs
- VPC Peering

## Documentation

Complete project documentation is available in:

- **vpc assignment done.pdf**

## Author

**Manoj Pallapu**
