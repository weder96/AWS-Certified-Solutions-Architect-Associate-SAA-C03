<img src="../images/extra/banner_aws.png" alt="aws" width=80 height=50 /> [General Content AWS Cloud][1]

[1]: https://github.com/weder96/aws-certification-learning

# Module 99: Concepts‌ ‌and‌‌ Strategies 

## Contents
1. <a href="#section-1"> Storage - EBS </a>

*********************************************************************************************

## <a id="section-1" ></a> **1 - Storage - EBS**
# Scenarios and Questions about AWS EBS for the SAA-C03 Exam

## Scenario 1: Introduction to EBS
**Question**: What is Amazon Elastic Block Store (EBS) primarily used for?  
**A)** Object storage for unstructured data.  
**B)** High-performance block storage for EC2 instances.  
**C)** File storage for user data directly.  
**D)** Archive data for long-term storage.  
**Correct Answer**: **B)** High-performance block storage for EC2 instances.  
*Explanation*: EBS provides block-level storage volumes for use with EC2 instances, making it ideal for databases and applications that require high performance and low latency.*

---

## Scenario 2: Types of EBS Volumes
**Question**: What are the different types of EBS volume options available?  
**A)** Standard, Enhanced, and Premium.  
**B)** General Purpose SSD, Provisioned IOPS SSD, and Magnetic.  
**C)** Basic and Advanced Storage.  
**D)** Fast and Slow Storage.  
**Correct Answer**: **B)** General Purpose SSD, Provisioned IOPS SSD, and Magnetic.  
*Explanation*: EBS offers several volume types including General Purpose (SSD), Provisioned IOPS (SSD), and Magnetic volumes to meet different performance needs.*

---

## Scenario 3: EBS Volume Size
**Question**: What is the maximum size of an EBS volume?  
**A)** 1 TB.  
**B)** 16 TB.  
**C)** 64 TB.  
**D)** 1 PB.  
**Correct Answer**: **C)** 64 TB.  
*Explanation*: EBS volumes can be up to 64 TB in size, allowing for substantial storage capacity for applications.*

---

## Scenario 4: IOPS
**Question**: What does IOPS stand for in the context of EBS?  
**A)** Internal Operations per Second.  
**B)** Input/Output Operations Per Second.  
**C)** Input Operations Per Second.  
**D)** Instance Operations Per Second.  
**Correct Answer**: **B)** Input/Output Operations Per Second.  
*Explanation*: IOPS measures the number of read and write operations that can be performed per second on an EBS volume.*

---

## Scenario 5: EBS Optimized Instances
**Question**: What is the purpose of using EBS-optimized EC2 instances?  
**A)** To increase the storage size of EBS volumes.  
**B)** To provide dedicated throughput between the EC2 and EBS.  
**C)** To reduce the cost of the EBS volume.  
**D)** To back up EBS volumes automatically.  
**Correct Answer**: **B)** To provide dedicated throughput between the EC2 and EBS.  
*Explanation*: EBS-optimized instances are designed to provide dedicated bandwidth between EC2 instances and EBS, helping to improve performance.*

---

## Scenario 6: Snapshots
**Question**: What is an EBS snapshot?  
**A)** A copy of an EBS volume stored in S3.  
**B)** A physical backup of your EC2 instance.  
**C)** A point-in-time copy of an EBS volume.  
**D)** A temporary storage mechanism.  
**Correct Answer**: **C)** A point-in-time copy of an EBS volume.  
*Explanation*: EBS snapshots are incremental backups of volumes, allowing for point-in-time recovery of data stored in volumes.*

---

## Scenario 7: Snapshot Pricing
**Question**: How is the cost of EBS snapshots determined?  
**A)** Based on the IOPS of the EBS volume.  
**B)** Based on the amount of data scanned in a snapshot.  
**C)** Based on the total size of the data stored in the snapshot.  
**D)** Free for the first 1 TB, then costs apply.  
**Correct Answer**: **C)** Based on the total size of the data stored in the snapshot.  
*Explanation*: The cost of EBS snapshots is calculated based on the size of the data stored in the snapshot, with incremental backups being charged only for changes.*

---

