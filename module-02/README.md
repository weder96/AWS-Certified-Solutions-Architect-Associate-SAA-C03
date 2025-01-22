# Cenários e Questões sobre AWS EBS para o Exame SAA-C03

# Scenarios and Questions about AWS EFS for the SAA-C03 Exam

## Scenario 1: Introduction to EFS
**Question**: What is Amazon Elastic File System (EFS) primarily used for?  
**A)** To provide block storage for EC2 instances.  
**B)** To create and manage file systems for cloud applications.  
**C)** To provide object storage at low cost.  
**D)** For backup and archival solutions only.  

**Correct Answer**: **B)** To create and manage file systems for cloud applications.  
*Explanation*: Amazon EFS is designed for creating, managing, and scaling file systems that can be accessed from multiple EC2 instances simultaneously, making it ideal for cloud applications.*

---

## Scenario 2: EFS File System Access
**Question**: Which protocol does Amazon EFS use to allow access to file systems?  
**A)** SMB.  
**B)** NFS.  
**C)** AFP.  
**D)** FTP.  

**Correct Answer**: **B)** NFS.  
*Explanation*: Amazon EFS supports the NFS protocol, enabling multiple EC2 instances to access the file system concurrently over the network.*

---

## Scenario 3: EFS Pricing Model
**Question**: How is Amazon EFS priced?  
**A)** Based on the number of EC2 instances accessing the file system.  
**B)** Based on the amount of data stored per month, and data transferred.  
**C)** A flat monthly fee regardless of usage.  
**D)** Only based on provisioned throughput.  

**Correct Answer**: **B)** Based on the amount of data stored per month, and data transferred.  
*Explanation*: EFS pricing is primarily based on the storage used and the data transfer across regions, with additional costs for provisioned throughput if required.*

---

## Scenario 4: Performance Modes
**Question**: What are the performance modes available for Amazon EFS?  
**A)** Standard and Premium modes.  
**B)** General Purpose and Max I/O modes.  
**C)** Fast and Slow modes.  
**D)** High and Low latency modes.  

**Correct Answer**: **B)** General Purpose and Max I/O modes.  
*Explanation*: EFS offers two performance modes: General Purpose for lower latency and Max I/O for higher throughput depending on the application’s requirements.*

---

## Scenario 5: EFS Throughput Mode
**Question**: Which throughput mode for EFS is most suitable for applications that require high throughput without the need for a high request rate?  
**A)** Bursting Throughput.  
**B)** Provisioned Throughput.  
**C)** General Throughput.  
**D)** None of the above.  

**Correct Answer**: **B)** Provisioned Throughput.  
*Explanation*: Provisioned Throughput allows customers to specify throughput levels independent of the storage used, making it suitable for applications with high throughput needs.*

---

## Scenario 6: Maximum Storage Capacity
**Question**: What is the maximum storage capacity of an Amazon EFS file system?  
**A)** 1 TB.  
**B)** 10 TB.  
**C)** 50 TB.  
**D)** Scalable to petabytes.  

**Correct Answer**: **D)** Scalable to petabytes.  
*Explanation*: Amazon EFS can scale automatically, allowing users to store petabytes of data without upfront provisioning.*

---

## Scenario 7: EFS Availability
**Question**: How does Amazon EFS provide high availability?  
**A)** By replicating data across multiple Availability Zones within a region.  
**B)** By only storing data in one Availability Zone.  
**C)** By using S3 for backups only.  
**D)** By requiring manual failover plans.  

**Correct Answer**: **A)** By replicating data across multiple Availability Zones within a region.  
*Explanation*: EFS replicates data across multiple Availability Zones automatically, ensuring high availability and durability.*

---

## Scenario 8: Accessing EFS from EC2
**Question**: What must be configured on an EC2 instance to access an EFS file system?  
**A)** No specific configuration is required.  
**B)** An NFS client must be installed and security groups configured.  
**C)** The instance must be running in a private subnet only.  
**D)** EFS performance mode must match the instance type.  

**Correct Answer**: **B)** An NFS client must be installed and security groups configured.  
*Explanation*: To access EFS from EC2 instances, the NFS client needs to be installed, and security groups must allow the correct ports for traffic.*

