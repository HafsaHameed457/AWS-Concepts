# AWS-Concepts
I am making this repository for the easy access to all the knowledge and revise it in one go. 



## Overview

Data is mostly used in cloud in all parts of the world. Question here arises is that what is cloud?



## What is a Cloud?
Cloud is a global network of servers that are located in different parts of the world acting as one massive hard drive. They are accessible over the internet. 

In today's world everything we are using from watching netflix to storing our data in gmail, everything is based on cloud technologies.

## Backing up data

When we backup our data it is sent to all servers across the globe. I can then access this data by connecting to the internet.

In short I can access my data anywhere and anytime.

## Risks related to cloud

1. My data is kept online, but what if I do not have internet accessibility??

2. Online data is exposed to many cyber attacks.

3. We do not have much power on our data as it is stored and managed by some third party.

## World without cloud

In early 2000s when cloud technologies were not common it was very difficult to start a business.

1. First we had to setup a complete infrastructure to handle our online services.

2. After this heavy investment on setting up we have tp spent a lot of money to manage the human resource to maintain and manage it.

3. Initially we have no idea about the size of the required setup and over the time it becomes very difficult to upscale or down scale it.

4. After all this very little time was left to focus on business.

## What is cloud computing?

Cloud computing is the delivery of computing services—like storage, databases, and processing power—over the internet, allowing users to access resources on-demand without managing physical hardware.

## Advantages of cloud computing

1. Easy scalability

2. Pay as you go.

3. More maintenance provided.

4. Robust disaster recovery measures.

5. More data security

6. Managing server.

7. Rent servers

8. No hidden charges.

9. Resources reside on some remote data center.



## What is a cloud provider?

A cloud provider is a company that offers cloud computing services, such as storage, processing power, and software, over the internet. Examples include AWS, Microsoft Azure, and Google Cloud.

## AWS

AWS (Amazon Web Services) is a leading cloud platform that provides a wide range of on-demand computing services, such as storage, databases, and machine learning, allowing businesses to scale and innovate quickly without managing physical servers. It offers 220+ services.

## Other cloud providers

Other major cloud providers include:

1. Microsoft Azure

2. Google Cloud Platform (GCP)

3. IBM Cloud

4. Oracle Cloud

5. Alibaba Cloud

## Types of service models in AWS

1. IaaS (Infrastructure as a Service): AWS provides virtualized computing resources over the internet. With services like Amazon EC2 (Elastic Compute Cloud), users can rent servers, storage, and networking infrastructure, managing the OS and applications.

2. PaaS (Platform as a Service): AWS offers platforms for building, deploying, and managing applications without managing underlying hardware. AWS Elastic Beanstalk is an example, where users can deploy web applications without handling server setup and maintenance.

3. SaaS (Software as a Service): AWS offers software applications hosted and maintained by AWS, accessible over the internet. Examples include Amazon Chime (video conferencing) and Amazon WorkSpaces (virtual desktops).

## Types of deployment models

! Here’s a look at each cloud deployment model with examples:

1. Public Cloud:

Example: AWS (Amazon Web Services), Microsoft Azure, Google Cloud Platform (GCP).

Description: Resources are provided and managed by a cloud provider and shared among multiple users. For example, a business can use AWS to host their website, leveraging AWS’s global data centers without managing any hardware.

2. Private Cloud:

Example: AWS Outposts, VMware on AWS, or an on-premises setup with OpenStack.

Description: A private cloud offers dedicated resources for a single organization. For instance, a bank might use AWS Outposts to set up AWS infrastructure in its own data centers, maintaining full control over data and security while using AWS tools.

3. Hybrid Cloud:

Example: AWS with on-premises systems, or Microsoft Azure with Azure Stack.

Description: Combines public and private cloud resources, allowing data and applications to move between them. For example, a healthcare organization may store sensitive patient data on-premises but use AWS for scalable, non-sensitive data processing.

4. Multi-Cloud:

Example: Using both AWS and Google Cloud, or combining AWS for computing and Azure for AI capabilities.

Description: Involves using multiple cloud providers to prevent vendor lock-in or optimize costs. For instance, a tech company might run its databases on AWS for reliability but use GCP’s machine learning services for advanced AI features.

## Myths related to cloud