## Scenario 8: Snapshot Restoration
**Question**: What happens when you restore an EBS snapshot to create a new volume?  
**A)** It overwrites the existing volume with the same ID.  
**B)** It creates a new volume from the snapshot.  
**C)** The snapshot is deleted immediately.  
**D)** You must always specify a size larger than the snapshot.  
**Correct Answer**: **B)** It creates a new volume from the snapshot.  
*Explanation*: Restoring from a snapshot creates a new volume; the original snapshot remains unchanged.*

---

## Scenario 9: Volume Attachment
**Question**: How many EBS volumes can be attached to a single EC2 instance?  
**A)** Up to 5 volumes.  
**B)** Up to 16 volumes in most cases.  
**C)** Unlimited EBS volumes.  
**D)** Only 1 volume at a time.  
**Correct Answer**: **B)** Up to 16 volumes in most cases.  
*Explanation*: While the limit may vary by instance type, generally, you can attach up to 16 EBS volumes to a single EC2 instance.*

---

## Scenario 10: Volume Encryption
**Question**: What is a feature of Amazon EBS regarding volume encryption?  
**A)** Only specific snapshot types can be encrypted.  
**B)** EBS volumes can be encrypted at rest and in transit.  
**C)** Encryption is not available for EBS volumes.  
**D)** Encryption is done through S3 only.  
**Correct Answer**: **B)** EBS volumes can be encrypted at rest and in transit.  
*Explanation*: Amazon EBS provides encryption capabilities for volumes, ensuring data is secure both at rest and during transit.*

---

## Scenario 11: EBS Performance Characteristics
**Question**: Which EBS volume type is optimized for latency-sensitive applications?  
**A)** Magnetic volumes.  
**B)** General Purpose (SSD) volumes.  
**C)** Provisioned IOPS (SSD) volumes.  
**D)** Archive Storage volumes only.  
**Correct Answer**: **C)** Provisioned IOPS (SSD) volumes.  
*Explanation*: Provisioned IOPS (SSD) volumes are specifically designed for low-latency and high-throughput performance, making them ideal for latency-sensitive applications.*

---

## Scenario 12: Backup Strategy with EBS
**Question**: What is a recommended backup strategy for critical data on EBS?  
**A)** Rely solely on local backups.  
**B)** Utilize snapshots regularly and store them in S3.  
**C)** Back up data to another EBS volume only.  
**D)** Manual copying of data to a local disk.  
**Correct Answer**: **B)** Utilize snapshots regularly and store them in S3.  
*Explanation*: Regularly taking EBS snapshots and storing them in S3 provides a reliable backup strategy, ensuring data is protected and recoverable.*

---

## Scenario 13: Data Migration
**Question**: Which AWS service can facilitate the migration of data to EBS from an on-premises environment?  
**A)** AWS Direct Connect.  
**B)** AWS Snowball.  
**C)** Amazon EC2.  
**D)** AWS Lambda.  
**Correct Answer**: **B)** AWS Snowball.  
*Explanation*: AWS Snowball can be used to transfer large amounts of data from on-premises environments to AWS, including EBS volumes.*

---

## Scenario 14: Changing Volume Type
**Question**: Can you change the volume type of an existing EBS volume?  
**A)** No, once created, the type is fixed.  
**B)** Yes, using AWS Console or CLI without data loss.  
**C)** Yes, but only if the volume is stopped.  
**D)** Yes, but it requires a complete backup first.  
**Correct Answer**: **B)** Yes, using AWS Console or CLI without data loss.  
*Explanation*: Amazon allows you to change the volume type of an existing EBS volume without data loss using AWS Management Console or CLI.*

---

## Scenario 15: Volume Deletion
**Question**: What happens to EBS snapshots when you delete the underlying EBS volume?  
**A)** Snapshots are deleted as well.  
**B)** Snapshots remain intact and can be used to create new volumes.  
**C)** You must delete snapshots manually.  
**D)** Snapshots are automatically downloaded to local storage.  
**Correct Answer**: **B)** Snapshots remain intact and can be used to create new volumes.  
*Explanation*: Deleting the EBS volume does not affect the associated snapshots, which can be used independently afterward.*

---

## Scenario 16: EBS Volume Limitations
**Question**: What is the maximum number of EBS volumes that can be created in an AWS account per region?  
**A)** 25 volumes.  
**B)** 100 volumes.  
**C)** 500 volumes.  
**D)** It depends on the region.  
**Correct Answer**: **B)** 100 volumes.  
*Explanation*: By default, an AWS account allows the creation of up to 100 EBS volumes in a single region, although this limit can be increased by contacting AWS support.*