---

## Scenario 9: Data Consistency
**Question**: What data consistency model does Amazon EFS use?  
**A)** Eventually consistent.  
**B)** Strongly consistent.  
**C)** Read-after-write consistency for new writes.  
**D)** Queued consistency.  

**Correct Answer**: **C)** Read-after-write consistency for new writes.  
*Explanation*: EFS ensures that new writes are immediately visible to all readers, providing read-after-write consistency.*

---

## Scenario 10: EFS Lifecycle Management
**Question**: What feature does Amazon EFS provide for cost saving on infrequently accessed files?  
**A)** Automatically deleting old files.  
**B)** Integration with S3 for archival storage.  
**C)** Infrequent Access (IA) storage class for EFS.  
**D)** Weekly snapshots of files.  

**Correct Answer**: **C)** Infrequent Access (IA) storage class for EFS.  
*Explanation*: EFS offers an Infrequent Access (IA) storage class that automatically moves files not accessed for a longer period to reduce costs.*

---

## Scenario 11: EFS Mount Targets
**Question**: What is the role of a mount target in Amazon EFS?  
**A)** To provide data backup capabilities.  
**B)** To manage EFS permissions.  
**C)** To allow EC2 instances to connect to an EFS file system from a specific VPC.  
**D)** To enforce security policies for EFS.  

**Correct Answer**: **C)** To allow EC2 instances to connect to an EFS file system from a specific VPC.  
*Explanation*: Mount targets serve as entry points for EC2 instances in the VPC to connect to EFS file systems securely.*

---

## Scenario 12: EFS Cross-Region Copying (Learn how Amazon EFS replication & cross-regional replication)
**Question**: Is it possible to replicate an EFS file system across AWS regions?  
**A)** Yes, automatically through AWS settings.  
**B)** No, EFS only operates within the same region.  
**C)** Yes, by creating snapshots and manually exporting them.  
**D)** Yes, but only for read-only access.  

**Correct Answer**: **B)** No, EFS only operates within the same region.  
*Explanation*: Amazon EFS does not support cross-region replication; it is designed to work within a single AWS region.*

[an-intro-to-amazon-efs-replication](https://stratusgrid.com/blog/an-intro-to-amazon-efs-replication)


---

## Scenario 13: EFS Security
**Question**: How can you control access to an Amazon EFS file system?  
**A)** Through IAM policies only.  
**B)** By configuring security groups and network ACLs.  
**C)** By using both security groups and IAM policies.  
**D)** Access is open by default.  

**Correct Answer**: **C)** By using both security groups and IAM policies.  
*Explanation*: Access to EFS can be controlled through IAM policies as well as security groups, allowing for granular permissions and network access.*

---

## Scenario 14: EFS and Lambda Integration
**Question**: Can Amazon EFS be used with AWS Lambda?  
**A)** No, it is not supported.  
**B)** Yes, for temporary storage only.  
**C)** Yes, Lambda functions can access EFS as a file system.  
**D)** Only in specific regions.  

**Correct Answer**: **C)** Yes, Lambda functions can access EFS as a file system.  
*Explanation*: AWS Lambda can mount an EFS file system, providing serverless applications with persistent storage capabilities.*

---

## Scenario 15: EFS Data Transfer
**Question**: How is data transferred to and from Amazon EFS?  
**A)** Only through AWS CLI.  
**B)** Through NFS mount points from EC2 instances.  
**C)** By using AWS DataSync only.  
**D)** Data is automatically uploaded to EFS without user intervention. 

**Correct Answer**: **B)** Through NFS mount points from EC2 instances.  
*Explanation*: Data is accessed from and stored in EFS through NFS mount points established on EC2 instances.*

---

## Scenario 16: EFS Performance
**Question**: What can affect the performance of an Amazon EFS file system?  
**A)** The instance types accessing the EFS.  
**B)** The file system's size.  
**C)** The number of instances accessed concurrently.  
**D)** All of the above.  

**Correct Answer**: **D)** All of the above.  
*Explanation*: EFS performance can be influenced by the type of EC2 instance using it, the size of the file system, and the number of concurrent instances accessing it.*

