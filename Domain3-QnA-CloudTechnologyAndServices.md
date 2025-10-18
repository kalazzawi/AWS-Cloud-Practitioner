# Cloud Technology and Services

**Total Questions: 50**  

---

### Question 1

A company has developed an eCommerce web application in AWS. What should they do to ensure that the application has the highest level of availability?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Deploy the application across multiple Availability Zones and Edge locations.
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Deploy the application across multiple Availability Zones and subnets.
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Deploy the application across multiple Regions and Availability Zones.
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Deploy the application across multiple VPC's and subnets.
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Deploying across multiple Regions provides global high availability and disaster recovery. Availability Zones are within a Region for local redundancy, but for highest availability, multi-Region is best. Edge locations are for caching, VPCs are network isolation.
</details>

---

### Question 2

What does AWS Snowball provide?
 (Choose TWO)
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Built-in computing capabilities that allow customers to process data locally.
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. A catalog of third-party software solutions that customers need to build solutions and run their businesses.
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. A hybrid cloud storage between on-premises environments and the AWS Cloud.
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. An Exabyte-scale data transfer service that allows you to move extremely large amounts of data to AWS.
<br>&nbsp;&nbsp;&nbsp;&nbsp;E. Secure transfer of large amounts of data into and out of the AWS.
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A, E
> **Explanation:** AWS Snowball is a petabyte-scale data transport device with on-board storage and compute capabilities (A) for secure data transfer (E). Option B is AWS Marketplace, C is Storage Gateway, D is Snowmobile for exabyte-scale.
</details>

---

### Question 3

A Japanese company hosts their applications on Amazon EC2 instances in the Tokyo Region. The company has opened new branches in the United States, and the US users are complaining of high latency. What can the company do to reduce latency for the users in the US while minimizing costs?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Applying the Amazon Connect latency-based routing policy.
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Registering a new US domain name to serve the users in the US.
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Building a new data center in the US and implementing a hybrid model.
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Deploying new Amazon EC2 instances in a Region located in the US.
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D

> **Explanation:** Deploying in a US Region like us-east-1 reduces latency by bringing compute closer to users. Amazon Connect is for contact centers, domain name doesn't affect latency, hybrid is more complex and costly.
</details>

---

### Question 4

A company has decided to migrate its Oracle database to AWS. Which AWS service can help achieve this without negatively impacting the functionality of the source database?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. AWS OpsWorks.
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Database Migration Service.
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Server Migration Service.
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Application Discovery Service.
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** AWS DMS supports continuous data replication with low downtime for database migrations, supporting Oracle as source and target. OpsWorks is for configuration management, SMS for servers, Discovery for inventory.
</details>

---

### Question 5

What does Amazon CloudFront use to distribute content to global users with low latency?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Global Accelerator.
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Regions.
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Edge Locations.
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Availability Zones.
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** CloudFront uses edge locations to cache content closer to users, reducing latency. Global Accelerator is for traffic optimization, Regions are larger geographic areas, AZs are for high availability within a Region.
</details>

---

### Question 6

The identification process of an online financial services company requires that new users must complete an online interview with their security team. The completed recorded interviews are only required in the event of a legal issue or a regulatory compliance breach. What is the most cost-effective service to store the recorded videos?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. S3 Intelligent-Tiering.
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Marketplace.
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon S3 Glacier Deep Archive.
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon EBS.
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** S3 Glacier Deep Archive is the lowest-cost storage for long-term archiving with retrieval in hours, ideal for rarely accessed data. Intelligent-Tiering is for unknown patterns, Marketplace is for software, EBS is for block storage.
</details>

---

### Question 7

Which service provides DNS in the AWS cloud?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Route 53.
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Config.
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon CloudFront.
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon EMR.
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Amazon Route 53 is a scalable DNS web service for routing traffic to internet applications. Config is for resource configuration, CloudFront for content delivery, EMR for big data processing.
</details>

---

### Question 8

A company is deploying a new two-tier web application in AWS. Where should the most frequently accessed data be stored so that the application's response time is optimal?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. AWS OpsWorks.
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Storage Gateway.
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon EBS volume.
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon ElastiCache.
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** Amazon ElastiCache (Redis/Memcached) provides in-memory caching for sub-millisecond response times. EBS is block storage, OpsWorks is configuration, Storage Gateway is hybrid.
</details>

---

### Question 9

Which of the following can be described as a global content delivery network (CDN) service?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. AWS VPN.
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Direct Connect.
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Regions.
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon CloudFront.
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** Amazon CloudFront is AWS's CDN service delivering content globally from edge locations. VPN is connectivity, Direct Connect is dedicated, Regions are data centers.
</details>

