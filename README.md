# CSE4267 Cloud Computing Course Notes 📚☁️

[![AWS](https://img.shields.io/badge/AWS-Cloud_Computing-orange?style=for-the-badge&logo=amazon-aws)](https://aws.amazon.com/)
[![Docker](https://img.shields.io/badge/Docker-Containerization-blue?style=for-the-badge&logo=docker)](https://www.docker.com/)
[![Kubernetes](https://img.shields.io/badge/Kubernetes-Orchestration-blue?style=for-the-badge&logo=kubernetes)](https://kubernetes.io/)
[![Linux](https://img.shields.io/badge/Linux-OS-yellow?style=for-the-badge&logo=linux)](https://www.linux.org/)

## 📋 Overview

This repository contains comprehensive notes and resources for the CSE4267 Cloud Computing course. These materials cover fundamental cloud computing concepts, AWS services, containerization, virtualization, and related technologies to help students understand and master cloud computing principles.

![Cloud Computing Concept](Images/1662635777501.png)

## 📑 Table of Contents

- [CSE4267 Cloud Computing Course Notes 📚☁️](#cse4267-cloud-computing-course-notes-️)
  - [📋 Overview](#-overview)
  - [📑 Table of Contents](#-table-of-contents)
  - [Course Materials](#course-materials)
  - [Key Topics Overview](#key-topics-overview)
  - [AWS Services Quick Reference](#aws-services-quick-reference)
  - [Exam Preparation](#exam-preparation)
    - [Key Areas to Focus On](#key-areas-to-focus-on)
    - [Practice Resources](#practice-resources)
  - [Lecture Slides](#lecture-slides)
  - [Cheat Sheets](#cheat-sheets)
  - [Online Learning Resources](#online-learning-resources)
    - [Official Documentation](#official-documentation)
    - [Free Learning Platforms](#free-learning-platforms)
    - [YouTube Channels](#youtube-channels)
  - [Detailed Course Notes](#detailed-course-notes)

## Course Materials

| Category                     | Description                                       | Files                                                                                                                                                                                                |
| ---------------------------- | ------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Comprehensive Notes**      | Detailed course notes covering all major topics   | [cloud_computing_notes.md](Markdown/cloud_computing_notes.md), [cloud_computing_concepts_and_foundations.md](Markdown/cloud_computing_concepts_and_foundations.md)                                   |
| **PowerPoint Presentations** | Lecture slides for each topic                     | [View All Slides](#lecture-slides)                                                                                                                                                                   |
| **PDF Resources**            | Additional reading materials and reference guides | [Cloud Computing for Dummies](PDFs/Cloud-Computing-for-Dummies-Judith-Hurwitz-Robin-Bloor-Marcia-Kaufman-Fern-Halper-Edisi-1-2010.pdf), [Course Outline](<PDFs/CSE4267 Cloud Computing Outline.pdf>) |
| **Exam Preparation**         | Materials to help with test preparation           | [Exam Tips](PDFs/Cloud-Computing-Exam-Tips.pdf), [Practice Questions](PDFs/AWS-Service-Question-Examples.pdf), [Quiz 2 Key Points](PDFs/Quize-2-key_point.pdf)                                       |
| **Cheat Sheets**             | Quick reference guides                            | [Docker Cheatsheet](PDFs/docker_cheatsheet.pdf), [Linux Command Line](<PDFs/Linux Command Line Cheat Sheet.pdf>)                                                                                     |

## Key Topics Overview

```mermaid
mindmap
  root((Cloud Computing))
    Fundamentals
      Definition & Evolution
        On-demand Computing Services
        Utility Computing Model
      Key Characteristics
        On-Demand Self-Service
        Broad Network Access
        Resource Pooling
        Rapid Elasticity
        Measured Service
      Service Models
        IaaS (EC2, Google Compute)
        PaaS (Elastic Beanstalk, App Engine)
        SaaS (Gmail, Salesforce)
        FaaS (Lambda, Azure Functions)
      Deployment Models
        Public Cloud (AWS, Azure, GCP)
        Private Cloud
        Hybrid Cloud
        Community Cloud
    AWS Services
      Compute
        EC2 (Virtual Servers)
        Lambda (Serverless)
        ECS/EKS (Containers)
        Elastic Beanstalk (PaaS)
      Storage
        S3 (Object Storage)
        EBS (Block Storage)
        EFS (File System)
        Glacier (Archival)
      Security
        IAM (Identity & Access)
        KMS (Encryption)
        WAF (Web Protection)
        Shield (DDoS Protection)
      Networking
        VPC (Virtual Network)
        Route 53 (DNS)
        CloudFront (CDN)
        API Gateway
      Databases
        RDS (Relational)
        DynamoDB (NoSQL)
        ElastiCache (In-memory)
        Redshift (Data Warehouse)
      Integration
        SQS (Message Queue)
        SNS (Notifications)
        SES (Email)
      Monitoring
        CloudWatch (Metrics & Logs)
        CloudTrail (API Activity)
        Cost Explorer
    Infrastructure
      Data Centers
        Tier Levels (I-IV)
        Physical Security
      Virtualization
        Hypervisors
        Resource Abstraction
      Containerization
        Docker
        Kubernetes
    Operations
      Linux
        CLI & Shell Scripting
        System Administration
      CI/CD
        Continuous Integration
        Continuous Delivery
        DevOps Practices
      Monitoring & SLAs
        Performance Metrics
        Uptime Guarantees
    Advanced Topics
      Cloud OS
      Shared Responsibility Model
        Provider vs Customer
      Future Trends
        Edge Computing
        Serverless
        Multi-cloud
```

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
- [Practice Exams](PDFs/AWS-Service-Question-Examples.pdf)
- [Class Test Examples](<PDFs/Class Test 1.pdf>)

## Lecture Slides

| Topic                                | Presentation                                                                                         |
| ------------------------------------ | ---------------------------------------------------------------------------------------------------- |
| Introduction to Cloud Computing      | [Slides](<Powerpoint Slides/1. Introduction to Cloud Computing.pptx>)                                |
| Resource Sharing in the Cloud        | [Slides](<Powerpoint Slides/2. Resource Sharing in the Cloud.pptx>)                                  |
| Challenges and Risks                 | [Slides](<Powerpoint Slides/3. Challenges and Risks in Cloud Computing.pptx>)                        |
| Cloud Service Models                 | [Slides](<Powerpoint Slides/4. Cloud Service Models.pptx>)                                           |
| IaaS (Amazon EC2)                    | [Slides](<Powerpoint Slides/5. IaaS (Amazon EC2).pptx>)                                              |
| Amazon S3                            | [Slides](<Powerpoint Slides/6. Amazon S3.pptx>)                                                      |
| AWS IAM                              | [Slides](<Powerpoint Slides/7. AWS IAM (Identity and Access Management).pptx>)                       |
| AWS VPC                              | [Slides](<Powerpoint Slides/8. AWS VPC (Virtual Private Cloud).pptx>)                                |
| Introduction to Linux                | [Slides](<Powerpoint Slides/9. Introduction to Linux.pptx>)                                          |
| AWS Auto Scaling and Load Balancing  | [Slides](<Powerpoint Slides/10. AWS Auto Scaling and Load Balancing.pptx>)                           |
| Amazon SQS & SNS                     | [Slides](<Powerpoint Slides/11. Amazon SQS & SNS.pptx>)                                              |
| AWS Route 53                         | [Slides](<Powerpoint Slides/12. AWS Route 53 (DNS).pptx>)                                            |
| AWS SES                              | [Slides](<Powerpoint Slides/13. AWS SES (Simple Email Service).pptx>)                                |
| Data Centers                         | [Slides](<Powerpoint Slides/14. Data Centers.pptx>)                                                  |
| Virtualization                       | [Slides](<Powerpoint Slides/15. Virtualization.pptx>)                                                |
| Containerization                     | [Slides](<Powerpoint Slides/16. Containerization_ Application Deployment.pptx>)                      |
| Docker                               | [Slides](<Powerpoint Slides/17. Docker_ Containerization Simplified.pptx>)                           |
| Kubernetes                           | [Slides](<Powerpoint Slides/18. Introduction to Kubernetes.pptx>)                                    |
| API Gateway                          | [Slides](<Powerpoint Slides/19. Understanding API Gateway.pptx>)                                     |
| Amazon CloudFront                    | [Slides](<Powerpoint Slides/20. Amazon CloudFront.pptx>)                                             |
| Amazon RDS                           | [Slides](<Powerpoint Slides/21. Amazon RDS.pptx>)                                                    |
| AWS Security                         | [Slides](<Powerpoint Slides/22. AWS Security_ KMS, WAF, and Shield.pptx>)                            |
| Capacity Planning & Cloud Brokers    | [Slides](<Powerpoint Slides/23. Capacity Planning & Cloud Brokers.pptx>)                             |
| Service-Level Agreements             | [Slides](<Powerpoint Slides/24. Service-Level Agreements (SLAs)  in Cloud Computing.pptx>)           |
| CI/CD                                | [Slides](<Powerpoint Slides/25. CI_CD_ Streamlining Software Delivery.pptx>)                         |
| Serverless Computing with AWS Lambda | [Slides](<Powerpoint Slides/26. Serverless Computing with AWS Lambda.pptx>)                          |
| Monitoring & Logging in AWS          | [Slides](<Powerpoint Slides/27. Monitoring & Logging in AWS (CloudWatch, CloudTrail, Logging).pptx>) |
| AWS Budget and Cost Optimisation     | [Slides](<Powerpoint Slides/28. AWS Budget and Cost Optimisation.pptx>)                              |
| Cloud Operating Systems and Servers  | [Slides](<Powerpoint Slides/29. Cloud Operating Systems and Servers.pptx>)                           |
| Revision Class                       | [Slides](<Powerpoint Slides/30. REVISION CLASS.pptx>)                                                |
| All Topics Combined                  | [Slides](PDFs/CloudComputingAll.pdf)                                                                 |

## Cheat Sheets

- [Cloud Computing Exam Cheat Sheet](Markdown/cloud_cheat_sheet.md)
- [AWS Services Cheat Sheet](Markdown/aws_services_cheat_sheet.md)
- [Docker Cheatsheet](PDFs/docker_cheatsheet.pdf)
- [Linux Command Line Cheat Sheet](<PDFs/Linux Command Line Cheat Sheet.pdf>)

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
- [Fireship](https://www.youtube.com/c/Fireship)
- [IBM Technology](https://www.youtube.com/c/IBMTechnology)
- [ByteByteGo](https://www.youtube.com/c/ByteByteGo)

---

## Detailed Course Notes

For in-depth technical details about AWS services, containerization, serverless computing, and more, refer to the [Cloud Computing Technical Notes](Markdown/cloud_computing_notes.md) and [Cloud Computing Concepts and Foundations](Markdown/cloud_computing_concepts_and_foundations.md).

The technical notes include 36 curated video resources covering various cloud computing topics. Each video is placed directly after its related content section for easier reference and learning. Topics include AWS services, containerization with Docker and Kubernetes, virtualization, Linux, and more.