---

## Scenario 17: EFS for Web Applications
**Question**: Why would you use EFS for web applications?  
**A)** To have high-speed, low-latency access to static files.  
**B)** Because it automatically scales with usage.  
**C)** For easy sharing of files among multiple instances.  
**D)** All of the above.  

**Correct Answer**: **D)** All of the above.  
*Explanation*: EFS is suitable for web applications due to its high-speed access, automatic scaling, and ease of sharing files between multiple EC2 instances.*

---

## Scenario 18: EFS Backup Options
**Question**: Which is a recommended way to back up your data in EFS?  
**A)** Only manually copy data to S3.  
**B)** Use AWS Backup to automate the backup process.  
**C)** Rely on EFS versioning.  
**D)** There is no need to back up EFS data.  

**Correct Answer**: **B)** Use AWS Backup to automate the backup process.  
*Explanation*: AWS Backup can be used to automate backups for EFS, ensuring data is regularly protected without manual intervention.*

---

## Scenario 19: EFS and Cost Optimization
**Question**: How can using EFS Infrequent Access mode benefit your costs?  
**A)** By charging more for access.  
**B)** By reducing costs on infrequently accessed files.  
**C)** By eliminating the need for backups.  
**D)** By providing free storage.  

**Correct Answer**: **B)** By reducing costs on infrequently accessed files.  
*Explanation*: EFS Infrequent Access mode automatically manages files that are not accessed frequently, reducing costs compared to standard storage.*

---

## Scenario 20: Deployment Scenarios
**Question**: In which situation would you choose EFS over S3?  
**A)** When you need low-latency file access.  
**B)** When you need a highly durable storage solution.  
**C)** When you require a file-sharing mechanism accessible via NFS.  
**D)** Both A and C.  

**Correct Answer**: **D)** Both A and C.  
*Explanation*: EFS is ideal when low-latency file access and NFS-based file sharing are needed, which S3 does not provide.*

---

## Scenario 21: Data Transfer Acceleration
**Question**: How can you speed up data transfer to EFS?  
**A)** By using AWS Direct Connect.  
**B)** By compressing data before upload.  
**C)** By using a Content Delivery Network (CDN).  
**D)** Both A and B.  

**Correct Answer**: **D)** Both A and B.  
*Explanation*: Using AWS Direct Connect can facilitate faster data transfer rates, along with compressing data before upload.*

---

## Scenario 22: EFS Scaling
**Question**: What happens to Amazon EFS when you add more data to it?  
**A)** It requires manual intervention to scale.  
**B)** It automatically scales up based on the data added.  
**C)** It will stop accepting new data once it reaches a limit.  
**D)** You need to create a new file system.  

**Correct Answer**: **B)** It automatically scales up based on the data added.  
*Explanation*: EFS automatically scales as more data is added, making it easy to manage without manual adjustments.*

---

## Scenario 23: EFS Security Features
**Question**: Which feature enhances security for EFS file systems?  
**A)** Encrypted access using IAM APIs.  
**B)** Encrypted data at rest and in transit.  
**C)** Only allowed ports for NFS connections.  
**D)** Multi-Factor Authentication (MFA).  

**Correct Answer**: **B)** Encrypted data at rest and in transit.  
*Explanation*: EFS supports encryption to protect data both at rest and in transit, adding an important layer of security.*

---

## Scenario 24: Use Cases for EFS
**Question**: Which of the following is a typical use case for Amazon EFS?  
**A)** Hosting a static website.  
**B)** Providing shared storage for containerized applications.  
**C)** Archiving data long term.  
**D)** Storing relational databases.  

**Correct Answer**: **B)** Providing shared storage for containerized applications.  
*Explanation*: EFS is commonly used to provide shared storage for containers, making it easy for applications to share files across instances.*

---

## Scenario 25: Mounting EFS
**Question**: What command is typically used to mount an EFS file system to an EC2 instance?  
**A)** mount -t efs  
**B)** mount -t nfs  
**C)** mount -t efs | nfs  
**D)** All of the above.  

**Correct Answer**: **D)** All of the above.  
*Explanation*: Different syntaxes are valid; the specific `mount` command may use either `efs` or `nfs` depending on the implementation.*