1. Cloud is not secure: Many believe that cloud computing is less secure than on-premises solutions. In reality, major cloud providers (like AWS, Azure, and Google Cloud) offer robust security features, such as encryption, compliance certifications, and dedicated security teams.

2. Cloud is only for large businesses: While cloud services provide scalability for large organizations, they are also highly beneficial for small and medium-sized businesses, offering cost-effective solutions, scalability, and flexibility.

3. Cloud services are always cheaper: While cloud computing can save on infrastructure and maintenance costs, the total cost depends on usage, the chosen services, and configurations. Poor management can lead to unexpected expenses.

4. Moving to the cloud is a simple process: Migrating to the cloud can be complex, requiring careful planning, security considerations, and possibly re-architecting applications. It’s not always a straightforward process.

5. Cloud means no need for IT staff: Cloud providers manage the infrastructure, but businesses still need skilled IT professionals for tasks like cloud architecture, security, and monitoring.

6. Cloud is always available and reliable: While cloud services are highly available, they can still experience downtime due to outages, network issues, or provider failures. It's important to have disaster recovery plans.

7. Cloud eliminates the need for backups: Cloud services often include data redundancy, but it’s still important to back up critical data to prevent data loss due to unforeseen issues like human error or security breaches.

## Careers related to cloud


Here are some common cloud careers and what each does:

1. Cloud Architect: Designs and manages cloud infrastructure and architecture for scalability and security.

2. Cloud Engineer: Implements and maintains cloud services, ensuring the proper configuration and optimization of cloud resources.

3. Cloud Security Specialist: Focuses on securing cloud environments, managing risks, and protecting data.

4. Cloud Developer: Builds applications and services that are hosted and run on cloud platforms.

5. Cloud Consultant: Advises organizations on cloud adoption strategies and solutions to meet business needs.

6. Cloud Systems Administrator: Manages cloud-based systems, ensuring smooth operation and troubleshooting issues.

7. Cloud DevOps Engineer: Automates and manages cloud infrastructure for continuous integration, deployment, and monitoring.

8. Cloud Product Manager: Oversees the development and lifecycle of cloud products, aligning them with customer needs and business goals.

9. Cloud Data Engineer: Designs and manages data pipelines and data storage solutions in the cloud.

10. Cloud Sales Specialist: Sells cloud services and solutions to customers, understanding their needs and tailoring products to them


## AWS Infrastructure

In AWS, the infrastructure is organized into Regions, Availability Zones, and Local Zones to ensure high availability, fault tolerance, and low-latency access for global users. Here’s a breakdown of each:

1. Regions
2. 
It is a data center located at a certain place. Can be in a country or in a continent.

- An AWS Region is a physical location in a specific geographic area that consists of multiple data centers.

- Each Region is independent, isolated, and offers a variety of AWS services.

- AWS Regions are spread across the world to allow users to choose where their data and applications are hosted, improving compliance with data residency requirements and reducing latency by being closer to end users.

2. Availability Zones (AZs)

These are seperate physical location within a region. They provide redundancy of data to avoid failures. They are isolated from one another.

- An Availability Zone (AZ) is one or more discrete data centers with independent power, cooling, and networking within an AWS Region.
  
- Each Region has at least two or more AZs (some have as many as six), providing redundancy in case one data center goes down.
  
- AZs within a Region are connected via low-latency, high-speed networking links, allowing for synchronous replication and load balancing across zones.
  
- Users can distribute applications across multiple AZs to ensure high availability and fault tolerance.

3. Local Zones

These are extensions close to specific user for faster data delivery and service. Helps in ultra low latency.

- Local Zones are extensions of AWS Regions that bring compute, storage, and other services closer to major metropolitan areas or specific locations.

- They are ideal for applications requiring very low latency to end users or on-premises resources in specific locations, like gaming, media, real-time streaming, and machine learning.

- Local Zones provide a subset of AWS services and have a direct connection to their parent AWS Region.

- Unlike AZs, Local Zones are not always close to their parent Region, which allows AWS to serve customers who need low-latency access in areas where full Regions or AZs might not be available.

## Core services

These are essential building blocks or primary areas of functionality AWS provided for cloud computing. 

- Fundamental tools comapnies use to run their apps and manage their infrastructure in cloud. 

## Domain 

It is a broad category of related services. Actually a group of interrelated services. 

- Computer domain has services to run apps.

- Storage domain saves and retrieves data.

