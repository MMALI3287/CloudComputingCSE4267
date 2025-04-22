# AWS Services Cheat-Sheet

## Table of Contents

### Compute Services

- [EC2](#ec2)
- [Lambda](#lambda)
- [Auto Scaling](#auto-scaling)
- [Elastic Beanstalk](#elastic-beanstalk)

### Storage Services

- [S3](#s3)
- [EBS](#ebs)
- [EFS](#efs)
- [Glacier](#glacier)

### Database Services

- [RDS](#rds)
- [DynamoDB](#dynamodb)
- [ElastiCache](#elasticache)

### Networking Services

- [VPC](#vpc)
- [Route 53](#route-53)
- [CloudFront](#cloudfront)
- [API Gateway](#api-gateway)
- [ELB](#elb)

### Messaging Services

- [SQS](#sqs)
- [SNS](#sns)
- [SES](#ses)

### Security Services

- [IAM](#iam)
- [KMS](#kms)
- [WAF](#waf)
- [Shield](#shield)

### Monitoring and Management Services

- [CloudWatch](#cloudwatch)
- [CloudTrail](#cloudtrail)
- [Cost Explorer](#cost-explorer)
- [AWS Budgets](#aws-budgets)
- [CloudFormation](#cloudformation)

## EC2

- **What:** Virtual servers in the cloud.
- **Why:** To host apps and run custom infrastructure.
- **How:** Launch customizable instances in regions with security groups & IAM.

## Lambda

- **What:** Serverless compute.
- **Why:** To run code in response to events without managing servers.
- **How:** Upload functions triggered by events; billed per invocation & duration.

## Auto Scaling

- **What:** Automatic scaling of resources.
- **Why:** To maintain performance and control costs.
- **How:** Monitors metrics and adjusts instance counts with defined policies.

## Elastic Beanstalk

- **What:** PaaS for web apps.
- **Why:** To simplify app deployment and management.
- **How:** Upload code; platform handles provisioning, scaling, and monitoring.

## S3

- **What:** Object storage service.
- **Why:** To store and retrieve data reliably.
- **How:** Organizes data in buckets with multiple storage classes.

## EBS

- **What:** Block storage for EC2.
- **Why:** To provide persistent, high-performance storage.
- **How:** Attach volumes to instances; supports snapshots for backups.

## EFS

- **What:** Scalable file storage.
- **Why:** For shared file systems across multiple EC2 instances.
- **How:** Provides an NFS that grows automatically as you add files.

## Glacier

- **What:** Archival storage.
- **Why:** For long-term, low-cost storage of infrequently accessed data.
- **How:** Stores archives with retrieval times ranging from minutes to hours.

## RDS

- **What:** Managed relational database.
- **Why:** To lower the admin burden for databases.
- **How:** Automates backups, patching, and scaling for popular DB engines.

## DynamoDB

- **What:** Managed NoSQL database.
- **Why:** For fast, scalable, low-latency data operations.
- **How:** Uses key-value and document data models with auto-scaling.

## ElastiCache

- **What:** In-memory caching.
- **Why:** To speed up data access and reduce database load.
- **How:** Deploys Redis or Memcached clusters for rapid data retrieval.

## VPC

- **What:** Isolated virtual network.
- **Why:** To control your own network environment in the cloud.
- **How:** Define subnets, route tables, and security groups.

## Route 53

- **What:** DNS web service.
- **Why:** To direct traffic using domain names.
- **How:** Maps domain names to IPs with advanced routing policies.

## CloudFront

- **What:** Content delivery network (CDN).
- **Why:** To deliver content with low latency globally.
- **How:** Caches content at edge locations across the world.

## API Gateway

- **What:** API management service.
- **Why:** To create secure, scalable APIs for backend services.
- **How:** Routes API calls to services (Lambda, EC2) with auth and throttling.

## ELB

- **What:** Load balancer.
- **Why:** To distribute traffic evenly across instances.
- **How:** Monitors health and directs traffic using various balancing algorithms.

## SQS

- **What:** Message queuing service.
- **Why:** To decouple microservices and enable asynchronous processing.
- **How:** Producers send messages to a queue; consumers retrieve and process them.

## SNS

- **What:** Pub/Sub messaging service.
- **Why:** For delivering notifications to multiple subscribers.
- **How:** Messages are published to topics and pushed to subscribers via various protocols.

## SES

- **What:** Email sending service.
- **Why:** For transactional and bulk email delivery.
- **How:** Integrates via API/SMTP; supports authentication (SPF, DKIM) and reputation management.

## IAM

- **What:** Identity and Access Management.
- **Why:** To control and secure access to AWS resources.
- **How:** Create users, groups, roles, and policies to manage permissions.

## KMS

- **What:** Key management service.
- **Why:** To securely create and manage encryption keys.
- **How:** Integrates with AWS services to encrypt data, with key rotation and access control.

## WAF

- **What:** Web Application Firewall.
- **Why:** To protect web apps from common threats (SQL injection, XSS).
- **How:** Allows you to define rules that filter HTTP/HTTPS requests.

## Shield

- **What:** DDoS protection service.
- **Why:** To safeguard applications against DDoS attacks.
- **How:** Automatically detects and mitigates attacks at the network edge.

## CloudWatch

- **What:** Monitoring and observability.
- **Why:** To collect metrics and logs for AWS resources.
- **How:** Uses dashboards, alarms, and logs to monitor performance and trigger actions.

## CloudTrail

- **What:** Audit logging.
- **Why:** For tracking API calls and user activity.
- **How:** Records and stores events in S3 for review and compliance.

## Cost Explorer

- **What:** Cost analysis tool.
- **Why:** To visualize and manage AWS spending.
- **How:** Generates reports and visualizations of historical usage and cost trends.

## AWS Budgets

- **What:** Budget tracking tool.
- **Why:** To set spending limits and receive alerts.
- **How:** Define budgets and get notifications when thresholds are exceeded.

## CloudFormation

- **What:** Infrastructure as Code (IaC) service.
- **Why:** To automate resource provisioning and updates.
- **How:** Uses JSON or YAML templates to create and manage AWS stacks.