---

## Scenario 26: Monitoring EFS Performance
**Question**: Which AWS service can be used to monitor the performance of Amazon EFS?  
**A)** AWS CloudTrail.  
**B)** AWS CloudFormation.  
**C)** Amazon CloudWatch.  
**D)** AWS Config.  

**Correct Answer**: **C)** Amazon CloudWatch.  
*Explanation*: Amazon CloudWatch can be used to monitor performance metrics of EFS, such as throughput and file system usage.*

---

## Scenario 27: EFS Integration with ECS
**Question**: How can Amazon EFS integrate with Amazon ECS?  
**A)** EFS provides a private container registry.  
**B)** EFS can be mounted as a volume for containers.  
**C)** EFS doesn't work with ECS.  
**D)** Only one container can access EFS at a time.  

**Correct Answer**: **B)** EFS can be mounted as a volume for containers.  
*Explanation*: EFS can be mounted as a volume in ECS task definitions, allowing shared access to data across multiple containers.*

---

## Scenario 28: Infrequent Access (IA) Usage
**Question**: Which of the following describes when to use EFS Infrequent Access?  
**A)** For all critical application files.  
**B)** For data that is accessed less frequently but needs to be visible.  
**C)** To store temporary files.  
**D)** For any file that is constantly accessed.  

**Correct Answer**: **B)** For data that is accessed less frequently but needs to be visible.  
*Explanation*: EFS Infrequent Access is ideal for files that are not accessed regularly but must still be available when needed.*

---

## Scenario 29: Data Organization in EFS
**Question**: How can you organize data in an EFS file system?  
**A)** Only flat file structure is allowed.  
**B)** By using directories and folders as in traditional file systems.  
**C)** Data organization is not possible within EFS.  
**D)** Files can only be organized via tags.  

**Correct Answer**: **B)** By using directories and folders as in traditional file systems.  
*Explanation*: EFS supports directory structures, allowing users to organize their data hierarchically similar to traditional file systems.*

---

## Scenario 30: EFS Limitations
**Question**: Which of the following is a limitation of Amazon EFS?  
**A)** It can only be accessed from a single Availability Zone.  
**B)** It does not support strong consistency.  
**C)** It cannot grow to meet increased claim based on storage needs.  
**D)** There is a maximum number of file handles that can be open at once.

**Correct Answer**: **D)** There is a maximum number of file handles that can be open at once.  
*Explanation*: EFS has limits on the number of open file handles per account, which can restrict concurrent access in very high-load scenarios.*

---

## Scenario 31: EFS Data Retrieval Speed
**Question**: What affects the speed at which data can be retrieved from EFS?  
**A)** The region where EFS is deployed.  
**B)** The amount of data stored in the file system.  
**C)** The performance mode selected for the file system.  
**D)** All of the above.  

**Correct Answer**: **D)** All of the above.  
*Explanation*: Data retrieval speed can be influenced by the region, size of the data, and the selected performance mode.*

---

## Scenario 32: Long-Term Storage Solutions
**Question**: Is Amazon EFS suitable for long-term storage solutions?  
**A)** Yes, but only for infrequently accessed files.  
**B)** No, it is designed for active file storage and not suited for long-term data retention.  
**C)** Yes, as it can store large amounts of data indefinitely.  
**D)** Only if integrated with S3 for archiving.  

**Correct Answer**: **B)** No, it is designed for active file storage and not suited for long-term data retention.  
*Explanation*: EFS is best utilized for active data storage; for long-term retention, S3 or Glacier is preferred.*

---

## Scenario 33: Access Scope
**Question**: What type of IAM policy can be used to manage access to an Amazon EFS file system?  
**A)** User policy only.  
**B)** Resource-based policy.  
**C)** Organization-wide policy.  
**D)** Only instance profile policy.  

**Correct Answer**: **B)** Resource-based policy.  
*Explanation*: Resource-based policies can be applied to EFS file systems to define which IAM entities can access them.*

---

