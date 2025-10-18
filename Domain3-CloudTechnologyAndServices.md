# Cloud Technology and Services

---

### Question 1

A company has developed an eCommerce web application in AWS. What should they do to ensure that the application has the highest level of availability?

&nbsp;&nbsp;&nbsp;&nbsp;A. Deploy the application across multiple Availability Zones and Edge locations.  
&nbsp;&nbsp;&nbsp;&nbsp;B. Deploy the application across multiple Availability Zones and subnets.  
&nbsp;&nbsp;&nbsp;&nbsp;C. Deploy the application across multiple Regions and Availability Zones.  
&nbsp;&nbsp;&nbsp;&nbsp;D. Deploy the application across multiple VPC's and subnets.

<details><summary>Click to reveal</summary><br>**Correct Answer:** C<br><br>**Explanation:** Deploying across multiple Regions provides global high availability and disaster recovery. Availability Zones are within a Region for local redundancy, but for highest availability, multi-Region is best. Edge locations are for caching, VPCs are network isolation.</details>

---

### Question 2

What does AWS Snowball provide? (Choose TWO)

&nbsp;&nbsp;&nbsp;&nbsp;A. Built-in computing capabilities that allow customers to process data locally.  
&nbsp;&nbsp;&nbsp;&nbsp;B. A catalog of third-party software solutions that customers need to build solutions and run their businesses.  
&nbsp;&nbsp;&nbsp;&nbsp;C. A hybrid cloud storage between on-premises environments and the AWS Cloud.  
&nbsp;&nbsp;&nbsp;&nbsp;D. An Exabyte-scale data transfer service that allows you to move extremely large amounts of data to AWS.  
&nbsp;&nbsp;&nbsp;&nbsp;E. Secure transfer of large amounts of data into and out of the AWS.

<details><summary>Click to reveal</summary><br>**Correct Answer:** A, E<br><br>**Explanation:** AWS Snowball is a petabyte-scale data transport device with on-board storage and compute capabilities (A) for secure data transfer (E). Option B is AWS Marketplace, C is Storage Gateway, D is Snowmobile for exabyte-scale.</details>

---

### Question 3

A Japanese company hosts their applications on Amazon EC2 instances in the Tokyo Region. The company has opened new branches in the United States, and the US users are complaining of high latency. What can the company do to reduce latency for the users in the US while minimizing costs?

&nbsp;&nbsp;&nbsp;&nbsp;A. Applying the Amazon Connect latency-based routing policy.  
&nbsp;&nbsp;&nbsp;&nbsp;B. Registering a new US domain name to serve the users in the US.  
&nbsp;&nbsp;&nbsp;&nbsp;C. Building a new data center in the US and implementing a hybrid model.  
&nbsp;&nbsp;&nbsp;&nbsp;D. Deploying new Amazon EC2 instances in a Region located in the US.

<details><summary>Click to reveal</summary><br>**Correct Answer:** D<br><br>**Explanation:** Deploying in a US Region like us-east-1 reduces latency by bringing compute closer to users. Amazon Connect is for contact centers, domain name doesn't affect latency, hybrid is more complex and costly.</details>

---

### Question 4

A company has decided to migrate its Oracle database to AWS. Which AWS service can help achieve this without negatively impacting the functionality of the source database?

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS OpsWorks.  
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Database Migration Service.  
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Server Migration Service.  
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Application Discovery Service.

<details><summary>Click to reveal</summary><br>**Correct Answer:** B<br><br>**Explanation:** AWS DMS supports continuous data replication with low downtime for database migrations, supporting Oracle as source and target. OpsWorks is for configuration management, SMS for servers, Discovery for inventory.</details>

---

### Question 5

What does Amazon CloudFront use to distribute content to global users with low latency?

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Global Accelerator.  
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Regions.  
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Edge Locations.  
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Availability Zones.

<details><summary>Click to reveal</summary><br>**Correct Answer:** C<br><br>**Explanation:** CloudFront uses edge locations to cache content closer to users, reducing latency. Global Accelerator is for traffic optimization, Regions are larger geographic areas, AZs are for high availability within a Region.</details>

---

### Question 6

The identification process of an online financial services company requires that new users must complete an online interview with their security team. The completed recorded interviews are only required in the event of a legal issue or a regulatory compliance breach. What is the most cost-effective service to store the recorded videos?

&nbsp;&nbsp;&nbsp;&nbsp;A. S3 Intelligent-Tiering.  
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Marketplace.  
&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon S3 Glacier Deep Archive.  
&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon EBS.