---

## Scenario 17: EBS Volume In-use Policy
**Question**: Can you detach an EBS volume that is in use by an EC2 instance?  
**A)** Yes, immediately.  
**B)** No, it must be stopped first.  
**C)** Yes, but only if the application on the instance is stopped.  
**D)** Detaching is not allowed for in-use volumes.  
**Correct Answer**: **C)** Yes, but only if the application on the instance is stopped.  
*Explanation*: An EBS volume can be detached while in use, but applications using it should be stopped to prevent data loss or corruption.*

---

## Scenario 18: Monitoring EBS Performance
**Question**: Which service can be used to monitor the performance of EBS volumes?  
**A)** AWS Inspector.  
**B)** Amazon CloudWatch.  
**C)** AWS Config.  
**D)** Amazon Trust Advisor.  
**Correct Answer**: **B)** Amazon CloudWatch.  
*Explanation*: Amazon CloudWatch provides metrics for monitoring EBS performance, such as IOPS and throughput.*

---

## Scenario 19: EBS and EC2 Instance Types
**Question**: Which EC2 instance types are recommended for maximizing EBS performance?  
**A)** All EC2 instance types are equal.  
**B)** Only M5 and C5.  
**C)** EBS-optimized instances.  
**D)** T2 and T3 instances only.  
**Correct Answer**: **C)** EBS-optimized instances.  
*Explanation*: EBS-optimized instances are specifically designed to provide optimal performance when working with EBS volumes by providing dedicated bandwidth for EBS I/O.*

---

## Scenario 20: Data Security Best Practices
**Question**: Which EBS feature enhances the security of the data being stored?  
**A)** Data must be encrypted locally.  
**B)** Multi-factor authentication (MFA).  
**C)** EBS volume encryption.  
**D)** Data is only accessible by manual methods.  
**Correct Answer**: **C)** EBS volume encryption.  
*Explanation*: EBS volume encryption protects your data at rest and in transit, greatly enhancing data security.*

---

## Scenario 21: When to Use Magnetic Volumes
**Question**: Which scenario is most appropriate for using EBS magnetic volumes?  
**A)** For high-performance databases.  
**B)** For infrequently accessed data and lower-cost storage.  
**C)** For very fast storage needs.  
**D)** For active web servers.  
**Correct Answer**: **B)** For infrequently accessed data and lower-cost storage.  
*Explanation*: Magnetic volumes are suited for workloads where cost-efficiency is more critical than performance, such as infrequent access to data.*

---

## Scenario 22: EBS Volume Snapshots Best Practices
**Question**: What is a best practice for managing EBS snapshots?  
**A)** Taking manual snapshots every day.  
**B)** Regularly delete unneeded snapshots to save costs.  
**C)** Keep all snapshots indefinitely.  
**D)** Only take snapshots during off-peak hours.  
**Correct Answer**: **B)** Regularly delete unneeded snapshots to save costs.  
*Explanation*: Managing snapshots efficiently and deleting unnecessary ones helps keep costs down, as you are charged based on disk space used.*

---

## Scenario 23: EBS Volume Attachment
**Question**: How can you attach an EBS volume to a running EC2 instance?  
**A)** Only via command-line interface (CLI).  
**B)** Management console, CLI, or API.  
**C)** You cannot attach a volume to a running instance.  
**D)** Only during instance launch.  
**Correct Answer**: **B)** Management console, CLI, or API.  
*Explanation*: EBS volumes can be attached to running EC2 instances through the AWS Management Console, CLI, or AWS API.*

---

## Scenario 24: EBS Volume Availability Zone
**Question**: To which Availability Zone must an EBS volume reside in order to be attached to an EC2 instance?  
**A)** Any Availability Zone.  
**B)** The same Availability Zone as the EC2 instance.  
**C)** The priority zone defined by setting.  
**D)** The primary Availability Zone only.  
**Correct Answer**: **B)** The same Availability Zone as the EC2 instance.  
*Explanation*: An EBS volume must be in the same Availability Zone as the EC2 instance to which it is attached for it to function properly.*

---

## Scenario 25: Resizing EBS Volumes
**Question**: Can you resize an existing EBS volume while it is in use?  
**A)** No, it must be unmounted first.  
**B)** Yes, without stopping the instance.  
**C)** Yes, but it requires temporary detachment.  
**D)** No, resizing is not allowed.  
**Correct Answer**: **B)** Yes, without stopping the instance.  
*Explanation*: EBS volumes can be resized while they are in use, and the changes take effect without downtime.*