---

### Question 10

Which service provides object-level storage in AWS?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon EBS.
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon Instance Store.
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon EFS.
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon S3.
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** Amazon S3 provides durable object storage for any amount of data. EBS is block, Instance Store is ephemeral, EFS is file storage.
</details>

---

### Question 11

Which AWS service automatically scales compute capacity based on incoming requests?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon EC2 Auto Scaling
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Lambda
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon ECS
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon EKS
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** AWS Lambda automatically scales from zero to thousands of instances based on request volume. EC2 Auto Scaling requires configuration, ECS/EKS need scaling policies.
</details>

---

### Question 12

A company needs to process streaming data in real-time. Which service is best suited?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon S3
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon Kinesis
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon RDS
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon EBS
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Amazon Kinesis processes and analyzes real-time streaming data. S3 is object storage, RDS is relational database, EBS is block storage.
</details>

---

### Question 13

Which service provides a fully managed Hadoop framework?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon EMR
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Batch
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Glue
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon Athena
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Amazon EMR provides managed Hadoop/Spark for big data processing. Batch is for jobs, Glue is ETL, Athena is query service.
</details>

---

### Question 14

What is the PRIMARY use case for Amazon SQS?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Object storage
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Message queuing
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. DNS routing
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Content delivery
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Amazon SQS is a fully managed message queuing service for decoupling applications. S3 is storage, Route 53 is DNS, CloudFront is CDN.
</details>

---

### Question 15

Which service provides a virtual private cloud networking environment?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon VPC
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Direct Connect
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon Route 53
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Transit Gateway
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Amazon VPC provides isolated cloud networking. Direct Connect is dedicated connection, Route 53 is DNS, Transit Gateway connects VPCs.
</details>

---

### Question 16

Which service is used for batch processing jobs?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Batch
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon EMR
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Lambda
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon ECS
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** AWS Batch manages and scales batch computing workloads without provisioning infrastructure.
</details>

---

### Question 17

What is the PRIMARY function of Amazon Elastic Block Store (EBS)?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Object storage
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Block storage for EC2
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. File storage
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Archival storage
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** EBS provides persistent block-level storage volumes for EC2 instances.
</details>

---

### Question 18

Which database service provides the highest performance for transactional workloads?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon RDS
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon DynamoDB
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon Aurora
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon Redshift
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Aurora is a MySQL/PostgreSQL-compatible relational database with up to 5x performance of standard MySQL.
</details>

---

### Question 19

What is Amazon Elastic File System (EFS)?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Block storage
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Object storage
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Scalable file storage
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Archival storage
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** EFS provides scalable, shared file storage for multiple EC2 instances and on-premises servers.
</details>

---

### Question 20

Which service provides serverless container execution?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon ECS
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Fargate
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon EKS
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Batch
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Fargate runs containers without managing servers or clusters.
</details>

---

### Question 21

What is the PRIMARY use case for Amazon Simple Notification Service (SNS)?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Message queuing
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Push notifications
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Data streaming
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. File storage
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** SNS enables fan-out messaging for push notifications, SMS, and email.
</details>

---

### Question 22

Which service allows querying data in S3 using SQL?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon Athena
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon Redshift
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Glue
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon QuickSight
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Athena is a serverless interactive query service for S3 data using standard SQL.
</details>

---

### Question 23

What is Amazon Elastic Container Service (ECS)?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Serverless compute
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Container orchestration
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Kubernetes service
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Batch processing
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** ECS is AWS's container orchestration service for Docker containers.
</details>

---

### Question 24

Which service provides managed Apache Kafka?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon MSK
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon MQ
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon Kinesis
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Batch
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Amazon Managed Streaming for Kafka (MSK) is a fully managed Kafka service.
</details>

---

### Question 25

What is the PRIMARY benefit of Amazon RDS Multi-AZ?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Read replicas
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Automatic failover
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Performance scaling
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Cost reduction
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Multi-AZ provides high availability with automatic failover to a standby instance.
</details>

---

### Question 26

Which service is used for ETL workloads?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Glue
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon EMR
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Batch
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon Kinesis
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** AWS Glue is a fully managed ETL service that automates data preparation.
</details>

---

### Question 27

What is Amazon Simple Storage Service (S3) Select?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Query data in place
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Data transfer
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. File sharing
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Backup service
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** S3 Select allows running SQL queries directly on objects in S3.
</details>

---

### Question 28

Which service provides managed Elasticsearch?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon OpenSearch Service
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon CloudSearch
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon Kendra
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Glue
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** OpenSearch Service (formerly Elasticsearch Service) provides managed search and analytics.
</details>

