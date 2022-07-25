AWS Certified Solutions Architect - Associate (SAA-C03)

[AWS Certified Solutions Architect - Associate (SAA-C03) Exam Guide](https://d1.awsstatic.com/training-and-certification/docs-sa-assoc/AWS-Certified-Solutions-Architect-Associate_Exam-Guide_C03.pdf)


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
Your score report could contain a table of classifications of your performance at each section level. This
information provides general feedback about your exam performance. The exam uses a compensatory
scoring model, which means that you do not need to achieve a passing score in each section. You need to
pass only the overall exam.
Each section of the exam has a specific weighting, so some sections have more questions than other
sections have. The table contains general information that highlights your strengths and weaknesses. Use
caution when interpreting section-level feedback. Candidates who pass the exam will not receive this
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
- Access controls and management across multiple accounts
- AWS federated access and identity services (for example, AWS Identity and Access Management [IAM], AWS Single Sign-On [AWS SSO])
- AWS global infrastructure (for example, Availability Zones, AWS Regions)
- AWS security best practices (for example, the principle of least privilege)
- The AWS shared responsibility model

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
- Application configuration and credentials security
- AWS service endpoints
- Control ports, protocols, and network traffic on AWS
- Secure application access
- Security services with appropriate use cases (for example, Amazon Cognito, Amazon GuardDuty, Amazon Macie)
- Threat vectors external to AWS (for example, DDoS, SQL injection)

### Skills in:
- Designing VPC architectures with security components (for example, security groups, route tables, network ACLs, NAT gateways)
- Determining network segmentation strategies (for example, using public subnets and private subnets)
vIntegrating AWS services to secure applications (for example, AWS Shield, AWS WAF, AWS SSO, AWS Secrets Manager)
- Securing external network connections to and from the AWS Cloud (for example, VPN, AWS Direct Connect)


**Task Statement 3: Determine appropriate data security controls.**
### Knowledge of:
- Data access and governance
- Data recovery
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
- API creation and management (for example, Amazon API Gateway, REST API)
- AWS managed services with appropriate use cases (for example, AWS Transfer Family, Amazon Simple Queue Service [Amazon SQS], Secrets Manager)
- Caching strategies
- Design principles for microservices (for example, stateless workloads compared with stateful workloads)
- Event-driven architectures
- Horizontal scaling and vertical scaling
- How to appropriately use edge accelerators (for example, content delivery network [CDN])
- How to migrate applications into containers
- Load balancing concepts (for example, Application Load Balancer)
- Multi-tier architectures
- Queuing and messaging concepts (for example, publish/subscribe)
- Serverless technologies and patterns (for example, AWS Fargate, AWS Lambda)
- Storage types with associated characteristics (for example, object, file, block)
- The orchestration of containers (for example, Amazon Elastic Container Service [Amazon ECS], Amazon Elastic Kubernetes Service [Amazon EKS])
- When to use read replicas
- Workflow orchestration (for example, AWS Step Functions)

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
- AWS global infrastructure (for example, Availability Zones, AWS Regions, Amazon Route 53)
- AWS managed services with appropriate use cases (for example, Amazon Comprehend, Amazon Polly)
- Basic networking concepts (for example, route tables)
- Disaster recovery (DR) strategies (for example, backup and restore, pilot light, warm standby, active-active failover, recovery point objective [RPO], recovery time objective [RTO])
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

- Compute
- Cost management
- Database
- Disaster recovery
- High performance
- Management and governance
- Microservices and component decoupling
- Migration and data transfer
- Networking, connectivity, and content delivery
- Resiliency
- Security
- Serverless and event-driven design principles
- Storage


-------------------------------------------------------------------------------------------------------

# AWS services and features

## Analytics:
- [Amazon Athena](https://github.com/weder96/aws-certification-learning/tree/main/module-11#section-2)
- AWS Data Exchange
- AWS Data Pipeline
- Amazon EMR
- [AWS Glue](https://github.com/weder96/aws-certification-learning/tree/main/module-11#section-3)
- [Amazon Kinesis](https://github.com/weder96/aws-certification-learning/tree/main/module-11#section-5)
- AWS Lake Formation
- Amazon Managed Streaming for Apache Kafka (Amazon MSK)
- Amazon OpenSearch Service (Amazon Elasticsearch Service)
- Amazon QuickSight
- Amazon Redshift

## Application Integration:
- Amazon AppFlow
- AWS AppSync
- Amazon EventBridge (Amazon CloudWatch Events)
- Amazon MQ
- Amazon Simple Notification Service (Amazon SNS)
- Amazon Simple Queue Service (Amazon SQS)
- AWS Step Functions

## AWS Cost Management:
- AWS Budgets
- AWS Cost and Usage Report
- AWS Cost Explorer
- Savings Plans

## Compute:
- AWS Batch
- Amazon EC2
- Amazon EC2 Auto Scaling
- AWS Elastic Beanstalk
- AWS Outposts
- AWS Serverless Application Repository
- VMware Cloud on AWS
- AWS Wavelength

## Containers:
- Amazon Elastic Container Registry (Amazon ECR)
- Amazon Elastic Container Service (Amazon ECS)
- Amazon ECS Anywhere
- Amazon Elastic Kubernetes Service (Amazon EKS)
- Amazon EKS Anywhere
- Amazon EKS Distro


## Database:
- Amazon Aurora
- Amazon Aurora Serverless
- Amazon DocumentDB (with MongoDB compatibility)
- Amazon DynamoDB
- Amazon ElastiCache
- Amazon Keyspaces (for Apache Cassandra)
- Amazon Neptune
- Amazon Quantum Ledger Database (Amazon QLDB)
- Amazon RDS
- Amazon Redshift
- Amazon Timestream

## Developer Tools:
- AWS X-Ray

## Front-End Web and Mobile:
- AWS Amplify
- Amazon API Gateway
- AWS Device Farm
- Amazon Pinpoint


## Machine Learning:
- Amazon Comprehend
- Amazon Forecast
- Amazon Fraud Detector
- Amazon Kendra
- Amazon Lex
- Amazon Polly
- Amazon Rekognition
- Amazon SageMaker
- Amazon Textract
- Amazon Transcribe
- Amazon Translate


## Management and Governance:
- AWS Auto Scaling
- AWS CloudFormation
- AWS CloudTrail
- Amazon CloudWatch
- AWS Command Line Interface (AWS CLI)
- AWS Compute Optimizer
- AWS Config
- AWS Control Tower
- AWS License Manager
- Amazon Managed Grafana
- Amazon Managed Service for Prometheus
- AWS Management Console
- AWS Organizations
- AWS Personal Health Dashboard
- AWS Proton
- AWS Service Catalog
- AWS Systems Manager
- AWS Trusted Advisor
- AWS Well-Architected Tool

## Media Services:
- Amazon Elastic Transcoder
- Amazon Kinesis Video Streams

## Migration and Transfer:
- AWS Application Discovery Service
- AWS Application Migration Service (CloudEndure Migration)
- AWS Database Migration Service (AWS DMS)
- AWS DataSync
- AWS Migration Hub
- AWS Server Migration Service (AWS SMS)
- AWS Snow Family
- AWS Transfer Family


## Networking and Content Delivery:
- Amazon CloudFront
- AWS Direct Connect
- Elastic Load Balancing (ELB)
- AWS Global Accelerator
- AWS PrivateLink
- Amazon Route 53
- AWS Transit Gateway
- Amazon VPC
- AWS VPN


## Security, Identity, and Compliance:
- AWS Artifact
- AWS Audit Manager
- AWS Certificate Manager (ACM)
- AWS CloudHSM
- Amazon Cognito
- Amazon Detective
- AWS Directory Service
- AWS Firewall Manager
- Amazon GuardDuty
- AWS Identity and Access Management (IAM)
- Amazon Inspector
- AWS Key Management Service (AWS KMS)
- Amazon Macie
- AWS Network Firewall
- AWS Resource Access Manager (AWS RAM)
- AWS Secrets Manager
- AWS Security Hub
- AWS Shield
- AWS Single Sign-On
- AWS WAF

## Serverless:
- AWS AppSync
- AWS Fargate
- AWS Lambda

## Storage:
- AWS Backup
- Amazon Elastic Block Store (Amazon EBS)
- Amazon Elastic File System (Amazon EFS)
- Amazon FSx (for all types)
- Amazon S3
- Amazon S3 Glacier
- AWS Storage Gateway

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