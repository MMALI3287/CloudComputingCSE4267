# Cloud Computing: Concepts and Foundations

## Cloud Computing Study Guide

### Key Concepts Review

#### 1. Introduction to Cloud Computing

- Define cloud computing and its core characteristics.
- Compare cloud computing to traditional IT infrastructure and utility services.
- Identify the key benefits and challenges of adopting cloud computing.
- Understand the different cloud deployment models (Public, Private, Hybrid, Community) and their use cases.
- Differentiate between the various cloud service models (IaaS, PaaS, SaaS, FaaS) and provide examples of each.
- Explain the Shared Responsibility Model in cloud security.

#### 2. Linux Fundamentals

- Understand the history and core features of the Linux operating system (open source, multiuser, portability, security, stability).
- Describe the basic architecture of Linux (Hardware, Kernel, System Libraries, Shell).
- Identify common use cases for Linux (old computers, embedded systems, minimalistic environments).
- Be familiar with basic Linux commands for file system navigation (ls, cd, pwd), file management (mkdir, rm, cp), and system monitoring (top, df -h, free -m).

#### 3. Virtualization

- Define virtualization and its benefits.
- Understand the role of a hypervisor in creating and managing virtual machines.
- Differentiate between different types of virtualization (server, network, storage, desktop).
- Recognize the characteristics of virtualization (partitioning, isolation, encapsulation).
- Understand the concept of Virtual Desktop Infrastructure (VDI).

#### 4. Containerization with Docker

- Define containerization and its advantages over traditional VMs.
- Understand the role of Docker in containerization.
- Identify the basic components of Docker (Dockerfile, Image, Container).
- Be familiar with essential Docker commands (build, run, ps, stop, pull, exec).
- Understand the basic syntax of a Dockerfile (FROM, RUN, COPY, CMD).

#### 5. Amazon Relational Database Service (RDS)

- Understand the purpose of Amazon RDS as a managed relational database service.
- Differentiate between relational databases (SQL) and NoSQL databases and their respective use cases.
- Recognize the flexible schemas and data models offered by NoSQL databases.

#### 6. Cloud Economics and Cost Management

- Understand the pay-as-you-go model in cloud computing.
- Identify factors influencing cloud costs.
- Recognize the importance of cost management in cloud environments.
- Be aware of concepts like capital expenditure reduction and economies of scale in the cloud.

#### 7. Cloud Security and Governance

- Understand the shared responsibility model for security in the cloud.
- Identify common security concerns and risks in cloud computing.
- Recognize the importance of governance in managing cloud environments.
- Be aware of best practices for cloud security and governance.

#### 8. Service-Oriented Architecture (SOA) and Cloud Services

- Understand the concept of a service in the context of cloud computing.
- Recognize the role of business services and component services.
- Differentiate between a service registry and a service repository.

#### 9. Massively Scaled Applications

- Understand the concept of massively scaled applications and their cost efficiencies in the cloud.
- Recognize examples of massively scaled SaaS offerings.

#### 10. Cloud Standards and Organizations

- Understand the importance of standards for interoperability, portability, integration, and security in the cloud.
- Be aware of key standards organizations and groups in cloud computing (e.g., NIST, DMTF, Cloud Security Alliance).

### Short-Answer Quiz

1. What is cloud computing, and what are the three core characteristics mentioned in the introduction?
2. Describe the difference between Infrastructure as a Service (IaaS) and Software as a Service (SaaS), providing a brief example for each.
3. Explain the Shared Responsibility Model in cloud security. Give one example of a responsibility of the cloud provider and one of the customer.
4. What is virtualization, and what is the software component that enables it? Briefly describe its function.
5. Explain the purpose of Docker, and list three fundamental Docker commands and their functions.
6. What is Amazon RDS, and what is the key difference between relational (SQL) and NoSQL databases?
7. Describe the 'pay-as-you-go' model in cloud computing and why it is considered a benefit.
8. Name three core features of the Linux operating system that make it suitable for cloud environments.
9. What is a service in the context of SOA and cloud computing? Briefly explain the difference between a service registry and a repository.
10. Why are massively scaled applications often more cost-effective in the cloud? Provide one example of a massively scaled SaaS offering.

### Short-Answer Quiz - Answer Key

1. Cloud computing is the delivery of on-demand computing services over the internet. The three core characteristics mentioned are on-demand, scalable, and pay-as-you-go.
2. IaaS provides fundamental compute, storage, and networking resources where the user manages the operating system and applications (e.g., virtual machines). SaaS provides ready-to-use applications over the internet, managed by the provider (e.g., email services like Yahoo Mail).
3. The Shared Responsibility Model outlines that the cloud provider is responsible for the security of the cloud infrastructure, while the customer is responsible for the security in the cloud, including their data and applications. For example, AWS secures its data centers, while the customer configures access controls to their EC2 instances.
4. Virtualization is the creation of a software-based representation of IT resources like servers or storage. A hypervisor is the software that creates and manages virtual machines by abstracting the underlying physical hardware.
5. Docker is a platform for building, shipping, and running applications in isolated environments called containers. docker build creates an image from a Dockerfile, docker run starts a container from an image, and docker ps lists currently running containers.
6. Amazon RDS is a managed relational database service in the cloud. Relational databases (SQL) organize data in tables with fixed schemas, while NoSQL databases are designed for specific data models with flexible schemas.
7. The 'pay-as-you-go' model means users only pay for the cloud resources they consume, similar to utility services. This is a benefit as it eliminates the need for large upfront capital expenditures and allows for cost optimization based on actual usage.
8. Three core features of Linux suitable for the cloud are its open-source nature (customizable), portability (runs on various hardware), and stability (reliable for long-term use).
9. A service in cloud computing is a task or functionality that has been packaged to be delivered to customers in a consistent and repeatable manner. A service registry is a catalog of available services and their locations, while a service repository is a central storage for software components used to build services.
10. Massively scaled applications achieve cost efficiencies by serving a large number of users doing the same thing, allowing providers to keep the cost per user very low due to economies of scale. An example of a massively scaled SaaS offering is Yahoo Mail.