---

## Scenario 26: Automatic Snapshot Management
**Question**: How can you automate the management of EBS snapshots?  
**A)** Manually through the AWS console only.  
**B)** Using AWS Backup and lifecycle policies.  
**C)** By creating a Lambda function for snapshot automation.  
**D)** Using CLI scripts only.  
**Correct Answer**: **B)** Using AWS Backup and lifecycle policies.  
*Explanation*: AWS Backup and lifecycle policies can automate snapshot actions like creation, deletion, and transitioning to cheaper storage options.*

---

## Scenario 27: RAID with EBS Volumes
**Question**: How can you achieve higher performance and redundancy with EBS volumes?  
**A)** By using RAID (Redundant Array of Independent Disks) configurations.  
**B)** By only using single volumes.  
**C)** By connecting multiple instances to the same volume.  
**D)** By increasing IOPS only.  
**Correct Answer**: **A)** By using RAID (Redundant Array of Independent Disks) configurations.  
*Explanation*: Configuring EBS volumes in a RAID setup can enhance performance for certain workloads and provide redundancy against volume failure.*

---

## Scenario 28: Monitoring EBS
**Question**: Which CloudWatch metrics are important for monitoring EBS performance?  
**A)** CPU Utilization and Memory Usage.  
**B)** Read/Write Operations and Throughput.  
**C)** Network Ingress and Egress.  
**D)** EC2 Termination Count.  
**Correct Answer**: **B)** Read/Write Operations and Throughput.  
*Explanation*: Metrics like Read/Write Operations and Throughput are crucial for monitoring the performance of EBS volumes via CloudWatch.*

---

## Scenario 29: Multi-Attach Feature
**Question**: What is the purpose of the EBS Multi-Attach feature?  
**A)** To replicate volumes across multiple regions.  
**B)** To enable simultaneous attachment of a single volume to multiple instances.  
**C)** To attach multiple volumes to a single instance.  
**D)** To manage data redundancy between different services.  
**Correct Answer**: **B)** To enable simultaneous attachment of a single volume to multiple instances.  
*Explanation*: EBS Multi-Attach allows a single EBS volume to be attached to multiple EC2 instances at the same time, facilitating shared access to data.*

---

## Scenario 30: Cost Optimization
**Question**: Which of the following strategies can help reduce EBS costs?  
**A)** Using Provisioned IOPS for all applications.  
**B)** Regularly deleting unused EBS snapshots.  
**C)** Keeping EBS volumes attached to stopped EC2 instances.  
**D)** Creating more snapshots for redundancy.  
**Correct Answer**: **B)** Regularly deleting unused EBS snapshots.  
*Explanation*: Actively managing and deleting unnecessary snapshots can significantly reduce costs, as charges accumulate based on the storage size of snapshots.*

---

## Scenario 31: IoT and EBS
**Question**: Can Amazon EBS be used for IoT applications?  
**A)** No, EBS is only for traditional servers.  
**B)** Yes, if integrated with EC2 for data processing and storage.  
**C)** Yes, but only for temporary data storage.  
**D)** No, EBS cannot handle IoT workloads.  
**Correct Answer**: **B)** Yes, if integrated with EC2 for data processing and storage.  
*Explanation*: EBS can be effectively used alongside EC2 in IoT applications for data processing, storage, and management of IoT data.*

---

## Scenario 32: EBS Pricing Model
**Question**: EBS pricing is primarily based on which of the following?  
**A)** Number of instances using the volume.  
**B)** Storage capacity provisioned and IOPS.  
**C)** Total data downloaded from the volume.  
**D)** API requests to access the EBS volumes.  
**Correct Answer**: **B)** Storage capacity provisioned and IOPS.  
*Explanation*: EBS pricing is determined by the provisioned storage capacity (measured in GB) and the IOPS depending on the volume type selected.*

---

## Scenario 33: EBS for Database Applications
**Question**: Which EBS volume type is most suitable for database applications requiring high IOPS?  
**A)** General Purpose SSD (gp2).  
**B)** Magnetic (standard) volumes.  
**C)** Provisioned IOPS SSD (io1 or io2).  
**D)** Cold HDD (sc1).  
**Correct Answer**: **C)** Provisioned IOPS SSD (io1 or io2).  
*Explanation*: Provisioned IOPS SSD volumes are specifically designed for workloads requiring high IOPS, making them ideal for database applications.*

