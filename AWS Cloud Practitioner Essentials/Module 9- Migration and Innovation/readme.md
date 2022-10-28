# Module 9 introduction
Learning objectives

In this module, you will learn how to:

1. Understand migration and innovation in the AWS Cloud.
2. Summarize the AWS Cloud Adoption Framework (AWS CAF). 
3. Summarize the six key factors of a cloud migration strategy.
4. Describe the benefits of AWS data migration solutions, such as AWS Snowcone, AWS Snowball, and AWS Snowmobile.
5. Summarize the broad scope of innovative solutions that AWS offers.

# AWS Cloud Adoption Framework (AWS CAF)
## Six core perspectives of the Cloud Adoption Framework

At the highest level, the AWS Cloud Adoption Framework (AWS CAF) organizes guidance into six areas of focus, called Perspectives. Each Perspective addresses distinct responsibilities. The planning process helps the right people across the organization prepare for the changes ahead.

In general, the Business, People, and Governance Perspectives focus on business capabilities, whereas the Platform, Security, and Operations Perspectives focus on technical capabilities.

To learn more, select the + symbol next to each category.
### 1. Business Perspective 
The Business Perspective ensures that IT aligns with business needs and that IT investments link to key business results.

Use the Business Perspective to create a strong business case for cloud adoption and prioritize cloud adoption initiatives. Ensure that your business strategies and goals align with your IT strategies and goals.

Common roles in the Business Perspective include: 

1. Business managers
2. Finance managers
3. Budget owners
4. Strategy stakeholders

### 2. People Perspective  
The People Perspective supports development of an organization-wide change management strategy for successful cloud adoption.

Use the People Perspective to evaluate organizational structures and roles, new skill and process requirements, and identify gaps. This helps prioritize training, staffing, and organizational changes.

Common roles in the People Perspective include: 

1. Human resources
2. Staffing
3. People managers

### 3. Governance Perspective 
The Governance Perspective focuses on the skills and processes to align IT strategy with business strategy. This ensures that you maximize the business value and minimize risks.

Use the Governance Perspective to understand how to update the staff skills and processes necessary to ensure business governance in the cloud. Manage and measure cloud investments to evaluate business outcomes.

Common roles in the Governance Perspective include: 

1. Chief Information Officer (CIO)
2. Program managers
3. Enterprise architects
4. Business analysts
5. Portfolio managers

### 4. Platform Perspective 
The Platform Perspective includes principles and patterns for implementing new solutions on the cloud, and migrating on-premises workloads to the cloud.

Use a variety of architectural models to understand and communicate the structure of IT systems and their relationships. Describe the architecture of the target state environment in detail.

Common roles in the Platform Perspective include: 

1. Chief Technology Officer (CTO)
2. IT managers
3. Solutions architects

### 5. Security Perspective 
The Security Perspective ensures that the organization meets security objectives for visibility, auditability, control, and agility. 

Use the AWS CAF to structure the selection and implementation of security controls that meet the organization’s needs.

Common roles in the Security Perspective include: 

1. Chief Information Security Officer (CISO)
2. IT security managers
3. IT security analysts

### 6. Operations Perspective 
The Operations Perspective helps you to enable, run, use, operate, and recover IT workloads to the level agreed upon with your business stakeholders.

Define how day-to-day, quarter-to-quarter, and year-to-year business is conducted. Align with and support the operations of the business. The AWS CAF helps these stakeholders define current operating procedures and identify the process changes and training needed to implement successful cloud adoption.

Common roles in the Operations Perspective include: 

1. IT operations managers
2. IT support managers

# Migration strategies
## 6 strategies for migration

When migrating applications to the cloud, six of the most common migration strategies that you can implement are:

1. Rehosting
2. Replatforming
3. Refactoring/re-architecting
4. Repurchasing
5. Retaining
6. Retiring

# AWS Snow Family members

The AWS Snow Family is a collection of physical devices that help to physically transport up to exabytes of data into and out of AWS. 

AWS Snow Family is composed of AWS Snowcone, AWS Snowball, and AWS Snowmobile. 

Illustration of the three AWS Snow Family members: AWS Snowcone, AWS Snowball, and AWS Snowmobile
These devices offer different capacity points, and most include built-in computing capabilities. AWS owns and manages the Snow Family devices and integrates with AWS security, monitoring, storage management, and computing capabilities.  

1. AWS Snowcone is a small, rugged, and secure edge computing and data transfer device. 
It features 2 CPUs, 4 GB of memory, and 8 TB of usable storage.

2. AWS Snowball offers two types of devices:

Snowball Edge Storage Optimized devices are well suited for large-scale data migrations and recurring transfer workflows, in addition to local computing with higher capacity needs. 
Storage: 80 TB of hard disk drive (HDD) capacity for block volumes and Amazon S3 compatible object storage, and 1 TB of SATA solid state drive (SSD) for block volumes. 
Compute: 40 vCPUs, and 80 GiB of memory to support Amazon EC2 sbe1 instances (equivalent to C5).
Snowball Edge Compute Optimized provides powerful computing resources for use cases such as machine learning, full motion video analysis, analytics, and local computing stacks. 
Storage: 42-TB usable HDD capacity for Amazon S3 compatible object storage or Amazon EBS compatible block volumes and 7.68 TB of usable NVMe SSD capacity for Amazon EBS compatible block volumes. 
Compute: 52 vCPUs, 208 GiB of memory, and an optional NVIDIA Tesla V100 GPU. Devices run Amazon EC2 sbe-c and sbe-g instances, which are equivalent to C5, M5a, G3, and P3 instances.

3. AWS Snowmobile is an exabyte-scale data transfer service used to move large amounts of data to AWS. 
You can transfer up to 100 petabytes of data per Snowmobile, a 45-foot long ruggedized shipping container, pulled by a semi trailer truck.


# Innovate with AWS Services

When examining how to use AWS services, it is important to focus on the desired outcomes. You are properly equipped to drive innovation in the cloud if you can clearly articulate the following conditions: 

1. The current state
2. The desired state
3. The problems you are trying to solve
Consider some of the paths you might explore in the future as you continue on your cloud journey. 

# Module 9 summary
In Module 9, you learned about the following concepts:

1. The AWS Cloud Adoption Framework
2. The six strategies for migration
3. The AWS Snow Family
4. Innovation with AWS services

# Additional resources

To learn more about the concepts that were explored in Module 9, review these resources.

1. Migration & Transfer on AWS
2. A Process for Mass Migrations to the Cloud
3. 6 Strategies for Migrating Applications to the Cloud
4. AWS Cloud Adoption Framework
5. AWS Fundamentals: Core Concepts
6. AWS Cloud Enterprise Strategy Blog
7. Modernizing with AWS Blog
8. AWS Customer Stories: Data Center Migration

