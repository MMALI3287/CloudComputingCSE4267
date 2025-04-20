# CSE4267 Cloud Computing Course Notes 📚☁️

<div align="center">

[![AWS](https://img.shields.io/badge/AWS-Cloud_Computing-orange?style=for-the-badge&logo=amazon-aws)](https://aws.amazon.com/)
[![Docker](https://img.shields.io/badge/Docker-Containerization-blue?style=for-the-badge&logo=docker)](https://www.docker.com/)
[![Kubernetes](https://img.shields.io/badge/Kubernetes-Orchestration-blue?style=for-the-badge&logo=kubernetes)](https://kubernetes.io/)
[![Linux](https://img.shields.io/badge/Linux-OS-yellow?style=for-the-badge&logo=linux)](https://www.linux.org/)

</div>

## 📋 Overview

This repository contains comprehensive notes and resources for the CSE4267 Cloud Computing course. These materials cover fundamental cloud computing concepts, AWS services, containerization, virtualization, and related technologies to help students understand and master cloud computing principles.

<div align="center">

![Cloud Computing Concept](1662635777501.png)

</div>

## 📑 Table of Contents

- [CSE4267 Cloud Computing Course Notes 📚☁️](#cse4267-cloud-computing-course-notes-️)
  - [📋 Overview](#-overview)
  - [📑 Table of Contents](#-table-of-contents)
  - [Course Materials](#course-materials)
  - [Key Topics Overview](#key-topics-overview)
  - [AWS Services Quick Reference](#aws-services-quick-reference)
  - [Practical Guides](#practical-guides)
    - [Docker Quick Start](#docker-quick-start)
    - [AWS CLI Essential Commands](#aws-cli-essential-commands)
    - [Linux Commands for Cloud](#linux-commands-for-cloud)
  - [Exam Preparation](#exam-preparation)
    - [Key Areas to Focus On](#key-areas-to-focus-on)
    - [Practice Resources](#practice-resources)
  - [Shared Responsibility Model](#shared-responsibility-model)
  - [Lecture Slides](#lecture-slides)
  - [Cheat Sheets](#cheat-sheets)
  - [Online Learning Resources](#online-learning-resources)
    - [Official Documentation](#official-documentation)
    - [Free Learning Platforms](#free-learning-platforms)
    - [YouTube Channels](#youtube-channels)
  - [Detailed Course Notes](#detailed-course-notes)

## Course Materials

| Category                     | Description                                       | Files                                                                                                                                                                                          |
| ---------------------------- | ------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Comprehensive Notes**      | Detailed course notes covering all major topics   | [cloud_computing_note.md](cloud_computing_notes.md), [cloud_overview.md](cloud_overview.md)                                                                                                    |
| **PowerPoint Presentations** | Lecture slides for each topic                     | [View All Slides](#lecture-slides)                                                                                                                                                             |
| **PDF Resources**            | Additional reading materials and reference guides | [Cloud Computing for Dummies](Cloud-Computing-for-Dummies-Judith-Hurwitz-Robin-Bloor-Marcia-Kaufman-Fern-Halper-Edisi-1-2010.pdf), [Course Outline](CSE4267%20Cloud%20Computing%20Outline.pdf) |
| **Exam Preparation**         | Materials to help with test preparation           | [Exam Tips](Cloud-Computing-Exam-Tips.pdf), [Practice Questions](AWS-Service-Question-Examples.pdf)                                                                                            |
| **Cheat Sheets**             | Quick reference guides                            | [Docker Cheatsheet](docker_cheatsheet.pdf), [Linux Command Line](Linux%20Command%20Line%20Cheat%20Sheet.pdf)                                                                                   |

## Key Topics Overview

<div align="center">

```mermaid
mindmap
  root((Cloud Computing))
    Fundamentals
      Definition & Evolution
      Key Characteristics
      Service Models
      Deployment Models
    AWS Services
      Compute (EC2)
      Storage (S3)
      Security (IAM)
      Networking (VPC)
      Databases (RDS)
      Serverless (Lambda)
    Infrastructure
      Data Centers
      Virtualization
      Containerization
        Docker
        Kubernetes
    Operations
      Linux
      CI/CD
      Monitoring
      SLAs
    Advanced Topics
      Cloud OS
      Shared Responsibility
      Future Trends
```

</div>

## AWS Services Quick Reference

| Service Category | Key Services               | Description                                                                |
| ---------------- | -------------------------- | -------------------------------------------------------------------------- |
| **Compute**      | EC2, Lambda, ECS           | Virtual servers, serverless functions, container orchestration             |
| **Storage**      | S3, EBS, EFS, Glacier      | Object storage, block storage, file storage, archival storage              |
| **Database**     | RDS, DynamoDB, ElastiCache | Relational, NoSQL, and in-memory databases                                 |
| **Networking**   | VPC, Route 53, CloudFront  | Virtual networks, DNS, content delivery network                            |
| **Security**     | IAM, KMS, WAF, Shield      | Identity management, encryption, web application firewall, DDoS protection |
| **Integration**  | SQS, SNS, API Gateway      | Message queues, pub/sub notifications, API management                      |
| **Monitoring**   | CloudWatch, CloudTrail     | Metrics, logs, events, API activity tracking                               |

## Practical Guides

### Docker Quick Start

```bash
# Build an image
docker build -t my-app .

# Run a container
docker run -d -p 8080:80 my-app

# List running containers
docker ps

# Stop a container
docker stop container-id
```

### AWS CLI Essential Commands

```bash
# List S3 buckets
aws s3 ls

# Create an EC2 instance
aws ec2 run-instances --image-id ami-12345678 --instance-type t2.micro

# List running EC2 instances
aws ec2 describe-instances --filters "Name=instance-state-name,Values=running"
```

### Linux Commands for Cloud

```bash
# System information
uname -a         # System information
df -h            # Disk usage
free -m          # Memory usage
top              # Process information

# Network
ping host        # Test connectivity
netstat -tulpn   # Show network connections
ssh user@host    # Connect to remote host
```

## Exam Preparation

### Key Areas to Focus On

- AWS service capabilities and limitations
- Security best practices
- Architectural patterns and anti-patterns
- Cost optimization strategies
- Disaster recovery and high availability

### Practice Resources

- [AWS Certified Cloud Practitioner](https://aws.amazon.com/certification/certified-cloud-practitioner/)
- [AWS Certified Solutions Architect](https://aws.amazon.com/certification/certified-solutions-architect-associate/)
- [Practice Exams](AWS-Service-Question-Examples.pdf)
- [Class Test Examples](Class%20Test%201.pdf)

## Shared Responsibility Model

<div align="center">

![AWS Shared Responsibility Model](Shared_Responsibility_Model_V2.59d1eccec334b366627e9295b304202faf7b899b.jpg)

</div>

## Lecture Slides

| Topic                                | Presentation                                                                                             |
| ------------------------------------ | -------------------------------------------------------------------------------------------------------- |
| Introduction to Cloud Computing      | [Slides](1.%20Introduction%20to%20Cloud%20Computing.pptx)                                                |
| Resource Sharing in the Cloud        | [Slides](2.%20Resource%20Sharing%20in%20the%20Cloud.pptx)                                                |
| Challenges and Risks                 | [Slides](3.%20Challenges%20and%20Risks%20in%20Cloud%20Computing.pptx)                                    |
| Cloud Service Models                 | [Slides](4.%20Cloud%20Service%20Models.pptx)                                                             |
| IaaS (Amazon EC2)                    | [Slides](<5.%20IaaS%20(Amazon%20EC2).pptx>)                                                              |
| Amazon S3                            | [Slides](6.%20Amazon%20S3.pptx)                                                                          |
| AWS IAM                              | [Slides](<7.%20AWS%20IAM%20(Identity%20and%20Access%20Management).pptx>)                                 |
| AWS VPC                              | [Slides](<8.%20AWS%20VPC%20(Virtual%20Private%20Cloud).pptx>)                                            |
| Introduction to Linux                | [Slides](9.%20Introduction%20to%20Linux.pptx)                                                            |
| AWS Auto Scaling and Load Balancing  | [Slides](10.%20AWS%20Auto%20Scaling%20and%20Load%20Balancing.pptx)                                       |
| Amazon SQS & SNS                     | [Slides](11.%20Amazon%20SQS%20%26%20SNS.pptx)                                                            |
| AWS Route 53                         | [Slides](<12.%20AWS%20Route%2053%20(DNS).pptx>)                                                          |
| AWS SES                              | [Slides](<13.%20AWS%20SES%20(Simple%20Email%20Service).pptx>)                                            |
| Data Centers                         | [Slides](14.%20Data%20Centers.pptx)                                                                      |
| Virtualization                       | [Slides](15.%20Virtualization.pptx)                                                                      |
| Containerization                     | [Slides](16.%20Containerization_%20Application%20Deployment.pptx)                                        |
| Docker                               | [Slides](17.%20Docker_%20Containerization%20Simplified.pptx)                                             |
| Kubernetes                           | [Slides](18.%20Introduction%20to%20Kubernetes.pptx)                                                      |
| API Gateway                          | [Slides](19.%20Understanding%20API%20Gateway.pptx)                                                       |
| Amazon CloudFront                    | [Slides](20.%20Amazon%20CloudFront.pptx)                                                                 |
| Amazon RDS                           | [Slides](21.%20Amazon%20RDS.pptx)                                                                        |
| AWS Security                         | [Slides](22.%20AWS%20Security_%20KMS%2C%20WAF%2C%20and%20Shield.pptx)                                    |
| Capacity Planning & Cloud Brokers    | [Slides](23.%20Capacity%20Planning%20%26%20Cloud%20Brokers.pptx)                                         |
| Service-Level Agreements             | [Slides](<24.%20Service-Level%20Agreements%20(SLAs)%20%20in%20Cloud%20Computing.pptx>)                   |
| CI/CD                                | [Slides](25.%20CI_CD_%20Streamlining%20Software%20Delivery.pptx)                                         |
| Serverless Computing with AWS Lambda | [Slides](26.%20Serverless%20Computing%20with%20AWS%20Lambda.pptx)                                        |
| Monitoring & Logging in AWS          | [Slides](<27.%20Monitoring%20%26%20Logging%20in%20AWS%20(CloudWatch%2C%20CloudTrail%2C%20Logging).pptx>) |
| AWS Budget and Cost Optimisation     | [Slides](28.%20AWS%20Budget%20and%20Cost%20Optimisation.pptx)                                            |
| Cloud Operating Systems and Servers  | [Slides](29.%20Cloud%20Operating%20Systems%20and%20Servers.pptx)                                         |
| Revision Class                       | [Slides](30.%20REVISION%20CLASS.pptx)                                                                    |
| All Topics Combined                  | [Slides](CloudComputingAll.pptx)                                                                         |

## Cheat Sheets

- [Docker Cheatsheet](docker_cheatsheet.pdf)
- [Linux Command Line Cheat Sheet](Linux%20Command%20Line%20Cheat%20Sheet.pdf)

## Online Learning Resources

### Official Documentation

- [AWS Documentation](https://docs.aws.amazon.com/)
- [AWS Architecture Center](https://aws.amazon.com/architecture/)
- [AWS Well-Architected Framework](https://aws.amazon.com/architecture/well-architected/)
- [Docker Documentation](https://docs.docker.com/)
- [Kubernetes Documentation](https://kubernetes.io/docs/)

### Free Learning Platforms

- [AWS Training and Certification](https://aws.amazon.com/training/)
- [AWS Skill Builder](https://explore.skillbuilder.aws/learn)
- [Microsoft Learn for Azure](https://learn.microsoft.com/en-us/training/azure/)
- [Google Cloud Training](https://cloud.google.com/training)
- [Docker Getting Started](https://docs.docker.com/get-started/)
- [Kubernetes Tutorials](https://kubernetes.io/docs/tutorials/)

### YouTube Channels

- [AWS Online Tech Talks](https://www.youtube.com/channel/UCT-nPlVzJI-ccQXlxjSvJmw)
- [TechWorld with Nana](https://www.youtube.com/c/TechWorldwithNana)
- [freeCodeCamp.org](https://www.youtube.com/c/Freecodecamp)
- [Cloud Guru](https://www.youtube.com/c/AcloudGuru)

---

## Detailed Course Notes

For in-depth technical details about AWS services, containerization, serverless computing, and more, refer to the [Cloud Computing Technical Notes](cloud_computing_notes.md).