---

## Scenario 34: Deleting EBS Volumes
**Question**: What should you consider before deleting an EBS volume?  
**A)** The volume must be detached from any EC2 instance.  
**B)** Ensure backups are done for the data.  
**C)** It will immediately release tripled costs.  
**D)** Both A and B are correct.  
**Correct Answer**: **D)** Both A and B are correct.  
*Explanation*: Prior to deleting an EBS volume, it is crucial to detach it from any instances and ensure that data is backed up if needed.*

---

## Scenario 35: Volume Types for Workloads
**Question**: What EBS volume type should be used for workloads that require low delay and high throughput performance?  
**A)** Cold HDD (sc1).  
**B)** Provisioned IOPS SSD (io1 or io2).  
**C)** General Purpose SSD (gp2).  
**D)** Magnetic volumes for archival data.  
**Correct Answer**: **B)** Provisioned IOPS SSD (io1 or io2).  
*Explanation*: Provisioned IOPS SSD (io1 or io2) volumes are specifically optimized for applications that need low-latency and high-throughput performance.*

---

## Scenario 36: Encryption Keys
**Question**: Which type of key can you use for encrypting EBS volumes?  
**A)** Only AWS keys.  
**B)** Your own KMS keys in AWS Key Management Service.  
**C)** Keys generated by EC2 instances.  
**D)** Public keys only.  
**Correct Answer**: **B)** Your own KMS keys in AWS Key Management Service.  
*Explanation*: EBS volumes can be encrypted using your own customer-managed keys through AWS Key Management Service (KMS).*

---

## Scenario 37: Shared Storage
**Question**: Is it possible to share an EBS volume across multiple instances simultaneously?  
**A)** Yes, through Multi-Attach feature.  
**B)** No, EBS volumes can only be attached to one instance at a time.  
**C)** Yes, if they are in different regions.  
**D)** Only CloudFront can provide shared access.  
**Correct Answer**: **A)** Yes, through Multi-Attach feature.  
*Explanation*: EBS Multi-Attach allows a single volume to be attached to multiple EC2 instances, facilitating shared access.*

---

## Scenario 38: EBS Volume Backup Options
**Question**: What is the preferred method for backing up an EBS volume?  
**A)** Copying data to an on-premises disk.  
**B)** Taking a snapshot of the volume.  
**C)** Using temporary storage on the EC2 instance.  
**D)** Transferring files to S3 directly.  
**Correct Answer**: **B)** Taking a snapshot of the volume.  
*Explanation*: The preferred backup method for EBS volumes is to take snapshots, allowing for point-in-time recovery and efficient storage management.*

---

## Scenario 39: Cross-Region Snapshots
**Question**: Can you copy EBS snapshots across regions?  
**A)** Yes, using the AWS Management Console or CLI.  
**B)** No, snapshots cannot be copied between regions.  
**C)** Only snapshots created in the same region can be copied.  
**D)** Yes, but only for magnetic volumes.  
**Correct Answer**: **A)** Yes, using the AWS Management Console or CLI.  
*Explanation*: EBS snapshots can be easily copied across AWS regions, allowing you to create backups in different geographic locations for disaster recovery.*

---

## Scenario 40: Monitoring Snapshot Use
**Question**: What metric is important for monitoring the usage of EBS snapshots?  
**A)** Snapshot Count.  
**B)** Snapshot Read/Write Latency.  
**C)** Total Snapshot Size in GB.  
**D)** Snapshot Warning Alerts.  
**Correct Answer**: **C)** Total Snapshot Size in GB.  
*Explanation*: Monitoring total snapshot size helps manage costs and understand storage consumption related to EBS snapshots.*

---

## Scenario 41: Tags on EBS Volumes
**Question**: What is the purpose of tagging EBS volumes?  
**A)** To improve performance.  
**B)** For billing and resource management.  
**C)** To encrypt data.  
**D)** For automatic backups.  
**Correct Answer**: **B)** For billing and resource management.  
*Explanation*: Tags on EBS volumes can be used for tracking costs, categorizing resources, and managing permissions effectively.*

---

