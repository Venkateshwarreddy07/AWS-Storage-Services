# AWS-Storage-Services

2. Storage
Amazon S3 (Standard, Intelligent Tiering, Glacier, Lifecycle Policies)
	• Concepts:
		○ S3 Standard: General-purpose object storage with high durability and availability.
		○ Intelligent Tiering: Optimizes storage costs by automatically moving data between tiers based on access patterns.
		○ Glacier: Archival storage for infrequently accessed data.
		○ Lifecycle Policies: Automates transitions between storage classes and data expiration.
	• Real-Time Example:
		○ S3 Standard: Storing images and videos for a social media platform.
		○ Intelligent Tiering: Hosting application logs where access patterns vary over time.
		○ Glacier: Archiving regulatory compliance records for 7 years.
		○ Lifecycle Policies: Automatically moving logs from Standard to Glacier after 30 days.
	• Use Cases:
		○ Standard: Frequently accessed content like media files or backups.
		○ Intelligent Tiering: Cost-optimized storage with uncertain access patterns.
		○ Glacier: Long-term, infrequent data access (e.g., backups, archives).
	• Secondary Options: Azure Blob Storage, Google Cloud Storage, AWS EBS for block-level storage.

EBS and EFS
	• Concepts:
		○ EBS (Elastic Block Store): Block storage for EC2 instances; ideal for high-performance databases or OS volumes.
		○ EFS (Elastic File System): Managed file storage for shared access across instances.
	• Real-Time Example:
		○ EBS: Hosting a MySQL database on an EC2 instance with high IOPS requirements.
		○ EFS: A media production team shares video files across multiple editors using EFS.
	• Use Cases:
		○ EBS: Databases, application storage, boot volumes.
		○ EFS: File-sharing systems, CMS, and data collaboration.
	• Secondary Options: FSx for shared file storage, Azure Disk Storage.

AWS Backup and Storage Gateway
	• Concepts:
		○ AWS Backup: Centralized backup management for AWS resources like EC2, RDS, and DynamoDB.
		○ Storage Gateway: Hybrid cloud storage integrating on-premises environments with AWS cloud storage.
	• Real-Time Example:
		○ AWS Backup: Automatically backing up RDS databases with compliance policies.
		○ Storage Gateway: A manufacturing company synchronizes on-premise file servers with S3.
	• Use Cases:
		○ AWS Backup: Disaster recovery and compliance.
		○ Storage Gateway: Hybrid cloud storage solutions.
	• Secondary Options: Veeam, Rubrik for backups, Azure Backup.

Amazon FSx
	• Concepts:
		○ Windows File Server: Managed file storage for Windows applications.
		○ Lustre: High-performance file system optimized for workloads like machine learning or big data analytics.
	• Real-Time Example:
		○ FSx Windows: A healthcare company hosting EMR applications requiring shared file storage.
		○ FSx Lustre: A financial services firm running real-time analytics on large datasets.
	• Use Cases:
		○ Windows File Server: File storage for Windows-based applications.
		○ Lustre: High-performance computing and analytics.
	• Secondary Options: EFS, NetApp Cloud Volumes.
![image](https://github.com/user-attachments/assets/ed52197f-6698-407e-afee-22c1516edff2)
