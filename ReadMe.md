# Automation with Python - Cloud & Infrastructure Projects

This repository contains a collection of automation projects focused on cloud infrastructure, server management, monitoring, and recovery. These projects leverage AWS, Terraform, Docker, and Python scripting to streamline cloud operations and enhance reliability.

## Table of Contents

### Project Overview
### Technologies Used
### Projects:
        1. EC2 Health Check & Status Monitoring
        2. Automating EC2 Server Tagging
        3. EKS Cluster Information Retrieval
        4. EC2 Data Backup & Restore
        5. Website Monitoring & Recovery
### Setup & Installation
### Usage


# Project Overview

This collection of projects demonstrates various automation techniques for cloud-based infrastructure using Python and AWS. The goal is to automate manual operations such as monitoring EC2 instances, managing backups, tagging resources, retrieving cluster information, and ensuring high availability for web applications.

# Technologies Used

1 Programming Language: Python
2 Cloud Services: AWS (EC2, EKS, S3, IAM)
3 Infrastructure as Code: Terraform
4 Automation & Containerization: Docker
5 Monitoring & Alerting: Custom Python scripts with email notifications

# Projects

## 1. EC2 Health Check & Status Monitoring

### Description:
A Python-based monitoring system for AWS EC2 instances that periodically checks their status and reports any issues.

### Features:
- Deploy EC2 instances using Terraform
- Fetch and display instance details
- Implement periodic status checks

### Technologies: 

Python, Boto3, AWS, Terraform

## 2. Automating EC2 Server Tagging

### Description:
A script that automates the process of tagging EC2 instances with environment-related metadata.

### Features:
- Identify untagged EC2 instances
- Assign predefined environment tags (e.g., Production, Development, Testing)

### Technologies:
 Python, Boto3, AWS

## 3. EKS Cluster Information Retrieval

### Description:
A script that gathers and displays real-time information about an AWS Elastic Kubernetes Service (EKS) cluster.

### Features:
- Fetch details of running Kubernetes nodes
- Display cluster health and status

### Technologies:
 Python, Boto3, AWS EKS

## 4. EC2 Data Backup & Restore

### Description:
Automates EC2 volume backups and restores using AWS snapshots.

### Features:
- Create automated backups for EC2 volumes
- Remove old snapshots to manage storage efficiently
- Restore EC2 volumes from existing backups

### Technologies: 
 Python, Boto3, AWS

## 5. Website Monitoring & Recovery

### Description:
A system that monitors website availability and automatically recovers the service if downtime is detected.

### Features:
- Deploy a website using Docker on a cloud platform
- Monitor website health using HTTP requests
- Send email notifications when the site is down
- Restart the application automatically upon failure

### Technologies:
 Python, Linode, Docker, Linux

# Setup & Installation

## Prerequisites
- Python 3.x installed
- AWS CLI configured (aws configure)
- Terraform installed (for EC2 deployment)
- Docker installed (for web monitoring project)

## Installation

Clone the repository:

```bash
git clone https://github.com/kwenealete/python-automation-projects.git
cd your-repo
```
Install required dependencies:

```bash
pip install boto3
```

Usage

Each project contains a dedicated script that can be executed individually.

Run the EC2 Health Check script:
```bash
python ec2_health_check.py
```
Run the Website Monitoring script:
```bash
python website_monitor.py
```
Modify configurations in each script as per your AWS setup before execution.


### Author

Monya