## Scenario 34: EFS Backup Policies
**Question**: Can you configure automatic backup policies for Amazon EFS?  
**A)** No, automatic backups are not supported.  
**B)** Yes, using AWS Backup service.  
**C)** Yes, through manual scripts only.  
**D)** Only for file systems with data under 1 TB.  

**Correct Answer**: **B)** Yes, using AWS Backup service.  
*Explanation*: AWS Backup allows users to automate backup and restore operations for EFS.*

---

## Scenario 35: EFS File System Scope
**Question**: Can an EFS file system be shared with multiple AWS accounts?  
**A)** Yes, through resource-based policies.  
**B)** No, it is limited to a single AWS account.  
**C)** Only with cross-account access enabled.  
**D)** Yes, but only within the same region. 

**Correct Answer**: **A)** Yes, through resource-based policies.  
*Explanation*: EFS allows cross-account sharing when using resource-based policies to define access across different AWS accounts.*

---

## Scenario 36: Monitoring EFS with CloudWatch
**Question**: Which EFS metric would you monitor to assess the performance related to read operations?  
**A)** DataWriteIOBytes.  
**B)** DataReadIOBytes.  
**C)** ActiveFileCount.  
**D)** BurstCreditBalance.  

**Correct Answer**: **B)** DataReadIOBytes.  
*Explanation*: Monitoring the DataReadIOBytes metric provides insights into the number of bytes read from your EFS file system, reflecting read performance.*

---

## Scenario 37: EFS for CI/CD Pipelines
**Question**: Why might you use Amazon EFS in CI/CD pipelines?  
**A)** To store versioned artifacts only.  
**B)** To share configurations and assets across build environments.  
**C)** It is required by the CI/CD service.  
**D)** To retain logs only.  

**Correct Answer**: **B)** To share configurations and assets across build environments.  
*Explanation*: EFS can be utilized in CI/CD processes to share files between different steps/stages of the pipeline, facilitating collaboration among different compute resources.*

---

## Scenario 38: EFS and Auto Scaling
**Question**: What benefit does using EFS provide in conjunction with Auto Scaling?  
**A)** It provides temporary storage for scaling instances.  
**B)** It allows for persistent storage that scales with the application.  
**C)** It is required for Auto Scaling.  
**D)** It reduces the number of EC2 instances required.  

**Correct Answer**: **B)** It allows for persistent storage that scales with the application.  
*Explanation*: EFS provides a shared, persistent file system that can be accessed by multiple instances as they scale up or down in response to load.*

---

## Scenario 39: EFS and Docker Containers
**Question**: What is a common use case for EFS with Docker containers?  
**A)** To store container images.  
**B)** To provide shared storage for multiple containers.  
**C)** EFS cannot be used with Docker containers.  
**D)** For temporary storage to hold container logs.  

**Correct Answer**: **B)** To provide shared storage for multiple containers.  
*Explanation*: EFS is used with Docker containers in services like ECS and EKS to provide a shared storage solution that multiple containers can access.*

---

## Scenario 40: EFS Constraints
**Question**: What is the primary constraint of Amazon EFS?  
**A)** It can only be used with specific instance types.  
**B)** There's a limit on how many files can be stored.  
**C)** It requires a minimum amount of storage space when created.  
**D)** It has limits on the number of concurrent connections per account.  

**Correct Answer**: **D)** It has limits on the number of concurrent connections per account.  
*Explanation*: EFS does have limitations on the number of simultaneous connections, impacting very high-load situations requiring extensive file access.*

---

## Scenario 41: EFS Metadata
**Question**: What type of metadata does Amazon EFS maintain for files?  
**A)** Only read and write bits.  
**B)** File ownership and permissions, timestamps, and sizes.  
**C)** File indexing information only.  
**D)** No metadata is maintained.  

**Correct Answer**: **B)** File ownership and permissions, timestamps, and sizes.  
*Explanation*: EFS maintains comprehensive metadata for files, including ownership, permissions, creation, and modification timestamps, similar to traditional file systems.*

---

## Scenario 42: Quotas on EFS
**Question**: Does Amazon EFS impose any quotas on file systems?  
**A)** No quotas are applied.  
**B)** It imposes a maximum number of files that can be created.  
**C)** Only on the total storage amount is there a quota.  
**D)** It enforces limits on metadata storage only.  

