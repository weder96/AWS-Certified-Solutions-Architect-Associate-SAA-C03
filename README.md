# **AWS Certified Solutions Architect - Associate (SAA-C03)**

[**AWS Certified Solutions Architect - Associate (SAA-C03) Exam Guide**](https://d1.awsstatic.com/training-and-certification/docs-sa-assoc/AWS-Certified-Solutions-Architect-Associate_Exam-Guide_C03.pdf) {:target="_blank"} 


This study guide will help you pass the newer AWS Certified Solutions Architect - Associate exam. Ideally, you should reference this guide while working through the following material:

1. Stephane Maarek's [Ultimate AWS Certified Solutions Architect Associate 2021 course](https://www.udemy.com/course/aws-certified-solutions-architect-associate-saa-c03/?couponCode=DEC_22_GET_STARTED) (permanent discount available through this link) 
A Cloud Guru's [AWS Certified Solutions Architect Associate SAA-C02](https://acloud.guru/learn/aws-certified-solutions-architect-associate) course

2. The FAQs for the most critical services, included in the recommended reading list below

3. Tutorials Dojo's [AWS Certified Solutions Architect Associate](https://www.udemy.com/course/aws-certified-solutions-architect-associate-amazon-practice-exams-saa-c03/) Practice Exams

4. Andrew Brown's [AWS Certified Solutions Architect](https://www.youtube.com/watch?v=Ia-UEYYR44s) - Associate 2020 (PASS THE EXAM!) | Ad-Free Course

Notes: If at any point you find yourself feeling uncertain of your progress and in need of more time, you can postpone your AWS exam date. Be sure to also keep up with the ongoing discussions in [r/AWSCertifications](https://www.reddit.com/r/AWSCertifications/) as you will find relevant exam tips, studying material, and advice from other exam takers. 

Before experimenting with AWS, it's very important to be sure that you know what is [free tier](https://aws.amazon.com/free/?all-free-tier.sort-by=item.additionalFields.SortRank&all-free-tier.sort-order=asc&awsf.Free%20Tier%20Types=*all&awsf.Free%20Tier%20Categories=*all) and what isn't. 

Relevant Free Tier FAQs can be found here. Finally, Udemy often has their courses go on sale from time to time. It might be worth waiting to purchase either the Tutorial Dojo practice exam or Stephane Maarek's course depending on how urgently you need the content.




# Introduction
The AWS Certified Solutions Architect - Associate (SAA-C03) exam is intended for individuals who perform
in a solutions architect role. The exam validates a candidate’s ability to use AWS technologies to design
solutions based on the AWS Well-Architected Framework.

**The exam also validates a candidate’s ability to complete the following tasks:**
- Design solutions that incorporate AWS services to meet current business requirements and future
projected needs
- Design architectures that are secure, resilient, high-performing, and cost-optimized
- Review existing solutions and determine improvements

# Target candidate description
The target candidate should have at least 1 year of hands-on experience designing cloud solutions that use
AWS services.
For a detailed list of specific tools and technologies that might be covered on the exam, as well as lists of
in-scope and out-of-scope AWS services, refer to the Appendix.

# Exam content
## Response types
There are two types of questions on the exam:
- **Multiple choice:** Has one correct response and three incorrect responses (distractors)
- **Multiple response:** Has two or more correct responses out of five or more response options

Select one or more responses that best complete the statement or answer the question. Distractors, or
incorrect answers, are response options that a candidate with incomplete knowledge or skill might choose.
Distractors are generally plausible responses that match the content area.
Unanswered questions are scored as incorrect; there is no penalty for guessing. The exam includes
50 questions that will affect your score.

## Unscored content
The exam includes **15 unscored questions that do not affect your score.** AWS collects information about
candidate performance on these unscored questions to evaluate these questions for future use as scored
questions. These unscored questions are not identified on the exam.


## Exam results
The AWS Certified Solutions Architect - Associate exam is a pass or fail exam. The exam is scored against a
minimum standard established by AWS professionals who follow certification industry best practices and
guidelines.

Your results for the exam are reported as a scaled score of 100–1,000. The minimum passing score is 720.

Your score shows how you performed on the exam as a whole and whether or not you passed. Scaled
scoring models help equate scores across multiple exam forms that might have slightly different difficulty
levels.

Your score report could contain a table of classifications of your performance at each section level. 

This information provides general feedback about your exam performance. The exam uses a compensatory
scoring model, which means that you do not need to achieve a passing score in each section. 

You need to pass only the overall exam.

Each section of the exam has a specific weighting, so some sections have more questions than other
sections have. The table contains general information that highlights your strengths and weaknesses. 

Use caution when interpreting section-level feedback. Candidates who pass the exam will not receive this
additional information.

## Content outline
This exam guide includes weightings, test domains, and task statements for the exam. It is not a
comprehensive listing of the content on the exam. However, additional context for each of the task
statements is available to help guide your preparation for the exam. The following table lists the main
content domains and their weightings. The table precedes the complete exam content outline, which
includes the additional context. The percentage in each domain represents only scored 


|Domain |% of Exam|
|-------|---------|
|Domain 1: Design Secure Architectures |30%|
|Domain 2: Design Resilient Architectures |26%|
|Domain 3: Design High-Performing Architectures |24%|
|Domain 4: Design Cost-Optimized Architectures |20%|
|TOTAL |100%|


-------------------------------------------------------------------------------------------------------
## Domain 1: Design Secure Architectures
**Task Statement 1: Design secure access to AWS resources.**

### Knowledge of:
- [Access controls and management across multiple accounts](https://www.stormit.cloud/blog/aws-organizations-how-to-manage-multiple-aws-accounts/)
- [AWS federated access and identity services (for example, AWS Identity and Access Management [IAM], AWS Single Sign-On [AWS SSO])](https://aws.amazon.com/identity/federation/)
- [AWS global infrastructure (for example, Availability Zones, AWS Regions)](https://github.com/weder96/aws-certification-learning/tree/main/module-3)
- [AWS security best practices (for example, the principle of least privilege)](https://github.com/weder96/aws-certification-learning/tree/main/module-4)
- [The AWS shared responsibility model](https://github.com/weder96/aws-certification-learning/tree/main/module-1#section-05)

### Skills in:
- Applying AWS security best practices to IAM users and root users (for example, multi-factor
authentication [MFA])
- Designing a flexible authorization model that includes IAM users, groups, roles, and policies
- Designing a role-based access control strategy (for example, AWS Security Token Service [AWS
STS], role switching, cross-account access)
- Designing a security strategy for multiple AWS accounts (for example, AWS Control Tower,
service control policies [SCPs])
- Determining the appropriate use of resource policies for AWS services
- Determining when to federate a directory service with IAM roles

**Task Statement 2: Design secure workloads and applications.**
### Knowledge of:
- [Application configuration and credentials security](https://docs.aws.amazon.com/IAM/latest/UserGuide/security-creds.html)
- [AWS service endpoints](https://docs.aws.amazon.com/general/latest/gr/rande.html)
- [Control ports, protocols, and network traffic on AWS](https://blowstack.com/blog/control-ports-protocols-and-network-traffic-on-aws)
- [Secure application access](https://blowstack.com/blog/secure-application-access-in-aws)
- [Security services with appropriate use cases (for example, Amazon Cognito, Amazon GuardDuty, Amazon Macie)](https://github.com/weder96/aws-certification-learning/tree/main/module-4)
- [Threat vectors external to AWS (for example, DDoS, SQL injection)](https://blowstack.com/blog/threat-vectors-external-to-aws)

### Skills in:
- Designing VPC architectures with security components (for example, security groups, route tables, network ACLs, NAT gateways)
- Determining network segmentation strategies (for example, using public subnets and private subnets)
vIntegrating AWS services to secure applications (for example, AWS Shield, AWS WAF, AWS SSO, AWS Secrets Manager)
- Securing external network connections to and from the AWS Cloud (for example, VPN, AWS Direct Connect)


**Task Statement 3: Determine appropriate data security controls.**
### Knowledge of:
- Data access and governance
- [Data recovery](https://aws.amazon.com/backup-restore/)
- Data retention and classification
- Encryption and appropriate key management

### Skills in:
- Aligning AWS technologies to meet compliance requirements
- Encrypting data at rest (for example, AWS Key Management Service [AWS KMS])
- Encrypting data in transit (for example, AWS Certificate Manager [ACM] using TLS)
- Implementing access policies for encryption keys
- Implementing data backups and replications
- Implementing policies for data access, lifecycle, and protection
- Rotating encryption keys and renewing certificates
-------------------------------------------------------------------------------------------------------

## Domain 2: Design Resilient Architectures
**Task Statement 1: Design scalable and loosely coupled architectures.**
### Knowledge of:
- [API creation and management (for example, Amazon API Gateway, REST API)](https://blowstack.com/blog/api-creation-and-management-in-aws)
- AWS managed services with appropriate use cases (for example, AWS Transfer Family, Amazon Simple Queue Service [Amazon SQS], Secrets Manager)
- [Caching strategies](https://aws.amazon.com/pt/caching/)
- [Design principles for microservices (for example, stateless workloads compared with stateful workloads)](https://blowstack.com/blog/design-principles-for-microservices-in-aws)
- [Event-driven architectures](https://aws.amazon.com/pt/event-driven-architecture/)
- [Horizontal scaling and vertical scaling](https://github.com/weder96/aws-certification-learning/tree/main/module-10)
- [How to appropriately use edge accelerators (for example, content delivery network [CDN])](https://aws.amazon.com/pt/products/networking/)
- [How to migrate applications into containers](https://blowstack.com/blog/how-to-migrate-applications-into-containers-in-aws)
- [Load balancing concepts (for example, Application Load Balancer)](https://aws.amazon.com/pt/what-is/load-balancing/#:~:text=Load%20balancing%20is%20the%20method,a%20fast%20and%20reliable%20manner.)
- [Multi-tier architectures](https://docs.aws.amazon.com/whitepapers/latest/serverless-multi-tier-architectures-api-gateway-lambda/introduction.html)
- [Queuing and messaging concepts (for example, publish/subscribe)](https://github.com/weder96/aws-certification-learning/tree/main/module-12)
- [Serverless technologies and patterns (for example, AWS Fargate, AWS Lambda)](https://github.com/weder96/aws-certification-learning/tree/main/module-14)
- [Storage types with associated characteristics (for example, object, file, block)](https://github.com/weder96/aws-certification-learning/tree/main/module-7)
- [The orchestration of containers (for example, Amazon Elastic Container Service [Amazon ECS], Amazon Elastic Kubernetes Service [Amazon EKS])](https://github.com/weder96/aws-certification-learning/tree/main/module-18)
- [When to use read replicas](https://aws.amazon.com/pt/rds/features/read-replicas/)
- [Workflow orchestration (for example, AWS Step Functions)](https://docs.aws.amazon.com/whitepapers/latest/best-practices-building-data-lake-for-games/workflow-orchestration.html)

### Skills in:
- Designing event-driven, microservice, and/or multi-tier architectures based on requirements
- Determining scaling strategies for components used in an architecture design
- Determining the AWS services required to achieve loose coupling based on requirements
- Determining when to use containers
- Determining when to use serverless technologies and patterns
- Recommending appropriate compute, storage, networking, and database technologies based on requirements
- Using purpose-built AWS services for workloads

**Task Statement 2: Design highly available and/or fault-tolerant architectures.**
### Knowledge of:
- [AWS global infrastructure (for example, Availability Zones, AWS Regions, Amazon Route 53)](https://aws.amazon.com/pt/about-aws/global-infrastructure/)
- [AWS managed services with appropriate use cases (for example, Amazon Comprehend, Amazon Polly)](https://github.com/weder96/aws-certification-learning/tree/main/module-19)
- [Basic networking concepts (for example, route tables)](https://github.com/weder96/aws-certification-learning/tree/main/module-5)
- [Disaster recovery (DR) strategies (for example, backup and restore, pilot light, warm standby, active-active failover, recovery point objective [RPO], recovery time objective [RTO])](https://d1.awsstatic.com/whitepapers/aws-disaster-recovery.pdf)
- Distributed design patterns
- Failover strategies
- Immutable infrastructure
- Load balancing concepts (for example, Application Load Balancer)
- Proxy concepts (for example, Amazon RDS Proxy)
- Service quotas and throttling (for example, how to configure the service quotas for a workload in a standby environment)
- Storage options and characteristics (for example, durability, replication)
- Workload visibility (for example, AWS X-Ray)

### Skills in:
- Determining automation strategies to ensure infrastructure integrity
- Determining the AWS services required to provide a highly available and/or fault-tolerant architecture across AWS Regions or Availability Zones
- Identifying metrics based on business requirements to deliver a highly available solution
- Implementing designs to mitigate single points of failure
- Implementing strategies to ensure the durability and availability of data (for example, backups)
- Selecting an appropriate DR strategy to meet business requirements
- Using AWS services that improve the reliability of legacy applications and applications not built for the cloud (for example, when application changes are not possible)
- Using purpose-built AWS services for workloads

-------------------------------------------------------------------------------------------------------

## Domain 3: Design High-Performing Architectures
**Task Statement 1: Determine high-performing and/or scalable storage solutions.**
### Knowledge of:
- Hybrid storage solutions to meet business requirements
- Storage services with appropriate use cases (for example, Amazon S3, Amazon Elastic File System [Amazon EFS], Amazon Elastic Block Store [Amazon EBS])
- Storage types with associated characteristics (for example, object, file, block)

### Skills in:
- Determining storage services and configurations that meet performance demands
- Determining storage services that can scale to accommodate future needs

**Task Statement 2: Design high-performing and elastic compute solutions.**
### Knowledge of:
- AWS compute services with appropriate use cases (for example, AWS Batch, Amazon EMR, Fargate)
- Distributed computing concepts supported by AWS global infrastructure and edge services
- Queuing and messaging concepts (for example, publish/subscribe)
- Scalability capabilities with appropriate use cases (for example, Amazon EC2 Auto Scaling, AWS Auto Scaling)
- Serverless technologies and patterns (for example, Lambda, Fargate)
- The orchestration of containers (for example, Amazon ECS, Amazon EKS)

### Skills in:
- Decoupling workloads so that components can scale independently
- Identifying metrics and conditions to perform scaling actions
- Selecting the appropriate compute options and features (for example, EC2 instance types) to meet business requirements
- Selecting the appropriate resource type and size (for example, the amount of Lambda memory) to meet business requirements

**Task Statement 3: Determine high-performing database solutions.**
### Knowledge of:
- AWS global infrastructure (for example, Availability Zones, AWS Regions)
- Caching strategies and services (for example, Amazon ElastiCache)
- Data access patterns (for example, read-intensive compared with write-intensive)
- Database capacity planning (for example, capacity units, instance types, Provisioned IOPS)
- Database connections and proxies
- Database engines with appropriate use cases (for example, heterogeneous migrations, homogeneous migrations)
- Database replication (for example, read replicas)
- Database types and services (for example, serverless, relational compared with non-relational, in-memory

### Skills in:
- Configuring read replicas to meet business requirements
- Designing database architectures
- Determining an appropriate database engine (for example, MySQL compared with PostgreSQL)
- Determining an appropriate database type (for example, Amazon Aurora, Amazon DynamoDB)
- Integrating caching to meet business requirements

**Task Statement 4: Determine high-performing and/or scalable network architectures.**
### Knowledge of:
- Edge networking services with appropriate use cases (for example, Amazon CloudFront, AWS Global Accelerator)
- How to design network architecture (for example, subnet tiers, routing, IP addressing)
- Load balancing concepts (for example, Application Load Balancer)
- Network connection options (for example, AWS VPN, Direct Connect, AWS PrivateLink)

### Skills in:
- Creating a network topology for various architectures (for example, global, hybrid, multi-tier)
- Determining network configurations that can scale to accommodate future needs
- Determining the appropriate placement of resources to meet business requirements
- Selecting the appropriate load balancing strategy

**Task Statement 5: Determine high-performing data ingestion and transformation solutions.**
### Knowledge of:
- Data analytics and visualization services with appropriate use cases (for example, Amazon Athena, AWS Lake Formation, Amazon QuickSight)
- Data ingestion patterns (for example, frequency)
- Data transfer services with appropriate use cases (for example, AWS DataSync, AWS Storage Gateway)
- Data transformation services with appropriate use cases (for example, AWS Glue)
- Secure access to ingestion access points
- Sizes and speeds needed to meet business requirements
- Streaming data services with appropriate use cases (for example, Amazon Kinesis)

### Skills in:
- Building and securing data lakes
- Designing data streaming architectures
- Designing data transfer solutions
- Implementing visualization strategies
- Selecting appropriate compute options for data processing (for example, Amazon EMR)
- Selecting appropriate configurations for ingestion
- Transforming data between formats (for example, .csv to .parquet)

-------------------------------------------------------------------------------------------------------

## Domain 4: Design Cost-Optimized Architectures
**Task Statement 1: Design cost-optimized storage solutions.**
### Knowledge of:
- Access options (for example, an S3 bucket with Requester Pays object storage)
- AWS cost management service features (for example, cost allocation tags, multi-account billing)
- AWS cost management tools with appropriate use cases (for example, AWS Cost Explorer, AWS Budgets, AWS Cost and Usage Report)
- AWS storage services with appropriate use cases (for example, Amazon FSx, Amazon EFS, Amazon S3, Amazon EBS)
- Backup strategies
- Block storage options (for example, hard disk drive [HDD] volume types, solid state drive [SSD] volume types)
- Data lifecycles
- Hybrid storage options (for example, DataSync, Transfer Family, Storage Gateway)
- Storage access patterns
- Storage tiering (for example, cold tiering for object storage)
- Storage types with associated characteristics (for example, object, file, block)

### Skills in:
- Designing appropriate storage strategies (for example, batch uploads to Amazon S3 compared with individual uploads)
- Determining the correct storage size for a workload
- Determining the lowest cost method of transferring data for a workload to AWS storage
- Determining when storage auto scaling is required
- Managing S3 object lifecycles
- Selecting the appropriate backup and/or archival solution
- Selecting the appropriate service for data migration to storage services
- Selecting the appropriate storage tier
- Selecting the correct data lifecycle for storage
- Selecting the most cost-effective storage service for a workload

**Task Statement 2: Design cost-optimized compute solutions.**
### Knowledge of:
- AWS cost management service features (for example, cost allocation tags, multi-account billing)
- AWS cost management tools with appropriate use cases (for example, Cost Explorer, AWS Budgets, AWS Cost and Usage Report)
- AWS global infrastructure (for example, Availability Zones, AWS Regions)
- AWS purchasing options (for example, Spot Instances, Reserved Instances, Savings Plans)
- Distributed compute strategies (for example, edge processing)
- Hybrid compute options (for example, AWS Outposts, AWS Snowball Edge)
- Instance types, families, and sizes (for example, memory optimized, compute optimized, virtualization)
- Optimization of compute utilization (for example, containers, serverless computing, microservices)
- Scaling strategies (for example, auto scaling, hibernation)

### Skills in:
- Determining an appropriate load balancing strategy (for example, Application Load Balancer [Layer 7] compared with Network Load Balancer [Layer 4] compared with Gateway Load Balancer)
- Determining appropriate scaling methods and strategies for elastic workloads (for example, horizontal compared with vertical, EC2 hibernation)
- Determining cost-effective AWS compute services with appropriate use cases (for example, Lambda, Amazon EC2, Fargate)
- Determining the required availability for different classes of workloads (for example, production workloads, non-production workloads)
- Selecting the appropriate instance family for a workload
- Selecting the appropriate instance size for a workload

**Task Statement 3: Design cost-optimized database solutions.**
### Knowledge of:
- AWS cost management service features (for example, cost allocation tags, multi-account billing)
- AWS cost management tools with appropriate use cases (for example, Cost Explorer, AWS Budgets, AWS Cost and Usage Report)
- Caching strategies
- Data retention policies
- Database capacity planning (for example, capacity units)
- Database connections and proxies
- Database engines with appropriate use cases (for example, heterogeneous migrations, homogeneous migrations)
- Database replication (for example, read replicas)
- Database types and services (for example, relational compared with non-relational, Aurora, DynamoDB)

**Task Statement 3: Design cost-optimized database solutions.**
### Knowledge of:
- AWS cost management service features (for example, cost allocation tags, multi-account billing)
- AWS cost management tools with appropriate use cases (for example, Cost Explorer, AWS Budgets, AWS Cost and Usage Report)
- Caching strategies
- Data retention policies
- Database capacity planning (for example, capacity units)
- Database connections and proxies
- Database engines with appropriate use cases (for example, heterogeneous migrations, homogeneous migrations)
- Database replication (for example, read replicas)
- Database types and services (for example, relational compared with non-relational, Aurora,DynamoDB)

-------------------------------------------------------------------------------------------------------

# Which key tools, technologies, and concepts might be covered on the exam?

The following is a non-exhaustive list of the tools and technologies that could appear on the exam. This list
is subject to change and is provided to help you understand the general scope of services, features, or
technologies on the exam. The general tools and technologies in this list appear in no particular order.
AWS services are grouped according to their primary functions. While some of these technologies will likely
be covered more than others on the exam, the order and placement of them in this list is no indication of
relative weight or importance:

- [Compute](https://github.com/weder96/aws-certification-learning/tree/main/module-6)
- [Cost management](https://github.com/weder96/aws-certification-learning/tree/main/module-2)
- [Database](https://github.com/weder96/aws-certification-learning/tree/main/module-8)
- [Disaster recovery](https://github.com/weder96/aws-certification-learning/tree/main/module-97#section_01)
- [High performance](https://github.com/weder96/aws-certification-learning/tree/main/module-97#section_03)
- [Management and governance](https://github.com/weder96/aws-certification-learning/tree/main/module-20)
- [Microservices and component decoupling](https://github.com/weder96/aws-certification-learning/tree/main/module-97#section_04)
- [Migration and data transfer](https://github.com/weder96/aws-certification-learning/tree/main/module-13)
- [Networking, connectivity, and content delivery](https://github.com/weder96/aws-certification-learning/tree/main/module-5)
- [Resiliency](https://github.com/weder96/aws-certification-learning/tree/main/module-97#section_02)
- [Security](https://github.com/weder96/aws-certification-learning/tree/main/module-4)
- [Serverless and event-driven design principles](https://github.com/weder96/aws-certification-learning/tree/main/module-14)
- [Storage](https://github.com/weder96/aws-certification-learning/tree/main/module-7)

-------------------------------------------------------------------------------------------------------

# AWS services and features

## Analytics:
1. <img src="./images/solid/check.png" width="20px"><a href="https://github.com/weder96/aws-certification-learning/tree/main/module-11#section-2" target="_blank">Amazon Athena</a>
2. <img src="./images/solid/check.png" width="20px"><a href="https://github.com/weder96/aws-certification-learning/tree/main/module-11#section-11" target="_blank">AWS Data Exchange</a>
3. <img src="./images/solid/check.png" width="20px"><a href="https://github.com/weder96/aws-certification-learning/tree/main/module-11#section-12" target="_blank">AWS Data Pipeline</a>
4. <img src="./images/solid/check.png" width="20px"><a href="https://github.com/weder96/aws-certification-learning/tree/main/module-11#section-01" target="_blank">Amazon EMR</a>
5. <img src="./images/solid/check.png" width="20px"><a href="https://github.com/weder96/aws-certification-learning/tree/main/module-11#section-3" target="_blank">AWS Glue</a>
6. <img src="./images/solid/check.png" width="20px"><a href="https://github.com/weder96/aws-certification-learning/tree/main/module-11#section-5" target="_blank">Amazon Kinesis</a>
7. <img src="./images/solid/check.png" width="20px"><a href="https://github.com/weder96/aws-certification-learning/tree/main/module-11#section-14" target="_blank">AWS Lake Formation</a>
8. <img src="./images/solid/check.png" width="20px"><a href="https://github.com/weder96/aws-certification-learning/tree/main/module-11#section-17" target="_blank">Amazon Managed Streaming for Apache Kafka (Amazon MSK)</a>
9. <img src="./images/solid/check.png" width="20px"><a href="https://github.com/weder96/aws-certification-learning/tree/main/module-11#section-10" target="_blank">Amazon OpenSearch Service (Amazon Elasticsearch Service)</a>
10. <img src="./images/solid/check.png" width="20px"><a href="https://github.com/weder96/aws-certification-learning/tree/main/module-11#section-15" target="_blank">Amazon QuickSight</a>
11. <img src="./images/solid/check.png" width="20px"><a href="https://github.com/weder96/aws-certification-learning/tree/main/module-8#section-04" target="_blank">Amazon Redshift</a>

## Application Integration:
1. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-12#section-5" target="_blank">Amazon AppFlow</a>
2. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-12#section-4" target="_blank">AWS AppSync</a>
3. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-12#section-7" target="_blank">Amazon EventBridge (Amazon CloudWatch Events)</a>
4. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-12#section-3" target="_blank">Amazon MQ</a>
5. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-12#section-1" target="_blank">Amazon Simple Notification Service (Amazon SNS)</a>
6. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-12#section-2" target="_blank">Amazon Simple Queue Service (Amazon SQS)</a>
7. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-12#section-8" target="_blank">AWS Step Functions</a>

## AWS Cost Management:
1. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-2#section-02" target="_blank">AWS Budgets</a>
2. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-2#section-06" target="_blank">AWS Cost and Usage Report </a>
3. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-2#section-04" target="_blank">AWS Cost Explorer</a>
4. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-2#section-07" target="_blank">Savings Plans</a>

## Compute:
1. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-6#section-9" target="_blank"> AWS Batch </a>
2. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-6#section-1" target="_blank"> Amazon EC2</a>
3. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-10#section-1" target="_blank"> Amazon EC2 Auto Scaling</a>
4. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-6#section-8" target="_blank"> AWS Elastic Beanstalk</a>
5. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-6#section-10" target="_blank"> AWS Outposts</a>
6. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-6#section-11" target="_blank"> AWS Serverless Application Repository</a>
7. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-6#section-12" target="_blank"> VMware Cloud on AWS</a>
8. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-6#section-13" target="_blank"> AWS Wavelength</a>

## Containers:
1. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-18#section-01" target="_blank"> Amazon Elastic Container Registry (Amazon ECR)</a>
2. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-18#section-02" target="_blank"> Amazon Elastic Container Service (Amazon ECS)</a>
3. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-18#section-02" target="_blank"> Amazon ECS Anywhere</a>
4. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-18#section-03" target="_blank"> Amazon Elastic Kubernetes Service (Amazon EKS)</a>
5. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-18#section-03" target="_blank"> Amazon EKS Anywhere</a>
6. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-18#section-03" target="_blank"> Amazon EKS Distro</a>


## Database:
1. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-8#section-12" target="_blank"> Amazon Aurora</a>
2. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-8#section-15" target="_blank"> Amazon Aurora Serverless</a>
3. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-8#section-13" target="_blank"> Amazon DocumentDB (with MongoDB compatibility)</a>
4. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-8#section-03" target="_blank"> Amazon DynamoDB</a>
5. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-8#section-05" target="_blank"> Amazon ElastiCache</a>
6. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-8#section-16" target="_blank"> Amazon Keyspaces (for Apache Cassandra)</a>
7. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-8#section-11" target="_blank"> Amazon Neptune</a>
8. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-8#section-14" target="_blank"> Amazon Quantum Ledger Database (Amazon QLDB)</a>
9. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-8#section-02" target="_blank"> Amazon RDS</a>
10. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-8#section-04" target="_blank"> Amazon Redshift</a>
11. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-8#section-17" target="_blank"> Amazon Timestream</a>

## Developer Tools:
1. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-26#section-01" target="_blank"> AWS X-Ray</a>

## Front-End Web and Mobile:
1. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-28#section-01" target="_blank"> AWS Amplify</a>
2. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-12#section-6" target="_blank"> Amazon API Gateway</a>
3. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-28#section-03" target="_blank"> AWS Device Farm</a>
4. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-28#section-04" target="_blank"> Amazon Pinpoint</a>


## Machine Learning:
1. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-19#section-01" target="_blank"> Amazon Comprehend</a>
2. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-19#section-02" target="_blank"> Amazon Forecast</a>
3. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-19#section-03" target="_blank"> Amazon Fraud Detector</a>
4. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-19#section-04" target="_blank"> Amazon Kendra</a>
5. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-19#section-05" target="_blank"> Amazon Lex</a>
6. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-19#section-06" target="_blank"> Amazon Polly</a>
7. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-19#section-07" target="_blank"> Amazon Rekognition</a>
8. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-19#section-08" target="_blank"> Amazon SageMaker</a>
9. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-19#section-09" target="_blank"> Amazon Textract</a>
10. <img src="./images/solid/check.png" width="20px"><a href="https://github.com/weder96/aws-certification-learning/tree/main/module-19#section-10" target="_blank"> Amazon Transcribe</a>
11. <img src="./images/solid/check.png" width="20px"><a href="https://github.com/weder96/aws-certification-learning/tree/main/module-19#section-11" target="_blank"> Amazon Translate</a>


## Management and Governance:
1. <img src="./images/solid/check.png" width="20px">  <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-10#section-1" target="_blank"> AWS Auto Scaling </a>
2. <img src="./images/solid/check.png" width="20px">  <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-20#section-2" target="_blank"> AWS CloudFormation </a>
3. <img src="./images/solid/check.png" width="20px">  <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-20#section-3" target="_blank"> AWS CloudTrail </a>
4. <img src="./images/solid/check.png" width="20px">  <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-20#section-4" target="_blank"> Amazon CloudWatch</a>
5. <img src="./images/solid/check.png" width="20px">  <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-20#section-5" target="_blank"> AWS Command Line Interface (AWS CLI)</a>
6. <img src="./images/solid/check.png" width="20px">  <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-20#section-6" target="_blank"> AWS Compute Optimizer</a>
7. <img src="./images/solid/check.png" width="20px">  <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-20#section-7" target="_blank"> AWS Config</a>
8. <img src="./images/solid/check.png" width="20px">  <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-20#section-8" target="_blank"> AWS Control Tower</a>
9. <img src="./images/solid/check.png" width="20px">  <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-20#section-9" target="_blank"> AWS License Manager</a>
10. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-20#section-10" target="_blank"> Amazon Managed Grafana</a>
11. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-20#section-11" target="_blank"> Amazon Managed Service for Prometheus</a>
12. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-20#section-12" target="_blank"> AWS Management Console</a>
13. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-20#section-13" target="_blank"> AWS Organizations</a>
14. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-20#section-14" target="_blank"> AWS Personal Health Dashboard</a>
15. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-20#section-15" target="_blank"> AWS Proton</a>
16. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-20#section-16" target="_blank"> AWS Service Catalog</a>
17. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-20#section-17" target="_blank"> AWS Systems Manager</a>
18. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-20#section-18" target="_blank"> AWS Trusted Advisor</a>
19. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-20#section-19" target="_blank"> AWS Well Architected Tool</a>

## Media Services:
1. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-17#section-07" target="_blank"> Amazon Elastic Transcoder</a>
2. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-11#section-05" target="_blank"> Amazon Kinesis Video Streams</a>

## Migration and Transfer:
1. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-13#section-07" target="_blank"> AWS Application Discovery Service</a>
2. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-13#section-08" target="_blank"> AWS Application Migration Service (CloudEndure Migration)</a>
3. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-13#section-01" target="_blank"> AWS Database Migration Service
(AWS DMS)</a>
4. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-13#section-02" target="_blank"> AWS DataSync</a>
5. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-13#section-03" target="_blank"> AWS Migration Hub</a>
6. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-13#section-04" target="_blank"> AWS Server Migration Service (AWS SMS)</a>
7. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-13#section-05" target="_blank"> AWS Snow Family</a>
8. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-13#section-06" target="_blank"> AWS Transfer Family</a>


## Networking and Content Delivery:
1. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-5#section-1" target="_blank"> Amazon CloudFront </a>
2. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-5#section-2" target="_blank"> AWS Direct Connect </a>
3. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-5#section-3" target="_blank"> Elastic Load Balancing (ELB) </a>
4. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-5#section-4" target="_blank"> AWS Global Accelerator </a>
5. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-5#section-5" target="_blank"> AWS PrivateLink </a>
6. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-5#section-6" target="_blank"> Amazon Route 53 </a>
7. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-5#section-7" target="_blank"> AWS Transit Gateway </a>
8. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-5#section-8" target="_blank"> Amazon VPC </a>
9. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-5#section-9" target="_blank"> AWS VPN</a>


## Security, Identity, and Compliance:
1. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-4#section-02" target="_blank"> AWS Artifact</a>
2. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-4#section-15" target="_blank"> AWS Audit Manager</a>
3. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-4#section-07" target="_blank"> AWS Certificate Manager (ACM)</a>
4. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-4#section-06" target="_blank"> AWS CloudHSM</a>
5. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-4#section-11" target="_blank"> Amazon Cognito</a>
6. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-4#section-17" target="_blank"> Amazon Detective</a>
7. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-4#section-12" target="_blank"> AWS Directory Service</a>
8. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-4#section-18" target="_blank"> AWS Firewall Manager</a>
9. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-4#section-03" target="_blank"> Amazon GuardDuty</a>
10. <img src="./images/solid/check.png" width="20px"><a href="https://github.com/weder96/aws-certification-learning/tree/main/module-15" target="_blank"> AWS Identity and Access Management(IAM)</a>
11. <img src="./images/solid/check.png" width="20px"><a href="https://github.com/weder96/aws-certification-learning/tree/main/module-4#section-01" target="_blank"> Amazon Inspector</a>
12. <img src="./images/solid/check.png" width="20px"><a href="https://github.com/weder96/aws-certification-learning/tree/main/module-4#section-05" target="_blank"> AWS Key Management Service (AWS KMS)</a>
13. <img src="./images/solid/check.png" width="20px"><a href="https://github.com/weder96/aws-certification-learning/tree/main/module-4#section-19" target="_blank"> Amazon Macie</a>
14. <img src="./images/solid/check.png" width="20px"><a href="https://github.com/weder96/aws-certification-learning/tree/main/module-4#section-20" target="_blank"> AWS Network Firewall</a>
15. <img src="./images/solid/check.png" width="20px"><a href="https://github.com/weder96/aws-certification-learning/tree/main/module-4#section-21" target="_blank"> AWS Resource Access Manager (AWS RAM)</a>
16. <img src="./images/solid/check.png" width="20px"><a href="https://github.com/weder96/aws-certification-learning/tree/main/module-4#section-14" target="_blank"> AWS Secrets Manager</a>
17. <img src="./images/solid/check.png" width="20px"><a href="https://github.com/weder96/aws-certification-learning/tree/main/module-4#section-22" target="_blank"> AWS Security Hub</a>
18. <img src="./images/solid/check.png" width="20px"><a href="https://github.com/weder96/aws-certification-learning/tree/main/module-4#section-23" target="_blank"> AWS Shield</a>
19. <img src="./images/solid/check.png" width="20px"><a href="https://github.com/weder96/aws-certification-learning/tree/main/module-4#section-10" target="_blank"> AWS IAM Identity Center (Sucesor Single Sign-On (AWS SSO)) </a>
20. <img src="./images/solid/check.png" width="20px"><a href="https://github.com/weder96/aws-certification-learning/tree/main/module-4#section-04" target="_blank"> AWS WAF</a>

## Serverless:
1. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-12#section-4" target="_blank"> AWS AppSync</a>
2. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-18#section-04" target="_blank"> AWS Fargate</a>
3. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-14#section-1" target="_blank"> AWS Lambda</a>

## Storage:
1. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-7#section-7" target="_blank"> AWS Backup</a>
2. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-7#section-3" target="_blank"> Amazon Elastic Block Store (AmazonEBS)</a>
3. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-7#section-5" target="_blank"> Amazon Elastic File System (AmazonEFS)</a>
4. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-7#section-1" target="_blank"> Amazon FSx (for all types)</a>
5. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-7#section-1" target="_blank"> Amazon S3</a>
6. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-7#section-1" target="_blank"> Amazon S3 Glacier</a>
7. <img src="./images/solid/check.png" width="20px"> <a href="https://github.com/weder96/aws-certification-learning/tree/main/module-7#section-6" target="_blank"> AWS Storage Gateway</a>

------------------------------------------------------------------------------------------

# Out-of-scope AWS services and features
The following is a non-exhaustive list of AWS services and features that are not covered on the exam.
These services and features do not represent every AWS offering that is excluded from the exam content.

## Analytics:
- Amazon CloudSearch

## Application Integration:
- Amazon Managed Workflows for Apache Airflow (Amazon MWAA)

## AR and VR:
- Amazon Sumerian

## Blockchain:
- Amazon Managed Blockchain

## Compute:
- Amazon Lightsail

## Database:
- Amazon RDS on VMware

## Developer Tools:
- AWS Cloud9
- AWS Cloud Development Kit (AWS CDK)
- AWS CloudShell
- AWS CodeArtifact
- AWS CodeBuild
- AWS CodeCommit
- AWS CodeDeploy
- Amazon CodeGuru
- AWS CodeStar
- Amazon Corretto
- AWS Fault Injection Simulator (AWS FIS)
- AWS Tools and SDKs


## Front-End Web and Mobile:
- Amazon Location Service

## Game Tech:
- Amazon GameLift
- Amazon Lumberyard

## Internet of Things:
- All services

## Machine Learning:
- Apache MXNet on AWS
- Amazon Augmented AI (Amazon A2I)
- AWS DeepComposer
- AWS Deep Learning AMIs (DLAMI)
- AWS Deep Learning Containers
- AWS DeepLens
- AWS DeepRacer
- Amazon DevOps Guru
- Amazon Elastic Inference
- Amazon HealthLake
- AWS Inferentia
- Amazon Lookout for Equipment
- Amazon Lookout for Metrics
- Amazon Lookout for Vision
- Amazon Monitron
- AWS Panorama
- Amazon Personalize
- PyTorch on AWS
- Amazon SageMaker Data Wrangler
- Amazon SageMaker Ground Truth
- TensorFlow on AWS

## Management and Governance:
- AWS Chatbot
- AWS Console Mobile Application
- AWS Distro for OpenTelemetry
- AWS OpsWorks

## Media Services:
- AWS Elemental Appliances and Software
- AWS Elemental MediaConnect
- AWS Elemental MediaConvert
- AWS Elemental MediaLive
- AWS Elemental MediaPackage
- AWS Elemental MediaStore
- AWS Elemental MediaTailor
- Amazon Interactive Video Service (Amazon IVS)

## Migration and Transfer:
- Migration Evaluator (formerly TSO Logic)

## Networking and Content Delivery:
- AWS App Mesh
- AWS Cloud Map

## Quantum Technologies:
- Amazon Braket

## Robotics:
- AWS RoboMaker

## Satellite:
- AWS Ground Station