### Essay Format Questions

1. Discuss the evolution from traditional IT infrastructure to cloud computing, highlighting the key drivers and benefits that have led to its widespread adoption. Consider the perspectives of both technical teams and business stakeholders.
2. Compare and contrast the three primary cloud service models: Infrastructure as a Service (IaaS), Platform as a Service (PaaS), and Software as a Service (SaaS). Provide detailed examples of use cases for each model, and analyze the level of management and control offered to the user in each.
3. Evaluate the significance of virtualization and containerization technologies in the context of cloud computing. Analyze their respective benefits and drawbacks, and discuss scenarios where one technology might be preferred over the other.
4. Analyze the challenges and risks associated with cloud computing adoption, with a particular focus on security and governance. Discuss the importance of the Shared Responsibility Model and suggest strategies for organizations to mitigate these concerns effectively.
5. Discuss the economic implications of cloud computing for businesses. Analyze the 'pay-as-you-go' model, the potential for cost savings, and other financial considerations involved in migrating to and operating in the cloud, including the concepts of capital expenditure reduction and economies of scale.

### Glossary of Key Terms

- **Cloud Computing**: The delivery of on-demand computing services—such as servers, storage, databases, networking, software, analytics, and intelligence—over the Internet ("the cloud").
- **IaaS (Infrastructure as a Service)**: A cloud service model that provides fundamental compute, storage, and networking resources on demand, allowing users to install and run operating systems and applications.
- **PaaS (Platform as a Service)**: A cloud service model that provides a platform allowing customers to develop, run, and manage applications without the complexity of managing the underlying infrastructure.
- **SaaS (Software as a Service)**: A cloud service model where a software application is hosted by a service provider and made available to customers over a network, typically the internet.
- **FaaS (Function as a Service)**: An event-driven, serverless compute execution model where the cloud provider dynamically manages the allocation and provisioning of servers.
- **Virtualization**: The creation of a software-based, or virtual, representation of something, such as computer hardware, operating systems, storage devices, or network resources.
- **Hypervisor**: Software that creates and runs virtual machines (VMs). It allows one host computer to support multiple guest VMs by sharing its resources, such as memory and processing.
- **Containerization**: A lightweight form of virtualization at the application level, where applications and their dependencies are packaged into isolated units called containers that can run consistently across different environments.
- **Docker**: A popular platform for building, shipping, and running containerized applications.
- **Dockerfile**: A text file containing instructions on how to build a Docker image.
- **Image (Docker)**: A lightweight, standalone, executable package that includes everything needed to run a piece of software, including the code, runtime, libraries, environment variables, and configuration files.
- **Container (Docker)**: A runnable instance of a Docker image.
- **Linux**: An open-source Unix-like operating system kernel. Due to its flexibility and open nature, it is widely used in cloud environments.
- **Open Source**: Software with source code that is freely available and can be modified and distributed by anyone.
- **Multi-tenancy**: An architecture where a single instance of a software application serves multiple customers. Each customer's data is isolated and remains invisible to other tenants.
- **Elasticity (Cloud)**: The ability of a cloud computing resource to dynamically expand or contract to match the workload demand.
- **Scalability (Cloud)**: The capability of a system, network, or architecture to handle a growing amount of work in a graceful manner or its capacity to be readily enlarged.
- **Pay-as-you-go**: A pricing model where users are charged based on their actual consumption of resources.
- **Shared Responsibility Model**: A security framework that defines the security obligations of the cloud provider and the customer.
- **SOA (Service-Oriented Architecture)**: An architectural style that structures an application as a collection of loosely coupled services.
- **Service Registry**: A database or directory that lists available network services, their locations, and their interfaces.
- **Service Repository**: A central location for storing and managing reusable software components and services.
- **Massively Scaled Applications**: Applications designed to handle a very large number of concurrent users and vast amounts of data, often leveraging the elasticity and scalability of the cloud.
- **Relational Database (SQL)**: A database that organizes data into tables with rows and columns, using structured query language (SQL) for data management.
- **NoSQL**: A category of non-relational databases that do not adhere to the traditional relational model and often provide flexible schemas for modern applications.
- **VDI (Virtual Desktop Infrastructure)**: A technology that hosts desktop operating systems and applications on a central server in a data center, allowing users to access them remotely from various devices.
- **API (Application Programming Interface)**: A set of rules and protocols that allows different software applications to communicate and exchange data with each other.
- **Cost Management (Cloud)**: The process of planning, monitoring, and controlling the expenses associated with cloud resources and services.
- **Economies of Scale**: The cost advantages that enterprises obtain due to their scale of operation, with cost per unit of output generally decreasing with increasing scale.
- **Capital Expenditure (CapEx)**: Funds used by a company to acquire, upgrade, and maintain physical assets such as property, plant, buildings, technology, or equipment.
- **Metadata**: Data that provides information about other data.