<details><summary>Click to reveal</summary><br>**Correct Answer:** C<br><br>**Explanation:** S3 Glacier Deep Archive is the lowest-cost storage for long-term archiving with retrieval in hours, ideal for rarely accessed data. Intelligent-Tiering is for unknown patterns, Marketplace is for software, EBS is for block storage.</details>

---

### Question 7

Which service provides DNS in the AWS cloud?

&nbsp;&nbsp;&nbsp;&nbsp;A. Route 53.  
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Config.  
&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon CloudFront.  
&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon EMR.

<details><summary>Click to reveal</summary><br>**Correct Answer:** A<br><br>**Explanation:** Amazon Route 53 is a scalable DNS web service for routing traffic to internet applications. Config is for resource configuration, CloudFront for content delivery, EMR for big data processing.</details>

---

### Question 8

A company is deploying a new two-tier web application in AWS. Where should the most frequently accessed data be stored so that the application's response time is optimal?

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS OpsWorks.  
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Storage Gateway.  
&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon EBS volume.  
&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon ElastiCache.

<details><summary>Click to reveal</summary><br>**Correct Answer:** D<br><br>**Explanation:** Amazon ElastiCache (Redis/Memcached) provides in-memory caching for sub-millisecond response times. EBS is block storage, OpsWorks is configuration, Storage Gateway is hybrid.</details>

---

### Question 9

Which of the following can be described as a global content delivery network (CDN) service?

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS VPN.  
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Direct Connect.  
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Regions.  
&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon CloudFront.

<details><summary>Click to reveal</summary><br>**Correct Answer:** D<br><br>**Explanation:** Amazon CloudFront is AWS's CDN service delivering content globally from edge locations. VPN is connectivity, Direct Connect is dedicated, Regions are data centers.</details>

---

### Question 10

Which service provides object-level storage in AWS?

&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon EBS.  
&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon Instance Store.  
&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon EFS.  
&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon S3.

<details><summary>Click to reveal</summary><br>**Correct Answer:** D<br><br>**Explanation:** Amazon S3 provides durable object storage for any amount of data. EBS is block, Instance Store is ephemeral, EFS is file storage.</details>

---

### Question 11

Which AWS service automatically scales compute capacity based on incoming requests?

&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon EC2 Auto Scaling  
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Lambda  
&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon ECS  
&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon EKS

<details><summary>Click to reveal</summary><br>**Correct Answer:** B<br><br>**Explanation:** AWS Lambda automatically scales from zero to thousands of instances based on request volume. EC2 Auto Scaling requires configuration, ECS/EKS need scaling policies.</details>

---

### Question 12

A company needs to process streaming data in real-time. Which service is best suited?

&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon S3  
&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon Kinesis  
&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon RDS  
&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon EBS

<details><summary>Click to reveal</summary><br>**Correct Answer:** B<br><br>**Explanation:** Amazon Kinesis processes and analyzes real-time streaming data. S3 is object storage, RDS is relational database, EBS is block storage.</details>

---

### Question 13

Which service provides a fully managed Hadoop framework?

&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon EMR  
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Batch  
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Glue  
&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon Athena

<details><summary>Click to reveal</summary><br>**Correct Answer:** A<br><br>**Explanation:** Amazon EMR provides managed Hadoop/Spark for big data processing. Batch is for jobs, Glue is ETL, Athena is query service.</details>

---

### Question 14

What is the PRIMARY use case for Amazon SQS?

&nbsp;&nbsp;&nbsp;&nbsp;A. Object storage  
&nbsp;&nbsp;&nbsp;&nbsp;B. Message queuing  
&nbsp;&nbsp;&nbsp;&nbsp;C. DNS routing  
&nbsp;&nbsp;&nbsp;&nbsp;D. Content delivery

<details><summary>Click to reveal</summary><br>**Correct Answer:** B<br><br>**Explanation:** Amazon SQS is a fully managed message queuing service for decoupling applications. S3 is storage, Route 53 is DNS, CloudFront is CDN.</details>

---

### Question 15

Which service provides a virtual private cloud networking environment?

&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon VPC  
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Direct Connect  
&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon Route 53  
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Transit Gateway

<details><summary>Click to reveal</summary><br>**Correct Answer:** A<br><br>**Explanation:** Amazon VPC provides isolated cloud networking. Direct Connect is dedicated connection, Route 53 is DNS, Transit Gateway connects VPCs.</details>

---
