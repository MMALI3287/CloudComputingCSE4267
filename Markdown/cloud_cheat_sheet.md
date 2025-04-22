# Cloud Computing Exam Cheat-Sheet

## Table of Contents

- [Cloud Computing Exam Cheat-Sheet](#cloud-computing-exam-cheat-sheet)
  - [Table of Contents](#table-of-contents)
  - [1. Introduction to Cloud Computing](#1-introduction-to-cloud-computing)
  - [2. Resource Sharing in the Cloud](#2-resource-sharing-in-the-cloud)
  - [3. Challenges and Risks in Cloud Computing](#3-challenges-and-risks-in-cloud-computing)
  - [4. Cloud Service Models (IaaS, PaaS, SaaS, FaaS)](#4-cloud-service-models-iaas-paas-saas-faas)
  - [5. Data Centers and Infrastructure](#5-data-centers-and-infrastructure)
  - [6. Virtualization](#6-virtualization)
  - [7. Containerization](#7-containerization)
  - [8. Serverless Computing](#8-serverless-computing)
  - [9. Monitoring and Logging](#9-monitoring-and-logging)
  - [10. Cost Management](#10-cost-management)
  - [11. Service-Level Agreements (SLAs)](#11-service-level-agreements-slas)
  - [12. Continuous Integration/Continuous Deployment (CI/CD)](#12-continuous-integrationcontinuous-deployment-cicd)
  - [13. Cloud Operating Systems and Servers](#13-cloud-operating-systems-and-servers)
  - [14. Linux for Cloud Computing](#14-linux-for-cloud-computing)
  - [15. Shared Responsibility Model](#15-shared-responsibility-model)

## 1. Introduction to Cloud Computing

- **What:** Delivery of computing resources (servers, storage, apps) over the internet.
- **Why:** Provides on-demand, scalable, and cost-effective computing without owning hardware.
- **How:** Uses virtualization, self-service provisioning, and resource pooling.

## 2. Resource Sharing in the Cloud

- **What:** Allowing multiple users to utilize the same computing resources.
- **Why:** Maximizes utilization, reduces cost, and supports multi-tenancy.
- **How:** Implements virtualization and dynamic allocation strategies.

## 3. Challenges and Risks in Cloud Computing

- **What:** Issues like security vulnerabilities, privacy concerns, and vendor lock-in.
- **Why:** They affect reliability, compliance, and overall trust.
- **How:** Mitigated using encryption, security audits, robust backup/disaster recovery, and careful vendor selection.

## 4. Cloud Service Models (IaaS, PaaS, SaaS, FaaS)

- **What:** Different layers of cloud offerings—from raw infrastructure to complete applications.
- **Why:** To suit varied control, management, and cost needs.
- **How:** IaaS offers virtual machines; PaaS provides managed platforms; SaaS delivers ready-to-use apps; FaaS runs functions on demand.

## 5. Data Centers and Infrastructure

- **What:** The physical facilities that house server, storage, and network equipment.
- **Why:** They provide the foundation for all cloud services.
- **How:** Organized into regions and availability zones with robust security, redundancy, and cooling systems.

## 6. Virtualization

- **What:** Creating virtual (software-based) versions of hardware or resources.
- **Why:** Increases utilization and reduces hardware waste.
- **How:** Through hypervisors (Type 1 for bare metal; Type 2 for hosted) running multiple OS instances on one machine.

## 7. Containerization

- **What:** Packaging applications with all their dependencies into isolated containers.
- **Why:** Ensures consistency across different environments, efficient resource use, and rapid scaling.
- **How:** Using tools like Docker to create containers and Kubernetes to orchestrate them.

## 8. Serverless Computing

- **What:** Running code without managing the underlying server infrastructure.
- **Why:** Eliminates server management overhead and scales automatically with demand.
- **How:** Triggering small functions (e.g., AWS Lambda) by events; billed only for execution time.

## 9. Monitoring and Logging

- **What:** Continuous collection of performance metrics and logs.
- **Why:** Essential for troubleshooting, ensuring performance, and maintaining operations.
- **How:** With tools (e.g., CloudWatch for metrics/alarms and CloudTrail for audit logs) that gather and analyze data.

## 10. Cost Management

- **What:** Practices and tools to control and forecast cloud spending.
- **Why:** To optimize budgets and avoid unnecessary expenses.
- **How:** By using tools like Cost Explorer, AWS Budgets, and Reserved Instance pricing, plus right-sizing resources.

## 11. Service-Level Agreements (SLAs)

- **What:** Contracts that define service uptime and performance standards.
- **Why:** To set clear expectations and ensure accountability.
- **How:** By specifying measurable metrics (like 99.9% uptime) and outlining remedies if targets aren’t met.

## 12. Continuous Integration/Continuous Deployment (CI/CD)

- **What:** Automation of software build, test, and deployment processes.
- **Why:** Improves speed, quality, and consistency of releases.
- **How:** Using automated pipelines (e.g., Jenkins, AWS CodePipeline) that integrate code, test, and deploy steps.

## 13. Cloud Operating Systems and Servers

- **What:** Operating systems optimized for cloud environments (e.g., Amazon Linux).
- **Why:** They are tailored for scalability, security, and integration with cloud APIs.
- **How:** Provide automation, resource management, and performance tuned for distributed server architectures.

## 14. Linux for Cloud Computing

- **What:** Linux distributions often used in cloud environments (e.g., Ubuntu, Amazon Linux).
- **Why:** Due to their stability, security, open-source nature, and community support.
- **How:** Managed via common Linux commands, shell scripting, and system administration best practices.

## 15. Shared Responsibility Model

- **What:** A framework that divides security responsibilities between the cloud provider and the customer.
- **Why:** To clarify what is secured by AWS (the infrastructure) and what the customer must secure (data, configuration, applications).
- **How:** AWS manages “security of the cloud” (hardware, facilities, network), while customers manage “security in the cloud” (access controls, encryption, applications).