---

### Question 29

What is AWS App Runner?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Serverless web app service
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Container service
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. CI/CD pipeline
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Database service
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** App Runner deploys and scales containerized web apps automatically.
</details>

---

### Question 30

Which service provides graph database?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon Neptune
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon DynamoDB
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon RDS
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon Redshift
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Neptune is a fully managed graph database for relationship-driven use cases.
</details>

---

### Question 31

What is Amazon Timestream?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Time series database
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Relational database
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. NoSQL database
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Data warehouse
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Timestream is a serverless time series database for IoT and operational data.
</details>

---

### Question 32

Which service provides managed Redis/Memcached?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon ElastiCache
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon DynamoDB
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon RDS
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon OpenSearch
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** ElastiCache provides in-memory caching with Redis and Memcached.
</details>

---

### Question 33

What is AWS Ground Station?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Satellite ground station service
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. IoT service
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Networking service
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Compute service
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Ground Station provides satellite data ingestion and processing.
</details>

---

### Question 34

Which service provides serverless GraphQL APIs?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. AWS AppSync
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon API Gateway
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon Neptune
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Amplify
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** AppSync is a managed GraphQL service with real-time data sync.
</details>

---

### Question 35

What is Amazon Managed Grafana?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Monitoring visualization
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Log analytics
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Data warehouse
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. ETL service
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Managed Grafana provides observability dashboards for metrics.
</details>

---

### Question 36

Which service provides quantum computing?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon Braket
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Outposts
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Local Zones
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Wavelength
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Braket provides access to quantum computers and simulators.
</details>

---

### Question 37

What is AWS Outposts?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. On-premises AWS infrastructure
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Hybrid cloud storage
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Edge computing
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Data transfer
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Outposts extends AWS infrastructure and services to on-premises.
</details>

---

### Question 38

Which service provides low-latency edge computing for 5G?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Wavelength
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Local Zones
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Outposts
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Snowball
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Wavelength runs AWS services in telco edge locations for 5G.
</details>

---

### Question 39

What is AWS Local Zones?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Edge locations for low latency
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. On-premises racks
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Data transfer devices
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Satellite service
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Local Zones place compute/storage closer to end users for low latency.
</details>

---

### Question 40

Which service provides ML model training?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon SageMaker
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon Rekognition
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon Lex
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon Comprehend
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** SageMaker is a fully managed ML platform for building, training, and deploying models.
</details>

---

### Question 41

What is Amazon Forecast?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Time series forecasting
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Image recognition
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Speech recognition
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Text analysis
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Forecast uses ML to generate time series forecasts without requiring ML expertise.
</details>

---

### Question 42

Which service provides computer vision?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon Rekognition
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon Textract
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon Transcribe
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon Polly
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Rekognition provides image/video analysis, face detection, and content moderation.
</details>

---

### Question 43

What is Amazon Textract?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Document text extraction
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Speech to text
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Text to speech
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Translation
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Textract automatically extracts text, handwriting, and data from documents.
</details>

---

### Question 44

Which service provides conversational AI?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon Lex
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon Connect
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon Chime
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon Pinpoint
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Lex builds chatbots using voice and text with the same deep learning as Alexa.
</details>

---

### Question 45

What is Amazon Translate?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Real-time language translation
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Speech recognition
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Text analysis
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Document analysis
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Translate uses ML to provide real-time text translation in supported languages.
</details>

---

### Question 46

Which service provides business intelligence?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon QuickSight
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon Athena
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon Redshift
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Glue
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** QuickSight is a fast, serverless BI service for creating dashboards.
</details>

---

### Question 47

What is Amazon Managed Blockchain?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Hyperledger Fabric and Ethereum
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Database service
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Messaging service
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Storage service
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Managed Blockchain simplifies creation of scalable blockchain networks.
</details>

---

### Question 48

Which service provides IoT device management?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. AWS IoT Core
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. AWS IoT Device Defender
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. AWS IoT Analytics
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. All of the above
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** IoT services provide connectivity, security, analytics, and management.
</details>

---

### Question 49

What is Amazon Augmented Reality and Virtual Reality (AR/VR)?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Sumerian
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. SageMaker
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Kinesis Video Streams
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. All of the above
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** Sumerian builds AR/VR apps, SageMaker for ML, Kinesis for video streaming.
</details>

---

### Question 50

Which service provides game development?

<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon GameLift
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon Lumberyard
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon Sumerian
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. All of the above
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** GameLift for multiplayer servers, Lumberyard engine, Sumerian for VR games.
</details>


---