## Scenario 42: EBS Volume Backup Frequency
**Question**: What backup frequency should typically be adopted for mission-critical applications using EBS?  
**A)** Weekly only.  
**B)** Daily snapshots.  
**C)** Monthly backups.  
**D)** Only when necessary.  
**Correct Answer**: **B)** Daily snapshots.  
*Explanation*: For mission-critical applications, taking daily snapshots is a best practice to ensure data availability and recoverability.*

---

## Scenario 43: Setting IOPS
**Question**: When using Provisioned IOPS for an EBS volume, how do you determine the necessary IOPS?  
**A)** Based on application requirements and testing.  
**B)** It is fixed regardless of application.  
**C)** You must guess based on volume size.  
**D)** IOPS requirements are determined by region.  
**Correct Answer**: **A)** Based on application requirements and testing.  
*Explanation*: The required IOPS should be determined through application testing and performance analysis to ensure the volume meets performance needs.*

---

## Scenario 44: Migrating Data to EBS
**Question**: Which feature helps with migrating existing data to EBS volumes?  
**A)** AWS Database Migration Service.  
**B)** AWS Snowball.  
**C)** EBS Volume Converter.  
**D)** You cannot migrate data.  
**Correct Answer**: **B)** AWS Snowball.  
*Explanation*: AWS Snowball can be used to migrate large datasets to EBS from on-premises systems efficiently.*

---

## Scenario 45: EBS in Multi-Region Architectures
**Question**: How should EBS snapshots be managed in a multi-region architecture?  
**A)** Keep separate backups for each region.  
**B)** Use multi-region EBS volume replication.  
**C)** AWS doesn't support multi-region architectures.  
**D)** Manage snapshots only in the primary region.  
**Correct Answer**: **A)** Keep separate backups for each region.  
*Explanation*: In multi-region architectures, it's essential to manage and maintain snapshots independently in each region for disaster recovery and availability.*

---

## Scenario 46: Availability Zones and EBS
**Question**: Why is it important to have EBS volumes in the same Availability Zone as the attached EC2 instance?  
**A)** To enhance IOPS performance.  
**B)** To reduce latency.  
**C)** Both A and B are correct.  
**D)** All storage must be in the same zone for security.  
**Correct Answer**: **C)** Both A and B are correct.  
*Explanation*: Placing EBS volumes in the same Availability Zone as the EC2 instance minimizes latency and optimizes IOPS performance.*

---

## Scenario 47: EBS and Scaling Out
**Question**: If more storage space is needed for an application running on EBS, what is the best practice?  
**A)** Increase the instance type in size.  
**B)** Attach a new EBS volume to the instance.  
**C)** Resize the existing volume to a larger size.  
**D)** Store data in an S3 bucket instead.  
**Correct Answer**: **C)** Resize the existing volume to a larger size.  
*Explanation*: The best practice is to either resize the existing EBS volume or attach additional volumes based on application requirements.*

---

## Scenario 48: Diagnostic Logs
**Question**: Which service can you use to track API requests for EBS volume modifications?  
**A)** Amazon CloudWatch.  
**B)** AWS CloudTrail.  
**C)** AWS Config.  
**D)** Amazon SNS.  
**Correct Answer**: **B)** AWS CloudTrail.  
*Explanation*: AWS CloudTrail provides logs of all API activity, enabling you to track modifications made to EBS volumes and other resources.*

---

## Scenario 49: Data Consistency
**Question**: How does Amazon EBS ensure data consistency during high-volume I/O operations?  
**A)** By using file systems only.  
**B)** Through the use of snapshots.  
**C)** By providing multi-attach EBS volumes.  
**D)** By implementing caching on EC2 instances.  
**Correct Answer**: **B)** Through the use of snapshots.  
*Explanation*: EBS snapshots ensure data consistency during I/O operations by capturing a point-in-time copy of the volume.*

---

## Scenario 50: EBS Volume Configuration
**Question**: Which consideration is crucial when configuring EBS volumes for production workloads?  
**A)** Selecting magnetic storage as the default option.  
**B)** Defining the correct IOPS for application requirements.  
**C)** Choosing the smallest possible volume size.  
**D)** Setting volume encryption for all instances.  
**Correct Answer**: **B)** Defining the correct IOPS for application requirements.  
*Explanation*: Properly defining IOPS and other performance requirements is critical for ensuring that EBS can support production workloads effectively.*

---

---