**Correct Answer**: **A)** No quotas are applied.  
*Explanation*: Amazon EFS does not impose quotas that restrict the number of files; it scales with the storage used, allowing for flexibility.*

---

## Scenario 43: EFS Data Migration
**Question**: Which service can facilitate the migration of data to EFS from on-premises environments?  
**A)** AWS Snowball.  
**B)** AWS DataSync.  
**C)** AWS Transfer for SFTP.  
**D)** All of the above.  

**Correct Answer**: **D)** All of the above.  
*Explanation*: AWS provides various services, including Snowball, DataSync, and Transfer services, to facilitate the migration of data to EFS from on-premises setups.*

---

## Scenario 44: Serverless Architecture
**Question**: In a serverless architecture with Lambda, how can EFS be used?  
**A)** Only for caching data temporarily.  
**B)** For persistent data storage accessed across Lambda invocations.  
**C)** EFS cannot be integrated with Lambda.  
**D)** To store environment variables.  

**Correct Answer**: **B)** For persistent data storage accessed across Lambda invocations.  
*Explanation*: EFS provides persistent storage that can be accessed by multiple Lambda functions, suitable for applications requiring shared state or data.*

---

## Scenario 45: File System Attributes
**Question**: What attributes can you set on an Amazon EFS file system?  
**A)** Only read-write permissions.  
**B)** Performance mode and throughput mode.  
**C)** Network traffic inhibition settings.  
**D)** IP address assignments.  

**Correct Answer**: **B)** Performance mode and throughput mode.  
*Explanation*: Users can configure the performance mode and throughput mode attributes for their EFS file systems.*

---

## Scenario 46: EFS Access Point
**Question**: What is the purpose of an Amazon EFS access point?  
**A)** To store extra copies of data.  
**B)** To simplify permissions for applications using EFS.  
**C)** To manage backup policies.  
**D)** To replace security groups.  

**Correct Answer**: **B)** To simplify permissions for applications using EFS.  
*Explanation*: EFS access points provide a way to manage permissions and attributes for applications using the file system, simplifying the access control process.*

---

## Scenario 47: EFS File System Identifier
**Question**: What identifier is given to each EFS file system?  
**A)** IP address.  
**B)** DNS name only.  
**C)** File system ID.  
**D)** ARN only.  

**Correct Answer**: **C)** File system ID.  
*Explanation*: Each EFS file system is assigned a unique file system ID that can be used to reference it in API calls and management processes.*

---

## Scenario 48: EFS Notifications
**Question**: Can Amazon EFS send notifications based on file system events?  
**A)** No, such features are not supported.  
**B)** Yes, through Amazon CloudWatch and Amazon SNS.  
**C)** Yes, but only to on-premises systems.  
**D)** Only when accessing files from EC2. 

**Correct Answer**: **B)** Yes, through Amazon CloudWatch and Amazon SNS.  
*Explanation*: EFS can integrate with CloudWatch and SNS to send notifications regarding events related to the file system.*

---

## Scenario 49: File System Encryption
**Question**: How can data in an EFS file system be encrypted?  
**A)** Through Amazon IAM policies.  
**B)** EFS automatically encrypts data at rest; additional settings are not needed.  
**C)** You must use third-party tools to encrypt EFS data.  
**D)** Only data at rest can be encrypted, not in transit.  

**Correct Answer**: **B)** EFS automatically encrypts data at rest; additional settings are not needed.  
*Explanation*: Amazon EFS automatically encrypts data at rest using keys managed through AWS Key Management Service (KMS).*

---

## Scenario 50: EFS and Database Storage
**Question**: Is Amazon EFS suitable as a backend storage solution for database applications?  
**A)** Yes, for all types of databases.  
**B)** No, EFS is not optimized for database workloads.  
**C)** Only for NoSQL databases.  
**D)** Yes, but only for caching purposes.  

**Correct Answer**: **B)** No, EFS is not optimized for database workloads.  
*Explanation*: While EFS can store data, it is not optimized for database performance characteristics like IOPS and latency; block storage (e.g., EBS) is preferred for databases.*

---