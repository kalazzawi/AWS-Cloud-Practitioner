# Cloud Concepts

**Total Questions: 150**  

---

### Question 1

Which of the following is an example of horizontal scaling in the AWS Cloud?

&nbsp;&nbsp;&nbsp;&nbsp;A. Replacing an existing EC2 instance with a larger, more powerful one.

&nbsp;&nbsp;&nbsp;&nbsp;B. Increasing the compute capacity of a single EC2 instance to address the growing demands of an application.

&nbsp;&nbsp;&nbsp;&nbsp;C. Adding more RAM capacity to an EC2 instance.

&nbsp;&nbsp;&nbsp;&nbsp;D. Adding more EC2 instances of the same size to handle an increase in traffic.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** Horizontal scaling, also known as scaling out, involves adding more instances to distribute the load across multiple servers, which enhances availability and fault tolerance. This is a key principle of cloud architecture. Options A, B, and C describe vertical scaling, or scaling up, where you increase the resources of a single instance, which has limits and can create single points of failure.
</details>

---

### Question 2

A company has developed an eCommerce web application in AWS. What should they do to ensure that the application has the highest level of availability?

&nbsp;&nbsp;&nbsp;&nbsp;A. Deploy the application across multiple Availability Zones and Edge locations.
&nbsp;&nbsp;&nbsp;&nbsp;B. Deploy the application across multiple Availability Zones and subnets.
&nbsp;&nbsp;&nbsp;&nbsp;C. Deploy the application across multiple Regions and Availability Zones.
&nbsp;&nbsp;&nbsp;&nbsp;D. Deploy the application across multiple VPC’s and subnets.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Deploying across multiple Regions provides global high availability and disaster recovery. Availability Zones are within a Region for local redundancy, but for highest availability, multi-Region is best. Edge locations are for caching, VPCs are network isolation.
</details>

---

### Question 3

Adjusting compute capacity dynamically to reduce cost is an implementation of which AWS cloud best practice?

&nbsp;&nbsp;&nbsp;&nbsp;A. Build security in every layer.
&nbsp;&nbsp;&nbsp;&nbsp;B. Parallelize tasks.
&nbsp;&nbsp;&nbsp;&nbsp;C. Implement elasticity.
&nbsp;&nbsp;&nbsp;&nbsp;D. Adopt monolithic architecture.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Elasticity is the ability to automatically add or remove resources based on demand, which optimizes costs by ensuring you only pay for what you use. This is a core AWS best practice under the Well-Architected Framework. Option A is security, B is for performance, and D is the opposite of recommended microservices architecture.
</details>

---

### Question 4

What are the benefits of having infrastructure hosted in AWS? (Choose TWO)

&nbsp;&nbsp;&nbsp;&nbsp;A. Increasing speed and agility.
&nbsp;&nbsp;&nbsp;&nbsp;B. There is no need to worry about security.
&nbsp;&nbsp;&nbsp;&nbsp;C. Gaining complete control over the physical infrastructure.
&nbsp;&nbsp;&nbsp;&nbsp;D. Operating applications on behalf of customers.
&nbsp;&nbsp;&nbsp;&nbsp;E. All of the physical security and most of the data/network security are taken care of for you.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A, E
> **Explanation:** AWS provides speed and agility by allowing rapid provisioning of resources, and handles physical and network security under the shared responsibility model, freeing customers to focus on application-level security. Option B is incorrect as customers are responsible for security in the cloud, C is not true as AWS manages physical infrastructure, and D is not a benefit as customers manage their own applications.
</details>

---

### Question 5

What is the advantage of the AWS-recommended practice of "decoupling" applications?

&nbsp;&nbsp;&nbsp;&nbsp;A. Allows treating an application as a single, cohesive unit.
&nbsp;&nbsp;&nbsp;&nbsp;B. Reduces inter-dependencies so that failures do not impact other components of the application.
&nbsp;&nbsp;&nbsp;&nbsp;C. Allows updates of any monolithic application quickly and easily.
&nbsp;&nbsp;&nbsp;&nbsp;D. Allows tracking of any API call made to any AWS service.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Decoupling reduces dependencies between components, making the system more resilient to failures, easier to scale, and simpler to update individual parts without affecting the whole. This aligns with microservices architecture. Option A describes monolithic, C is also monolithic, and D is CloudTrail's function.
</details>

---

### Question 6

One of the most important AWS best-practices to follow is the cloud architecture principle of elasticity. How does this principle improve your architecture’s design?

&nbsp;&nbsp;&nbsp;&nbsp;A. By automatically scaling your on-premises resources based on changes in demand.
&nbsp;&nbsp;&nbsp;&nbsp;B. By automatically scaling your AWS resources using an Elastic Load Balancer.
&nbsp;&nbsp;&nbsp;&nbsp;C. By reducing interdependencies between application components wherever possible.
&nbsp;&nbsp;&nbsp;&nbsp;D. By automatically provisioning the required AWS resources based on changes in demand.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** Elasticity allows resources to be provisioned and released automatically based on demand, optimizing costs and performance. Services like Auto Scaling and ELB enable this, but the principle is the automatic provisioning. Option A is not AWS, B is specific to ELB, C is decoupling.
</details>

---

### Question 7

Which of the following does NOT belong to the AWS Cloud Computing models?

&nbsp;&nbsp;&nbsp;&nbsp;A. Platform as a Service (PaaS).
&nbsp;&nbsp;&nbsp;&nbsp;B. Infrastructure as a Service (IaaS).
&nbsp;&nbsp;&nbsp;&nbsp;C. Software as a Service (SaaS).
&nbsp;&nbsp;&nbsp;&nbsp;D. Networking as a Service (NaaS).

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** AWS supports IaaS (e.g., EC2), PaaS (e.g., Elastic Beanstalk), and SaaS (e.g., WorkSpaces). NaaS is not a standard AWS model; networking is part of IaaS.
</details>

---

### Question 8

A global company with a large number of AWS accounts is seeking a way in which they can centrally manage billing and security policies across all accounts. Which AWS Service will assist them in meeting these goals?

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Organizations.
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Trusted Advisor.
&nbsp;&nbsp;&nbsp;&nbsp;C. IAM User Groups.
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Config.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** AWS Organizations allows central management of multiple accounts, including consolidated billing and service control policies for security. Trusted Advisor is for optimization, IAM Groups are for user permissions within an account, AWS Config is for resource configuration.
</details>

---

### Question 9

Which of the below is a best-practice when building applications on AWS?

&nbsp;&nbsp;&nbsp;&nbsp;A. Invest heavily in architecting your environment, as it is not easy to change your design later.
&nbsp;&nbsp;&nbsp;&nbsp;B. Use AWS reservations to reduce costs when testing your production environment.
&nbsp;&nbsp;&nbsp;&nbsp;C. Automate wherever possible to make architectural experimentation easier.
&nbsp;&nbsp;&nbsp;&nbsp;D. Provision a large compute capacity to handle any spikes in load

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Automation using tools like CloudFormation makes it easier to experiment, test, and iterate on architectures, aligning with AWS best practices for agility. Option A is contrary to cloud flexibility, B is for cost, D is overprovisioning, which is inefficient.
</details>

---

### Question 10

The principle “design for failure and nothing will fail” is very important when designing your AWS Cloud architecture. Which of the following would help adhere to this principle? (Choose TWO)

&nbsp;&nbsp;&nbsp;&nbsp;A. Multi-factor authentication.
&nbsp;&nbsp;&nbsp;&nbsp;B. Availability Zones.
&nbsp;&nbsp;&nbsp;&nbsp;C. Elastic Load Balancing.
&nbsp;&nbsp;&nbsp;&nbsp;D. Penetration testing.
&nbsp;&nbsp;&nbsp;&nbsp;E. Vertical Scaling.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B, C
> **Explanation:** Designing for failure means building redundancy and fault tolerance. Availability Zones provide isolated locations for high availability, and Elastic Load Balancing distributes traffic across multiple instances. MFA is security, penetration testing is assessment, vertical scaling creates single points of failure.
</details>

---

### Question 11

Which of the following is equivalent to a user name and password and is used to authenticate your programmatic access to AWS services and APIs?

&nbsp;&nbsp;&nbsp;&nbsp;A. Instance Password.
&nbsp;&nbsp;&nbsp;&nbsp;B. Key pairs.
&nbsp;&nbsp;&nbsp;&nbsp;C. Access Keys.
&nbsp;&nbsp;&nbsp;&nbsp;D. MFA.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Access Keys (Access Key ID and Secret Access Key) are used for programmatic access via AWS CLI, SDKs, and APIs, similar to username/password for console access. Key pairs are for EC2 SSH/RDP, Instance Password for Windows, MFA is additional security.
</details>

---

### Question 12

Which of the following AWS services scale automatically without your intervention? (Choose TWO)

&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon EC2.
&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon S3.
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Lambda.
&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon EMR.
&nbsp;&nbsp;&nbsp;&nbsp;E. Amazon EBS.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B, C
> **Explanation:** Amazon S3 automatically scales storage and throughput, AWS Lambda automatically scales compute based on invocation rate. EC2 requires Auto Scaling configuration, EMR is managed Hadoop, EBS scales manually or via snapshots.
</details>

---

### Question 13

Which of the following is one of the benefits of moving infrastructure from an on-premises data center to AWS?

&nbsp;&nbsp;&nbsp;&nbsp;A. Free support for all enterprise customers.
&nbsp;&nbsp;&nbsp;&nbsp;B. Automatic data protection.
&nbsp;&nbsp;&nbsp;&nbsp;C. Reduced Capital Expenditure (CapEx).
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS holds responsibility for managing customer applications.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Moving to AWS shifts from CapEx (buying hardware) to OpEx (pay-as-you-go), eliminating upfront infrastructure costs. Support is paid, data protection is customer responsibility, AWS doesn't manage customer applications.
</details>

---

### Question 14

Which of the following are important design principles you should adopt when designing systems on AWS? (Choose TWO)

&nbsp;&nbsp;&nbsp;&nbsp;A. Always use Global Services in your architecture rather than Regional Services.
&nbsp;&nbsp;&nbsp;&nbsp;B. Always choose to pay as you go.
&nbsp;&nbsp;&nbsp;&nbsp;C. Treat servers as fixed resources.
&nbsp;&nbsp;&nbsp;&nbsp;D. Automate wherever possible.
&nbsp;&nbsp;&nbsp;&nbsp;E. Remove single points of failure.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D, E
> **Explanation:** Automation enables rapid deployment and consistency (Well-Architected), removing single points of failure ensures reliability. Global vs Regional depends on use case, pay-as-you-go is pricing, treating servers as fixed contradicts elasticity.
</details>

---

### Question 15

Which of the following are advantages of the AWS Cloud? (Choose TWO)

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS manages capacity planning for physical servers.
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS manages the security of applications built on AWS.
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS manages the development of applications on AWS.
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS manages cost planning for virtual servers.
&nbsp;&nbsp;&nbsp;&nbsp;E. AWS manages the maintenance of the cloud infrastructure.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A, E
> **Explanation:** Under shared responsibility, AWS manages physical capacity planning and infrastructure maintenance. Customers manage application security and development, cost planning is customer responsibility.
</details>

---

### Question 16

Which of the following statements describes the AWS Cloud’s agility?

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS provides a low-cost virtual network infrastructure for your workloads.
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS allows you to host your applications in multiple regions around the world.
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS allows you to pay for what you use with no long-term commitments.
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS allows you to provision capacity on the fly.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** Agility is the ability to rapidly provision and de-provision resources as needed. Low-cost networking is economy of scale, multi-region is global reach, pay-as-you-go is economic model.
</details>

---

### Question 17

Which of the following does AWS provide to help reduce the complexity of managing multiple AWS accounts?

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Trusted Advisor.
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Management Console.
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Organizations.
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS IAM.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** AWS Organizations centralizes management of multiple accounts with consolidated billing and policies. Trusted Advisor is optimization, Console is UI, IAM is within-account permissions.
</details>

---

### Question 18

Which of the following does the AWS Cloud provide to its customers? (Choose TWO)

&nbsp;&nbsp;&nbsp;&nbsp;A. Physical networking.
&nbsp;&nbsp;&nbsp;&nbsp;B. Secure data centers.
&nbsp;&nbsp;&nbsp;&nbsp;C. Software firewalls.
&nbsp;&nbsp;&nbsp;&nbsp;D. Multiple storage options.
&nbsp;&nbsp;&nbsp;&nbsp;E. Virtual storage.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B, D
> **Explanation:** AWS provides secure physical data centers and multiple storage options (S3, EBS, Glacier). Physical networking is abstracted, software firewalls and virtual storage are customer-managed.
</details>

---

### Question 19

What are the benefits of using the AWS Cloud Adoption Framework (AWS CAF)?

&nbsp;&nbsp;&nbsp;&nbsp;A. Helps you understand how to use AWS to improve your business.
&nbsp;&nbsp;&nbsp;&nbsp;B. Provides structured guidance to help customers build a cloud infrastructure.
&nbsp;&nbsp;&nbsp;&nbsp;C. Provides a structured approach to help customers develop an agile methodology to move to the AWS Cloud.
&nbsp;&nbsp;&nbsp;&nbsp;D. Provides a structured framework for large enterprises to achieve better business outcomes.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** AWS CAF provides structured guidance for building and migrating to cloud infrastructure across business, people, governance, and technical perspectives. Option D is partially correct but B is more precise.
</details>

---

### Question 20

Which of the below is a best-practice when building applications on AWS?

&nbsp;&nbsp;&nbsp;&nbsp;A. Strengthen physical security by applying the principle of least privilege to all AWS resources.
&nbsp;&nbsp;&nbsp;&nbsp;B. Ensure that the application runs on hardware from trusted vendors.
&nbsp;&nbsp;&nbsp;&nbsp;C. Use IAM policies to maintain performance.
&nbsp;&nbsp;&nbsp;&nbsp;D. Decouple the components of the application so that they run independently.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** Decoupling components is a best practice for building resilient and scalable applications on AWS, as it reduces dependencies and allows for independent scaling and failure isolation.
</details>

---

### Question 21

Using Amazon EC2 falls under which of the following cloud computing models?

&nbsp;&nbsp;&nbsp;&nbsp;A. Iaas & SaaS.
&nbsp;&nbsp;&nbsp;&nbsp;B. IaaS.
&nbsp;&nbsp;&nbsp;&nbsp;C. SaaS.
&nbsp;&nbsp;&nbsp;&nbsp;D. PaaS.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Amazon EC2 is an IaaS service, providing virtual servers where customers manage the OS and applications.
</details>

---

### Question 22

Your company is designing a new application that will store and retrieve photos and videos. Which of the following services should you recommend as the underlying storage mechanism?

&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon EBS.
&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon SQS.
&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon Instance Store.
&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon S3.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** Amazon S3 is designed for storing objects like photos and videos, offering high durability, availability, and infinite scalability.
</details>

---

### Question 23

What does Amazon Elastic Beanstalk provide?

&nbsp;&nbsp;&nbsp;&nbsp;A. A PaaS solution to automate application deployment.
&nbsp;&nbsp;&nbsp;&nbsp;B. A compute engine for Amazon ECS.
&nbsp;&nbsp;&nbsp;&nbsp;C. A scalable file storage solution for use with AWS and on-premises servers.
&nbsp;&nbsp;&nbsp;&nbsp;D. A NoSQL database service.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Amazon Elastic Beanstalk is a PaaS service that handles the deployment, scaling, and load balancing of applications, allowing developers to focus on code.
</details>

---

### Question 24

Your application has recently experienced significant global growth, and international users are complaining of high latency. What is the AWS characteristic that can help improve your international users’ experience?

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS allows customers to launch powerful EC2 instances to handle spikes in load.
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS allows customers to pay upfront to get bigger discounts.
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS allows customers to launch and terminate EC2 instances based on demand.
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS allows customers to choose cheaper types of EC2 instances that best fit their needs.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Global reach allows deploying resources in regions closer to users to reduce latency.
</details>

---

### Question 25

Which statement best describes the operational excellence pillar of the AWS Well-Architected Framework?

&nbsp;&nbsp;&nbsp;&nbsp;A. The ability of a system to recover gracefully from failure.
&nbsp;&nbsp;&nbsp;&nbsp;B. The efficient use of computing resources to meet requirements.
&nbsp;&nbsp;&nbsp;&nbsp;C. The ability to monitor systems and improve supporting processes and procedures.
&nbsp;&nbsp;&nbsp;&nbsp;D. The ability to manage datacenter operations more efficiently.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** The operational excellence pillar focuses on running and monitoring systems to deliver business value and continually improve processes and procedures.
</details>

---

### Question 26

Which of the following is true regarding the AWS availability zones and edge locations?

&nbsp;&nbsp;&nbsp;&nbsp;A. Edge locations are located in separate Availability Zones worldwide to serve global customers.
&nbsp;&nbsp;&nbsp;&nbsp;B. An availability zone exists within an edge location to distribute content globally with low latency.
&nbsp;&nbsp;&nbsp;&nbsp;C. An Availability Zone is a geographic location where AWS provides multiple, physically separated and isolated edge locations.
&nbsp;&nbsp;&nbsp;&nbsp;D. An AWS Availability Zone is an isolated location within an AWS Region, however edge locations are located in multiple cities worldwide.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** Availability Zones are isolated locations within a Region, while edge locations are points of presence for caching content globally.
</details>

---

### Question 27

Which of the following are advantages of using AWS as a cloud computing provider? (Choose TWO)

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS eliminates the need to monitor servers and applications.
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS manages all the compliance and auditing tasks.
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS provides custom hardware to meet any specification.
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS eliminates the need to guess on infrastructure capacity needs.
&nbsp;&nbsp;&nbsp;&nbsp;E. AWS enables customers to trade their capital expenses for operational expenses.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D, E
> **Explanation:** AWS allows for on-demand provisioning, eliminating capacity guessing, and shifts from CapEx to OpEx.
</details>

---

### Question 28

Which of the following is a cloud computing deployment model that connects infrastructure and applications between cloud-based resources and existing resources not located in the cloud?

&nbsp;&nbsp;&nbsp;&nbsp;A. On-premises.
&nbsp;&nbsp;&nbsp;&nbsp;B. Mixed.
&nbsp;&nbsp;&nbsp;&nbsp;C. Hybrid.
&nbsp;&nbsp;&nbsp;&nbsp;D. Cloud.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Hybrid cloud combines cloud and on-premises resources.
</details>

---

### Question 29

You want to create a backup of your data in another geographical location. Where should you create this backup?

&nbsp;&nbsp;&nbsp;&nbsp;A. In another Edge location.
&nbsp;&nbsp;&nbsp;&nbsp;B. In another Region.
&nbsp;&nbsp;&nbsp;&nbsp;C. In another VPC.
&nbsp;&nbsp;&nbsp;&nbsp;D. In another Availability Zone.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Regions are geographically isolated, providing data replication for disaster recovery.
</details>

---

### Question 30

What does the term “Economies of scale” mean?

&nbsp;&nbsp;&nbsp;&nbsp;A. It means that you save more when you consume more.
&nbsp;&nbsp;&nbsp;&nbsp;B. As more time passes using AWS, you pay more for its services.
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS will continuously lower costs as it grows.
&nbsp;&nbsp;&nbsp;&nbsp;D. It means that you have the ability to pay as you go.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** AWS passes on savings from large-scale operations to customers through price reductions.
</details>

---

### Question 31

Which statement best describes the AWS Pay-As-You-Go pricing model?

&nbsp;&nbsp;&nbsp;&nbsp;A. With AWS, you replace low upfront expenses with large variable payments.
&nbsp;&nbsp;&nbsp;&nbsp;B. With AWS, you replace low upfront expenses with large fixed payments.
&nbsp;&nbsp;&nbsp;&nbsp;C. With AWS, you replace large upfront expenses with low fixed payments.
&nbsp;&nbsp;&nbsp;&nbsp;D. With AWS, you replace large capital expenses with low variable payments.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** Pay-as-you-go allows paying only for used resources, replacing CapEx with OpEx.
</details>

---

### Question 32

Why are Serverless Architectures more economical than Server-based Architectures?

&nbsp;&nbsp;&nbsp;&nbsp;A. Serverless Architectures use new powerful computing devices.
&nbsp;&nbsp;&nbsp;&nbsp;B. With the Server-based Architectures, compute resources continue to run all the time but with serverless architecture, compute resources are only used when code is being executed.
&nbsp;&nbsp;&nbsp;&nbsp;C. When you reserve serverless capacity, you will get large discounts compared to server reservation.
&nbsp;&nbsp;&nbsp;&nbsp;D. With Serverless Architectures you have the ability to scale automatically up or down as demand changes.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Serverless runs code only when needed, charging only for execution time, unlike servers that run continuously.
</details>

---

### Question 33

The owner of an E-Commerce application notices that the compute capacity requirements vary heavily from time to time. What makes AWS more economical than traditional data centers for this type of application?

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS allows customers to launch powerful EC2 instances to handle spikes in load.
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS allows customers to pay upfront to get bigger discounts.
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS allows customers to launch and terminate EC2 instances based on demand.
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS allows customers to choose cheaper types of EC2 instances that best fit their needs.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** AWS enables scaling by launching/terminating instances based on demand, paying only for used resources.
</details>

---

### Question 34

Which principles are used to architect applications for reliability on the AWS Cloud? (Choose TWO)

&nbsp;&nbsp;&nbsp;&nbsp;A. Design for automated failure recovery.
&nbsp;&nbsp;&nbsp;&nbsp;B. Use multiple Availability Zones.
&nbsp;&nbsp;&nbsp;&nbsp;C. Manage changes via documented processes.
&nbsp;&nbsp;&nbsp;&nbsp;D. Test for moderate demand to ensure reliability.
&nbsp;&nbsp;&nbsp;&nbsp;E. Backup recovery to an on-premises environment.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A, B
> **Explanation:** Reliability involves automatic recovery and using AZs for fault tolerance.
</details>

---

### Question 35

Which of the following main components of the AWS global infrastructure consists of one or more discrete data centers interconnected through low latency links?

&nbsp;&nbsp;&nbsp;&nbsp;A. Availability Zone.
&nbsp;&nbsp;&nbsp;&nbsp;B. Edge location.
&nbsp;&nbsp;&nbsp;&nbsp;C. Region.
&nbsp;&nbsp;&nbsp;&nbsp;D. Private networking.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Availability Zones are multiple isolated data centers within a Region, connected by low-latency links.
</details>

---

### Question 36

What is a value proposition of the AWS Cloud?

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS is responsible for security in the AWS Cloud.
&nbsp;&nbsp;&nbsp;&nbsp;B. No long-term contract is required.
&nbsp;&nbsp;&nbsp;&nbsp;C. Provision new servers in days.
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS manages user applications in the AWS Cloud.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** AWS offers flexible pricing without long-term commitments.
</details>

---

### Question 37

Which of the following is a cloud architectural design principle?

&nbsp;&nbsp;&nbsp;&nbsp;A. Scale up not out.
&nbsp;&nbsp;&nbsp;&nbsp;B. Loosely couple components.
&nbsp;&nbsp;&nbsp;&nbsp;C. Build monolithic systems.
&nbsp;&nbsp;&nbsp;&nbsp;D. Use commercial database software.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Loose coupling reduces dependencies between components for better fault isolation.
</details>

---

### Question 38

Which AWS service enables users to deploy infrastructure as code by automating the process of provisioning resources?

&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon GameLift.
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS CloudFormation.
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Data Pipeline.
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Glue.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** AWS CloudFormation allows modeling and provisioning resources using templates.
</details>

---

### Question 39

Which of the following allows users to provision a dedicated network connection from their internal network to AWS?

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS CloudHSM.
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Direct Connect.
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS VPN.
&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon Connect.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** AWS Direct Connect provides a dedicated private connection from on-premises to AWS.
</details>

---

### Question 40

Which service would provide network connectivity in a hybrid architecture that includes the AWS Cloud?

&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon VPC.
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Direct Connect.
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Directory Service.
&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon API Gateway.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Amazon VPC allows extending on-premises networks to the cloud for hybrid setups.
</details>

---

### Question 41

Which tool can be used to compare the costs of running a web application in a traditional hosting environment to running it on AWS?

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Cost Explorer.
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Budgets.
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Cost and Usage report.
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Total Cost of Ownership (TCO) Calculator.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** The TCO Calculator estimates cost savings when moving to AWS from on-premises.
</details>

---

### Question 42

What is the benefit of elasticity in the AWS Cloud?

&nbsp;&nbsp;&nbsp;&nbsp;A. Ensure web traffic is automatically spread across multiple AWS Regions.
&nbsp;&nbsp;&nbsp;&nbsp;B. Minimize storage costs by automatically archiving log data.
&nbsp;&nbsp;&nbsp;&nbsp;C. Enable AWS to automatically select the most cost-effective services.
&nbsp;&nbsp;&nbsp;&nbsp;D. Automatically adjust the required compute capacity to maintain consistent performance.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** Elasticity allows automatic adjustment of resources to match demand, maintaining performance.
</details>

---

### Question 43

Which of the following are benefits of hosting infrastructure in the AWS Cloud? (Choose TWO)

&nbsp;&nbsp;&nbsp;&nbsp;A. There are no upfront commitments.
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS manages all security in the cloud.
&nbsp;&nbsp;&nbsp;&nbsp;C. Users have the ability to provision resources on demand.
&nbsp;&nbsp;&nbsp;&nbsp;D. Users have access to free and unlimited storage.
&nbsp;&nbsp;&nbsp;&nbsp;E. Users have control over the physical infrastructure.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A, C
> **Explanation:** AWS has no upfront commitments and allows on-demand provisioning.
</details>

---

### Question 44

Which AWS Cloud best practice uses the elasticity and agility of cloud computing?

&nbsp;&nbsp;&nbsp;&nbsp;A. Provision capacity based on past usage and theoretical peaks.
&nbsp;&nbsp;&nbsp;&nbsp;B. Dynamically and predictively scale to meet usage demands.
&nbsp;&nbsp;&nbsp;&nbsp;C. Build the application and infrastructure in a data center that grants physical access.
&nbsp;&nbsp;&nbsp;&nbsp;D. Break apart the application into loosely coupled components.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Predictive scaling uses elasticity to adjust resources based on demand.
</details>

---

### Question 45

Which method helps to optimize costs of users moving to the AWS Cloud?

&nbsp;&nbsp;&nbsp;&nbsp;A. Paying only for what is used.
&nbsp;&nbsp;&nbsp;&nbsp;B. Purchasing hardware before it is needed.
&nbsp;&nbsp;&nbsp;&nbsp;C. Manually provisioning cloud resources.
&nbsp;&nbsp;&nbsp;&nbsp;D. Purchasing for the maximum possible load.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Pay-as-you-go optimizes costs by charging only for used resources.
</details>

---

### Question 46

What is one of the core principles to follow when designing a highly available application in the AWS Cloud?

&nbsp;&nbsp;&nbsp;&nbsp;A. Design using a serverless architecture.
&nbsp;&nbsp;&nbsp;&nbsp;B. Assume that all components within an application can fail.
&nbsp;&nbsp;&nbsp;&nbsp;C. Design AWS Auto Scaling into every application.
&nbsp;&nbsp;&nbsp;&nbsp;D. Design all components using open-source code.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Designing for failure assumes components can fail, building in redundancy.
</details>

---

### Question 47

Which of the AWS global infrastructure is used to cache copies of content for faster delivery to users across the globe?

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Regions.
&nbsp;&nbsp;&nbsp;&nbsp;B. Availability Zones.
&nbsp;&nbsp;&nbsp;&nbsp;C. Edge locations.
&nbsp;&nbsp;&nbsp;&nbsp;D. Data centers.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Edge locations cache content for low-latency delivery via CloudFront.
</details>

---

### Question 48

A Cloud Practitioner is developing a disaster recovery plan and intends to replicate data between multiple geographic areas.

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Accounts.
&nbsp;&nbsp;&nbsp;&nbsp;B. A. AWS Regions.
&nbsp;&nbsp;&nbsp;&nbsp;C. Availability Zones.
&nbsp;&nbsp;&nbsp;&nbsp;D. Edge locations.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Replicating across Regions provides geographic separation for disaster recovery.
</details>

---

### Question 49

The AWS Total Cost of Ownership (TCO) Calculator is used to:

&nbsp;&nbsp;&nbsp;&nbsp;A. receive reports that break down AWS Cloud compute costs by duration, resource, or tags.
&nbsp;&nbsp;&nbsp;&nbsp;B. estimate savings when comparing the AWS Cloud to an on-premises environment.
&nbsp;&nbsp;&nbsp;&nbsp;C. estimate a monthly bill for the AWS Cloud resources that will be used.
&nbsp;&nbsp;&nbsp;&nbsp;D. enable billing alerts to monitor actual AWS costs compared to estimated costs.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** The TCO Calculator estimates savings from migrating to AWS.
</details>

---

### Question 50

A company has distributed its workload on both the AWS Cloud and some on-premises servers. What type of architecture is this?

&nbsp;&nbsp;&nbsp;&nbsp;A. Virtual private network.
&nbsp;&nbsp;&nbsp;&nbsp;B. Virtual private cloud.
&nbsp;&nbsp;&nbsp;&nbsp;C. Hybrid cloud.
&nbsp;&nbsp;&nbsp;&nbsp;D. Private cloud.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Hybrid cloud combines cloud and on-premises infrastructures.
</details>

---

### Question 51

A company has an application with users in both Australia and Brazil. All the company infrastructure is currently provisioned in the Asia Pacific (Sydney) Region in Australia, and Brazilian users are experiencing high latency. What should the company do to reduce latency?

&nbsp;&nbsp;&nbsp;&nbsp;A. Implement AWS Direct Connect for users in Brazil.
&nbsp;&nbsp;&nbsp;&nbsp;B. Provision resources in the South America (São Paulo) Region in Brazil.
&nbsp;&nbsp;&nbsp;&nbsp;C. Use AWS Transit Gateway to quickly route users from Brazil to the application.
&nbsp;&nbsp;&nbsp;&nbsp;D. Launch additional Amazon EC2 instances in Sydney to handle the demand.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Provisioning in a closer Region reduces latency for users in that area.
</details>

---

### Question 52

An Amazon EC2 instance runs only when needed yet must remain active for the duration of the process. Which Amazon EC2 purchasing option will meet these requirements?

&nbsp;&nbsp;&nbsp;&nbsp;A. Dedicated Instances.
&nbsp;&nbsp;&nbsp;&nbsp;B. Spot Instances.
&nbsp;&nbsp;&nbsp;&nbsp;C. On-Demand Instances.
&nbsp;&nbsp;&nbsp;&nbsp;D. Reserved Instances.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** On-Demand Instances are suitable for short-term, uninterrupted workloads.
</details>

---

### Question 53

What is an Availability Zone in AWS?

&nbsp;&nbsp;&nbsp;&nbsp;A. One or more physical data centers.
&nbsp;&nbsp;&nbsp;&nbsp;B. A completely isolated geographic location.
&nbsp;&nbsp;&nbsp;&nbsp;C. A data center location with a single source of power and networking.
&nbsp;&nbsp;&nbsp;&nbsp;D. One or more edge locations based around the world.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Availability Zones consist of one or more discrete data centers with redundant power and networking.
</details>

---

### Question 54

Which AWS services can be used to gather information about AWS account activity? (Select TWO.)

&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon CloudFront.
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Cloud9.
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS CloudTrail.
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS CloudHSM.
&nbsp;&nbsp;&nbsp;&nbsp;E. Amazon CloudWatch.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C, E
> **Explanation:** CloudTrail logs API activity, CloudWatch monitors metrics and logs for account activity.
</details>

---

### Question 55

Which of the following common IT tasks can AWS cover to free up company IT resources? (Select TWO.)

&nbsp;&nbsp;&nbsp;&nbsp;A. Patching databases software.
&nbsp;&nbsp;&nbsp;&nbsp;B. Testing application releases.
&nbsp;&nbsp;&nbsp;&nbsp;C. Backing up databases.
&nbsp;&nbsp;&nbsp;&nbsp;D. Creating database schema.
&nbsp;&nbsp;&nbsp;&nbsp;E. Running penetration tests.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A, C
> **Explanation:** AWS managed services like RDS handle patching and backups.
</details>

---

### Question 56

In which scenario should Amazon EC2 Spot Instances be used?

&nbsp;&nbsp;&nbsp;&nbsp;A. A company wants to move its main website to AWS from an on-premises web server.
&nbsp;&nbsp;&nbsp;&nbsp;B. A company has a number of application services whose Service Level Agreement (SLA) requires 99.999% uptime.
&nbsp;&nbsp;&nbsp;&nbsp;C. A company's heavily used legacy database is currently running on-premises.
&nbsp;&nbsp;&nbsp;&nbsp;D. A company has a number of infrequent, interruptible jobs that are currently using On-Demand Instances.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** Spot Instances are ideal for interruptible, flexible workloads.
</details>

---

### Question 57

Which AWS feature should a customer leverage to achieve high availability of an application?

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Direct Connect.
&nbsp;&nbsp;&nbsp;&nbsp;B. Availability Zones.
&nbsp;&nbsp;&nbsp;&nbsp;C. Data centers.
&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon Virtual Private Cloud (Amazon VPC).

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Availability Zones provide fault isolation for high availability.
</details>

---

### Question 58

What can AWS edge locations be used for? (Select TWO.)

&nbsp;&nbsp;&nbsp;&nbsp;A. Hosting applications.
&nbsp;&nbsp;&nbsp;&nbsp;B. Delivering content closer to users.
&nbsp;&nbsp;&nbsp;&nbsp;C. Running NoSQL database caching services.
&nbsp;&nbsp;&nbsp;&nbsp;D. Reducing traffic on the server by caching responses.
&nbsp;&nbsp;&nbsp;&nbsp;E. Sending notification messages to end users.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B, D
> **Explanation:** Edge locations cache content and deliver it closer to users for low latency.
</details>

---

### Question 59

Which services use AWS edge locations? (Choose TWO.)

&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon CloudFront.
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Shield.
&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon EC2.
&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon RDS.
&nbsp;&nbsp;&nbsp;&nbsp;E. Amazon ElastiCache.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A, B
> **Explanation:** CloudFront and Shield use edge locations for content delivery and DDoS protection.
</details>

---

### Question 60

Which of the following AWS services can be used to manually launch instances based on resource requirements?

&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon EBS.
&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon S3.
&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon EC2.
&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon ECS.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Amazon EC2 allows manual launching of instances based on needs.
</details>

---

### Question 61

Which AWS Cloud benefit eliminates the need for users to try estimating future infrastructure usage?

&nbsp;&nbsp;&nbsp;&nbsp;A. Easy and fast deployment of applications in multiple Regions around the world.
&nbsp;&nbsp;&nbsp;&nbsp;B. Security of the AWS Cloud.
&nbsp;&nbsp;&nbsp;&nbsp;C. Elasticity of the AWS Cloud.
&nbsp;&nbsp;&nbsp;&nbsp;D. Lower variable costs due to massive economies of scale.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Elasticity allows scaling without estimating future needs.
</details>

---

### Question 62

Compared with costs in traditional and virtualized data centers, AWS has:

&nbsp;&nbsp;&nbsp;&nbsp;A. Greater variable costs and greater upfront costs.
&nbsp;&nbsp;&nbsp;&nbsp;B. Fixed usage costs and lower upfront costs.
&nbsp;&nbsp;&nbsp;&nbsp;C. Lower variable costs and greater upfront costs.
&nbsp;&nbsp;&nbsp;&nbsp;D. Lower variable costs and lower upfront costs.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** AWS reduces both variable and upfront costs through pay-as-you-go.
</details>

---

### Question 63

A characteristic of edge locations is that they:

&nbsp;&nbsp;&nbsp;&nbsp;A. Host Amazon EC2 instances closer to users.
&nbsp;&nbsp;&nbsp;&nbsp;B. Help lower latency and improve performance for users.
&nbsp;&nbsp;&nbsp;&nbsp;C. Cache frequently changing data without reaching the origin server.
&nbsp;&nbsp;&nbsp;&nbsp;D. Refresh data changes daily.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Edge locations improve performance by reducing latency for users.
</details>

---

### Question 64

Which AWS feature will reduce the customer’s total cost of ownership (TCO)?

&nbsp;&nbsp;&nbsp;&nbsp;A. Shared responsibility security model.
&nbsp;&nbsp;&nbsp;&nbsp;B. Single tenancy.
&nbsp;&nbsp;&nbsp;&nbsp;C. Elastic computing.
&nbsp;&nbsp;&nbsp;&nbsp;D. Encryption.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Elastic computing allows paying only for used resources, reducing TCO.
</details>

---

### Question 65

Which of the following is a benefit of using the AWS Cloud?

&nbsp;&nbsp;&nbsp;&nbsp;A. Permissive security removes the administrative burden.
&nbsp;&nbsp;&nbsp;&nbsp;B. Ability to focus on revenue-generating activities.
&nbsp;&nbsp;&nbsp;&nbsp;C. Control over cloud network hardware.
&nbsp;&nbsp;&nbsp;&nbsp;D. Choice of specific cloud hardware vendors.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** AWS handles infrastructure, allowing focus on business.
</details>

---

### Question 66

What is an AWS Cloud design best practice?

&nbsp;&nbsp;&nbsp;&nbsp;A. Tight coupling of components.
&nbsp;&nbsp;&nbsp;&nbsp;B. Single point of failure.
&nbsp;&nbsp;&nbsp;&nbsp;C. High availability.
&nbsp;&nbsp;&nbsp;&nbsp;D. Overprovisioning of resources.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** High availability is a key best practice for cloud designs.
</details>

---

### Question 67

Why is AWS more economical than traditional data centers for applications with varying compute workloads?

&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon Elastic Compute Cloud (Amazon EC2) costs are billed on a monthly basis.
&nbsp;&nbsp;&nbsp;&nbsp;B. Customers retain full administrative access to their Amazon EC2 instances.
&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon EC2 instances can be launched on-demand when needed.
&nbsp;&nbsp;&nbsp;&nbsp;D. Customers can permanently run enough instances to handle peak workloads.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** On-demand instances allow scaling without overprovisioning.
</details>

---

### Question 68

Which AWS service or resource is serverless?

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Lambda.
&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon EC2 instances.
&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon Lightsail.
&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon ElastiCache.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** AWS Lambda is serverless, running code without managing servers.
</details>

---

### Question 69

Which of the following are advantages of the AWS Cloud? (Choose TWO)

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS manages the maintenance of the cloud infrastructure.
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS manages the security of applications built on AWS.
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS manages capacity planning for physical servers.
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS manages the development of applications on AWS.
&nbsp;&nbsp;&nbsp;&nbsp;E. AWS manages cost planning for virtual servers.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A, C
> **Explanation:** AWS handles infrastructure maintenance and capacity planning.
</details>

---

### Question 70

A user must meet compliance and software licensing requirements that state a workload must be hosted on a physical server. Which Amazon EC2 instance pricing option will meet these requirements?

&nbsp;&nbsp;&nbsp;&nbsp;A. Dedicated Hosts.
&nbsp;&nbsp;&nbsp;&nbsp;B. Dedicated Instances.
&nbsp;&nbsp;&nbsp;&nbsp;C. Spot Instances.
&nbsp;&nbsp;&nbsp;&nbsp;D. Reserved Instances.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Dedicated Hosts provide physical servers for compliance and licensing.
</details>

---

### Question 71

A company is planning to migrate from on-premises to the AWS Cloud. Which AWS tool or service provides detailed reports on estimated cost savings after migration?

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Total Cost of Ownership (TCO) Calculator.
&nbsp;&nbsp;&nbsp;&nbsp;B. Cost Explorer.
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Budgets.
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Migration Hub.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** The TCO Calculator provides reports on potential savings.
</details>

---

### Question 72

What can assist in evaluating an application for migration to the cloud? (Choose TWO)

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Trusted Advisor.
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Professional Services.
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Systems Manager.
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Partner Network (APN).
&nbsp;&nbsp;&nbsp;&nbsp;E. AWS Secrets Manager.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B, D
> **Explanation:** AWS Professional Services and APN partners assist with migration evaluations.
</details>

---

### Question 73

Which AWS service is suitable for an event-driven workload?

&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon EC2.
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Elastic Beanstalk.
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Lambda.
&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon Lumberyard.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** AWS Lambda is designed for event-driven, serverless workloads.
</details>

---

### Question 74

Which of the following is an example of how moving to the AWS Cloud reduces upfront cost?

&nbsp;&nbsp;&nbsp;&nbsp;A. By replacing large variable costs with lower capital investments.
&nbsp;&nbsp;&nbsp;&nbsp;B. By replacing large capital investments with lower variable costs.
&nbsp;&nbsp;&nbsp;&nbsp;C. By allowing the provisioning of compute and storage at a fixed level to meet peak demand.
&nbsp;&nbsp;&nbsp;&nbsp;D. By replacing the repeated scaling of virtual servers with a simpler fixed-scale model.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** AWS shifts from CapEx to variable OpEx.
</details>

---

### Question 75

When designing a typical three-tier web application, which AWS services and/or features improve availability and reduce the impact failures? (Choose TWO)

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Auto Scaling for Amazon EC2 instances.
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS VPC subnet ACLs to check the health of a service.
&nbsp;&nbsp;&nbsp;&nbsp;C. Distributed resources across multiple Availability Zones.
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Server Migration Service (AWS SMS) to move Amazon EC2 instances into a different Region.
&nbsp;&nbsp;&nbsp;&nbsp;E. Distributed resources across multiple AWS points of presence.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A, C
> **Explanation:** Auto Scaling and multi-AZ deployments improve availability.
</details>

---

### Question 76

Which cloud design principle aligns with AWS Cloud best practices?

&nbsp;&nbsp;&nbsp;&nbsp;A. Create fixed dependencies among application components.
&nbsp;&nbsp;&nbsp;&nbsp;B. Aggregate services on a single instance.
&nbsp;&nbsp;&nbsp;&nbsp;C. Deploy applications in a single Availability Zone.
&nbsp;&nbsp;&nbsp;&nbsp;D. Distribute the compute load across multiple resources.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** Load distribution enhances performance and fault tolerance.
</details>

---

### Question 77

An application designed to span multiple Availability Zones is described as:

&nbsp;&nbsp;&nbsp;&nbsp;A. being highly available.
&nbsp;&nbsp;&nbsp;&nbsp;B. having global reach.
&nbsp;&nbsp;&nbsp;&nbsp;C. using an economy of scale.
&nbsp;&nbsp;&nbsp;&nbsp;D. having elasticity.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Multi-AZ deployment ensures high availability.
</details>

---

### Question 78

A new service using AWS must be highly available. Yet, due to regulatory requirements, all of its Amazon EC2 instances must be located in a single geographic area. According to best practices, to meet these requirements, the EC2 instances must be placed in at least two:

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Regions.
&nbsp;&nbsp;&nbsp;&nbsp;B. Availability Zones.
&nbsp;&nbsp;&nbsp;&nbsp;C. subnets.
&nbsp;&nbsp;&nbsp;&nbsp;D. placement groups.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Multiple AZs in one Region provide high availability within a geographic area.
</details>

---

### Question 79

Which AWS service or resource is serverless?

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Lambda.
&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon EC2 instances.
&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon Lightsail.
&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon ElastiCache.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** AWS Lambda is serverless.
</details>

---

### Question 80

A user deploys an Amazon RDS DB instance in multiple Availability Zones. This strategy involves which pillar of the AWS Well-Architected Framework?

&nbsp;&nbsp;&nbsp;&nbsp;A. Performance efficiency.
&nbsp;&nbsp;&nbsp;&nbsp;B. Reliability.
&nbsp;&nbsp;&nbsp;&nbsp;C. Cost optimization.
&nbsp;&nbsp;&nbsp;&nbsp;D. Security.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Multi-AZ RDS enhances reliability.
</details>

---

### Question 81

Which element of the AWS global infrastructure consists of one or more discrete data centers, each with redundant power, networking, and connectivity, which are housed in separate facilities?

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Regions.
&nbsp;&nbsp;&nbsp;&nbsp;B. Availability Zones.
&nbsp;&nbsp;&nbsp;&nbsp;C. Edge locations.
&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon CloudFront.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Availability Zones are separate data centers with redundancy.
</details>

---

### Question 82

Which AWS service can be used to automatically scale an application up and down without making capacity planning decisions?

&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon AutoScaling.
&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon Redshift.
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS CloudTrail.
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Lambda.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Amazon Auto Scaling handles automatic scaling.
</details>

---

### Question 83

A company wants to expand from one AWS Region into a second AWS Region. What does the company need to do to start supporting the new Region?

&nbsp;&nbsp;&nbsp;&nbsp;A. Contact an AWS Account Manager to sign a new contract.
&nbsp;&nbsp;&nbsp;&nbsp;B. Move an Availability Zone to the new Region.
&nbsp;&nbsp;&nbsp;&nbsp;C. Begin deploying resources in the second Region.
&nbsp;&nbsp;&nbsp;&nbsp;D. Download the AWS Management Console for the new Region.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Resources can be deployed in any Region without additional contracts.
</details>

---

### Question 84

Which AWS Cloud benefit eliminates the need for users to try estimating future infrastructure usage?

&nbsp;&nbsp;&nbsp;&nbsp;A. Easy and fast deployment of applications in multiple Regions around the world.
&nbsp;&nbsp;&nbsp;&nbsp;B. Security of the AWS Cloud.
&nbsp;&nbsp;&nbsp;&nbsp;C. Elasticity of the AWS Cloud.
&nbsp;&nbsp;&nbsp;&nbsp;D. Lower variable costs due to massive economies of scale.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Elasticity allows on-demand scaling without estimation.
</details>

---

### Question 85

When comparing AWS Cloud with on-premises Total Cost of Ownership, which expenses must be considered?

&nbsp;&nbsp;&nbsp;&nbsp;A. Software development.
&nbsp;&nbsp;&nbsp;&nbsp;B. Project management.
&nbsp;&nbsp;&nbsp;&nbsp;C. Storage hardware.
&nbsp;&nbsp;&nbsp;&nbsp;D. Physical servers.
&nbsp;&nbsp;&nbsp;&nbsp;E. Antivirus software license.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C, D
> **Explanation:** On-premises TCO includes hardware costs, which AWS reduces.
</details>

---

### Question 86

Which scenarios represent the concept of elasticity on AWS? (Choose TWO)

&nbsp;&nbsp;&nbsp;&nbsp;A. Scaling the number of Amazon EC2 instances based on traffic.
&nbsp;&nbsp;&nbsp;&nbsp;B. Resizing Amazon RDS instances as business needs change.
&nbsp;&nbsp;&nbsp;&nbsp;C. Automatically directing traffic to less-utilized Amazon EC2 instances.
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS compliance documents to accelerate the compliance process.
&nbsp;&nbsp;&nbsp;&nbsp;E. Having the ability to create and govern environments using code.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A, B
> **Explanation:** Elasticity involves automatic scaling of EC2 and resizing RDS.
</details>

---

### Question 87

When is it beneficial for a company to use a Spot Instance?

&nbsp;&nbsp;&nbsp;&nbsp;A. When there is flexibility in when an application needs to run.
&nbsp;&nbsp;&nbsp;&nbsp;B. When there are mission-critical workloads.
&nbsp;&nbsp;&nbsp;&nbsp;C. When dedicated capacity is needed.
&nbsp;&nbsp;&nbsp;&nbsp;D. When an instance should not be stopped.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Spot Instances are for flexible, interruptible workloads.
</details>

---

### Question 88

Which design principle should be considered when architecting in the AWS Cloud?

&nbsp;&nbsp;&nbsp;&nbsp;A. Think of servers as non-disposable resources.
&nbsp;&nbsp;&nbsp;&nbsp;B. Use synchronous integration of services.
&nbsp;&nbsp;&nbsp;&nbsp;C. Loose coupling.
&nbsp;&nbsp;&nbsp;&nbsp;D. Implement the least permissive rules for security groups.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Loose coupling is a key design principle for resilience.
</details>

---

### Question 89

The continual reduction of AWS Cloud pricing is due to:

&nbsp;&nbsp;&nbsp;&nbsp;A. Pay-as-you-go pricing.
&nbsp;&nbsp;&nbsp;&nbsp;B. The AWS global infrastructure.
&nbsp;&nbsp;&nbsp;&nbsp;C. Economies of scale.
&nbsp;&nbsp;&nbsp;&nbsp;D. Reserved storage pricing.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Economies of scale allow AWS to lower prices as it grows.
</details>

---

### Question 90

Which AWS Cloud best practice uses the elasticity and agility of cloud computing?

&nbsp;&nbsp;&nbsp;&nbsp;A. Provision capacity based on past usage and theoretical peaks.
&nbsp;&nbsp;&nbsp;&nbsp;B. Dynamically and predictively scale to meet usage demands.
&nbsp;&nbsp;&nbsp;&nbsp;C. Build the application and infrastructure in a data center that grants physical access.
&nbsp;&nbsp;&nbsp;&nbsp;D. Break apart the application into loosely coupled components.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Predictive scaling uses elasticity.
</details>

---

### Question 91

Performing operations as code is a design principle that supports which pillar of the AWS Well-Architected Framework?

&nbsp;&nbsp;&nbsp;&nbsp;A. Performance efficiency.
&nbsp;&nbsp;&nbsp;&nbsp;B. Operational excellence.
&nbsp;&nbsp;&nbsp;&nbsp;C. Reliability.
&nbsp;&nbsp;&nbsp;&nbsp;D. Security.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Operations as code is part of operational excellence.
</details>

---

### Question 92

Which design principle is achieved by following the reliability pillar of the AWS Well-Architected Framework?

&nbsp;&nbsp;&nbsp;&nbsp;A. Vertical scaling.
&nbsp;&nbsp;&nbsp;&nbsp;B. Manual failure recovery.
&nbsp;&nbsp;&nbsp;&nbsp;C. Testing recovery procedures.
&nbsp;&nbsp;&nbsp;&nbsp;D. Changing infrastructure manually.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Testing recovery is key to reliability.
</details>

---

### Question 93

A user has underutilized on-premises resources. Which AWS Cloud concept can BEST address this issue?

&nbsp;&nbsp;&nbsp;&nbsp;A. High availability.
&nbsp;&nbsp;&nbsp;&nbsp;B. Elasticity.
&nbsp;&nbsp;&nbsp;&nbsp;C. Security.
&nbsp;&nbsp;&nbsp;&nbsp;D. Loose coupling.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Elasticity allows right-sizing resources to utilization.
</details>

---

### Question 94

Under the AWS shared responsibility model, which of the following is the customer's responsibility?

&nbsp;&nbsp;&nbsp;&nbsp;A. Patching guest OS and applications.
&nbsp;&nbsp;&nbsp;&nbsp;B. Patching and fixing flaws in the infrastructure.
&nbsp;&nbsp;&nbsp;&nbsp;C. Physical and environmental controls.
&nbsp;&nbsp;&nbsp;&nbsp;D. Configuration of AWS infrastructure devices.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Customers are responsible for guest OS and applications.
</details>

---

### Question 95

A user has limited knowledge of AWS services, but wants to quickly deploy a scalable Node.js application in the AWS Cloud. Which service should be used to deploy the application?

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS CloudFormation.
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Elastic Beanstalk.
&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon EC2.
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS OpsWorks.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Elastic Beanstalk simplifies deployment of scalable applications.
</details>

---

### Question 96

What are the advantages of deploying an application with Amazon EC2 instances in multiple Availability Zones? (Choose TWO)

&nbsp;&nbsp;&nbsp;&nbsp;A. All resources run using on-premises infrastructure.
&nbsp;&nbsp;&nbsp;&nbsp;B. Increasing the availability of the application.
&nbsp;&nbsp;&nbsp;&nbsp;C. Allowing the application to serve cross-region users with low latency.
&nbsp;&nbsp;&nbsp;&nbsp;D. Preventing a single point of failure.
&nbsp;&nbsp;&nbsp;&nbsp;E. Increasing the load of the application.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B, D
> **Explanation:** Multi-AZ deployment increases availability and avoids single points of failure.
</details>

---

### Question 97

A company wants to ensure its infrastructure is designed for fault tolerance and business continuity in the event of an environmental disruption. Which AWS infrastructure component should the company replicate across?

&nbsp;&nbsp;&nbsp;&nbsp;A. Edge locations.
&nbsp;&nbsp;&nbsp;&nbsp;B. Availability Zones.
&nbsp;&nbsp;&nbsp;&nbsp;C. Regions.
&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon Route 53.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Replicating across AZs provides fault tolerance.
</details>

---

### Question 98

Which AWS Cloud design principles can help increase reliability? (Choose TWO)

&nbsp;&nbsp;&nbsp;&nbsp;A. Using monolithic architecture.
&nbsp;&nbsp;&nbsp;&nbsp;B. Measuring overall efficiency.
&nbsp;&nbsp;&nbsp;&nbsp;C. Testing recovery procedures.
&nbsp;&nbsp;&nbsp;&nbsp;D. Adopting a consumption model.
&nbsp;&nbsp;&nbsp;&nbsp;E. Automatically recovering from failure.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C, E
> **Explanation:** Recovery testing and automatic recovery increase reliability.
</details>

---

### Question 99

Which cloud computing benefit does AWS demonstrate with its ability to offer lower variable costs as a result of high purchase volumes?

&nbsp;&nbsp;&nbsp;&nbsp;A. Pay-as-you-go pricing.
&nbsp;&nbsp;&nbsp;&nbsp;B. High availability.
&nbsp;&nbsp;&nbsp;&nbsp;C. Global reach.
&nbsp;&nbsp;&nbsp;&nbsp;D. Economies of scale.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** Economies of scale lower costs through volume.
</details>

---

### Question 100

How can a company reduce its Total Cost of Ownership (TCO) using AWS?

&nbsp;&nbsp;&nbsp;&nbsp;A. By minimizing large capital expenditures.
&nbsp;&nbsp;&nbsp;&nbsp;B. By having no responsibility for third-party license costs.
&nbsp;&nbsp;&nbsp;&nbsp;C. By having no operational expenditures.
&nbsp;&nbsp;&nbsp;&nbsp;D. By having AWS manage applications.

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** AWS reduces CapEx.
</details>

### CloudConcepts.md (Continued)

*(Continuing from Question 100 with all remaining unique Cloud Concepts questions from the aggregated sources. Total: 150 unique questions)*

---

### Question 101

Which AWS Well-Architected Framework pillar focuses on the ability of a system to recover from disruptions?

&nbsp;&nbsp;&nbsp;&nbsp;A. Operational Excellence
&nbsp;&nbsp;&nbsp;&nbsp;B. Security
&nbsp;&nbsp;&nbsp;&nbsp;C. Reliability
&nbsp;&nbsp;&nbsp;&nbsp;D. Performance Efficiency

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** The Reliability pillar ensures systems recover from infrastructure failures, application errors, and service disruptions automatically.
</details>

---

### Question 102

What is the main advantage of using multiple Availability Zones for an application?

&nbsp;&nbsp;&nbsp;&nbsp;A. Reduced latency for global users
&nbsp;&nbsp;&nbsp;&nbsp;B. Fault tolerance and high availability
&nbsp;&nbsp;&nbsp;&nbsp;C. Lower storage costs
&nbsp;&nbsp;&nbsp;&nbsp;D. Automatic scaling

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Multiple AZs provide fault tolerance since AZs are isolated from each other, ensuring high availability if one fails.
</details>

---

### Question 103

Which AWS service provides a fully managed relational database with Multi-AZ deployment capability?

&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon DynamoDB
&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon RDS
&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon Redshift
&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon ElastiCache

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Amazon RDS supports Multi-AZ deployments for automatic failover and high availability.
</details>

---

### Question 104

What does the AWS Well-Architected Framework's Performance Efficiency pillar focus on?

&nbsp;&nbsp;&nbsp;&nbsp;A. Protecting systems and data
&nbsp;&nbsp;&nbsp;&nbsp;B. Using computing resources efficiently
&nbsp;&nbsp;&nbsp;&nbsp;C. Running and monitoring systems
&nbsp;&nbsp;&nbsp;&nbsp;D. Controlling costs

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Performance Efficiency focuses on selecting the right resource types and quantities to meet demand efficiently.
</details>

---

### Question 105

Which principle helps reduce the blast radius of failures in cloud applications?

&nbsp;&nbsp;&nbsp;&nbsp;A. Tight coupling
&nbsp;&nbsp;&nbsp;&nbsp;B. Monolithic architecture
&nbsp;&nbsp;&nbsp;&nbsp;C. Loose coupling
&nbsp;&nbsp;&nbsp;&nbsp;D. Vertical scaling

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Loose coupling allows components to fail independently, limiting the impact of failures.
</details>

---

### Question 106

What is the benefit of the AWS global infrastructure for international applications?

&nbsp;&nbsp;&nbsp;&nbsp;A. Reduced compliance requirements
&nbsp;&nbsp;&nbsp;&nbsp;B. Lower latency through regional deployment
&nbsp;&nbsp;&nbsp;&nbsp;C. Single point of failure elimination
&nbsp;&nbsp;&nbsp;&nbsp;D. Automatic cost optimization

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Deploying in Regions close to users reduces latency and improves performance.
</details>

---

### Question 107

Which AWS service allows automatic scaling of compute resources based on demand?

&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon EC2
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Auto Scaling
&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon S3
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Lambda

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** AWS Auto Scaling automatically adjusts EC2 capacity based on demand metrics.
</details>

---

### Question 108

What is the AWS shared responsibility model?

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS manages everything
&nbsp;&nbsp;&nbsp;&nbsp;B. Customers manage everything
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS manages security OF the cloud, customers manage IN the cloud
&nbsp;&nbsp;&nbsp;&nbsp;D. Equal split of all responsibilities

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** AWS secures the cloud infrastructure; customers secure their data and applications.
</details>

---

### Question 109

Which AWS service provides Infrastructure as Code (IaC)?

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS CloudFormation
&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon CloudWatch
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Config
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Systems Manager

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** CloudFormation allows provisioning resources using declarative templates.
</details>

---

### Question 110

What is the default durability of Amazon S3?

&nbsp;&nbsp;&nbsp;&nbsp;A. 99.9%
&nbsp;&nbsp;&nbsp;&nbsp;B. 99.99%
&nbsp;&nbsp;&nbsp;&nbsp;C. 99.999999999%
&nbsp;&nbsp;&nbsp;&nbsp;D. 100%

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** S3 provides 99.999999999% (11 9's) durability by automatically replicating objects across multiple AZs.
</details>

---

### Question 111

Which AWS support plan includes a Technical Account Manager?

&nbsp;&nbsp;&nbsp;&nbsp;A. Basic
&nbsp;&nbsp;&nbsp;&nbsp;B. Developer
&nbsp;&nbsp;&nbsp;&nbsp;C. Business
&nbsp;&nbsp;&nbsp;&nbsp;D. Enterprise

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** Enterprise Support includes a dedicated Technical Account Manager for proactive guidance.
</details>

---

### Question 112

What is the maximum number of Availability Zones in an AWS Region?

&nbsp;&nbsp;&nbsp;&nbsp;A. 2
&nbsp;&nbsp;&nbsp;&nbsp;B. 3
&nbsp;&nbsp;&nbsp;&nbsp;C. 6
&nbsp;&nbsp;&nbsp;&nbsp;D. Unlimited

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Most Regions have 3-6 AZs, with some having up to 6 available.
</details>

---

### Question 113

Which service provides content delivery with low latency worldwide?

&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon Route 53
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Global Accelerator
&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon CloudFront
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Direct Connect

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** CloudFront is a CDN that caches content at edge locations globally.
</details>

---

### Question 114

What is the AWS Free Tier?

&nbsp;&nbsp;&nbsp;&nbsp;A. Always free services
&nbsp;&nbsp;&nbsp;&nbsp;B. 12 months of limited free usage
&nbsp;&nbsp;&nbsp;&nbsp;C. Both A and B
&nbsp;&nbsp;&nbsp;&nbsp;D. Enterprise support

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Free Tier includes always-free offers and 12 months of limited usage across 20+ services.
</details>

---

### Question 115

Which EC2 purchasing option provides the most significant discount?

&nbsp;&nbsp;&nbsp;&nbsp;A. On-Demand
&nbsp;&nbsp;&nbsp;&nbsp;B. Reserved (3-year, All Upfront)
&nbsp;&nbsp;&nbsp;&nbsp;C. Spot
&nbsp;&nbsp;&nbsp;&nbsp;D. Savings Plans

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** 3-year Reserved Instances with All Upfront payment offer up to 75% discount.
</details>

---

### Question 116

What is Amazon Machine Image (AMI)?

&nbsp;&nbsp;&nbsp;&nbsp;A. Operating system template for EC2
&nbsp;&nbsp;&nbsp;&nbsp;B. Storage volume
&nbsp;&nbsp;&nbsp;&nbsp;C. Network configuration
&nbsp;&nbsp;&nbsp;&nbsp;D. Security group

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** AMI is a template containing OS, software, and configuration for launching EC2 instances.
</details>

---

### Question 117

Which service provides fully managed NoSQL database?

&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon RDS
&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon DynamoDB
&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon Redshift
&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon Aurora

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** DynamoDB is a fully managed NoSQL database with seamless scalability.
</details>

---

### Question 118

What is the purpose of Amazon Route 53?

&nbsp;&nbsp;&nbsp;&nbsp;A. CDN service
&nbsp;&nbsp;&nbsp;&nbsp;B. DNS service
&nbsp;&nbsp;&nbsp;&nbsp;C. Load balancing
&nbsp>&nbsp;&nbsp;&nbsp;D. VPN connection

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Route 53 is a scalable DNS web service for domain registration and routing.
</details>

---

### Question 119

Which storage class in S3 has the lowest cost?

&nbsp;&nbsp;&nbsp;&nbsp;A. Standard
&nbsp;&nbsp;&nbsp;&nbsp;B. Intelligent-Tiering
&nbsp;&nbsp;&nbsp;&nbsp;C. Glacier Deep Archive
&nbsp;&nbsp;&nbsp;&nbsp;D. One Zone-IA

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Glacier Deep Archive is the lowest cost for long-term archival storage.
</details>

---

### Question 120

What is Elastic Load Balancing (ELB)?

&nbsp;&nbsp;&nbsp;&nbsp;A. Distributes traffic across multiple targets
&nbsp;&nbsp;&nbsp;&nbsp;B. Scales storage automatically
&nbsp;&nbsp;&nbsp;&nbsp;C. Manages database connections
&nbsp;&nbsp;&nbsp;&nbsp;D. Provides DNS resolution

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** ELB automatically distributes incoming traffic across multiple targets for high availability.
</details>

---

### Question 121

Which service is used for ETL (Extract, Transform, Load) jobs?

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Glue
&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon EMR
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Batch
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Lambda

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** AWS Glue is a fully managed ETL service for data preparation.
</details>

---

### Question 122

What is the availability SLA for Amazon S3 Standard storage?

&nbsp;&nbsp;&nbsp;&nbsp;A. 99.9%
&nbsp;&nbsp;&nbsp;&nbsp;B. 99.99%
&nbsp;&nbsp;&nbsp;&nbsp;C. 99.999999999%
&nbsp;&nbsp;&nbsp;&nbsp;D. 100%

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** S3 Standard offers 99.99% availability SLA.
</details>

---

### Question 123

Which service provides real-time data streaming?

&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon Kinesis
&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon SQS
&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon SNS
&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon MQ

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Amazon Kinesis processes and analyzes real-time streaming data.
</details>

---

### Question 124

What is AWS Artifact?

&nbsp;&nbsp;&nbsp;&nbsp;A. Compliance reports portal
&nbsp;&nbsp;&nbsp;&nbsp;B. Cost management tool
&nbsp;&nbsp;&nbsp;&nbsp;C. Security scanning service
&nbsp;&nbsp;&nbsp;&nbsp;D. Migration assessment tool

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** AWS Artifact provides on-demand access to AWS compliance reports.
</details>

---

### Question 125

Which EC2 instance type is optimized for compute-intensive workloads?

&nbsp;&nbsp;&nbsp;&nbsp;A. C5
&nbsp;&nbsp;&nbsp;&nbsp;B. M5
&nbsp;&nbsp;&nbsp;&nbsp;C. R5
&nbsp;&nbsp;&nbsp;&nbsp;D. T3

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** C5 instances are optimized for compute-intensive applications like batch processing.
</details>

---

### Question 126

What is the purpose of AWS Trusted Advisor?

&nbsp;&nbsp;&nbsp;&nbsp;A. Real-time security scanning
&nbsp;&nbsp;&nbsp;&nbsp;B. Best practice recommendations
&nbsp;&nbsp;&nbsp;&nbsp;C. Automated backup service
&nbsp;&nbsp;&nbsp;&nbsp;D. Cost allocation tool

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Trusted Advisor provides recommendations across security, cost, performance, and reliability.
</details>

---

### Question 127

Which service provides managed Kafka?

&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon MSK
&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon MQ
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Batch
&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon Kinesis

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Amazon MSK is a fully managed Apache Kafka service.
</details>

---

### Question 128

What is Amazon EBS?

&nbsp;&nbsp;&nbsp;&nbsp;A. Object storage
&nbsp;&nbsp;&nbsp;&nbsp;B. Block storage
&nbsp;&nbsp;&nbsp;&nbsp;C. File storage
&nbsp;&nbsp;&nbsp;&nbsp;D. Archive storage

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** EBS provides persistent block storage volumes for EC2 instances.
</details>

---

### Question 129

Which service is used for container orchestration?

&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon ECS
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Fargate
&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon EKS
&nbsp;&nbsp;&nbsp;&nbsp;D. All of the above

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** ECS, Fargate, and EKS all provide container orchestration capabilities.
</details>

---

### Question 130

What is the maximum size of a single Amazon S3 object?

&nbsp;&nbsp;&nbsp;&nbsp;A. 1 GB
&nbsp;&nbsp;&nbsp;&nbsp;B. 5 TB
&nbsp;&nbsp;&nbsp;&nbsp;C. 5 TB
&nbsp;&nbsp;&nbsp;&nbsp;D. Unlimited

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** S3 supports objects up to 5 terabytes in size.
</details>

---

### Question 131

Which AWS service provides serverless container management?

&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon ECS
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Fargate
&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon EKS
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Batch

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Fargate runs containers without managing servers or clusters.
</details>

---

### Question 132

What is Amazon VPC?

&nbsp;&nbsp;&nbsp;&nbsp;A. Virtual Private Cloud
&nbsp;&nbsp;&nbsp;&nbsp;B. Virtual Public Cloud
&nbsp;&nbsp;&nbsp;&nbsp;C. Virtual Processing Cloud
&nbsp;&nbsp;&nbsp;&nbsp;D. Virtual Performance Cloud

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** VPC provides a logically isolated network within AWS.
</details>

---

### Question 133

Which service provides machine learning without coding?

&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon SageMaker
&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon Rekognition
&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon Lex
&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon Comprehend

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** All of the above
> **Explanation:** All provide no-code ML services for specific use cases.
</details>

---

### Question 134

What is the billing granularity for Linux EC2 instances?

&nbsp;&nbsp;&nbsp;&nbsp;A. Per hour
&nbsp;&nbsp;&nbsp;&nbsp;B. Per minute
&nbsp;&nbsp;&nbsp;&nbsp;C. Per second
&nbsp;&nbsp;&nbsp;&nbsp;D. Per month

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Linux EC2 instances are billed per second with a 60-second minimum.
</details>

---

### Question 135

Which service provides global application acceleration?

&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon CloudFront
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Global Accelerator
&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon Route 53
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Direct Connect

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Global Accelerator improves availability and performance using AWS global network.
</details>

---

### Question 136

What is AWS Shield?

&nbsp;&nbsp;&nbsp;&nbsp;A. WAF service
&nbsp;&nbsp;&nbsp;&nbsp;B. DDoS protection
&nbsp;&nbsp;&nbsp;&nbsp;C. Encryption service
&nbsp;&nbsp;&nbsp;&nbsp;D. Backup service

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** AWS Shield provides managed DDoS protection.
</details>

---

### Question 137

Which storage service provides shared file system for EC2?

&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon EBS
&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon EFS
&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon S3
&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon Glacier

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** EFS provides scalable file storage accessible by multiple EC2 instances.
</details>

---

### Question 138

What is the default VPC CIDR block?

&nbsp;&nbsp;&nbsp;&nbsp;A. 10.0.0.0/16
&nbsp;&nbsp;&nbsp;&nbsp;B. 172.31.0.0/16
&nbsp;&nbsp;&nbsp;&nbsp;C. 192.168.0.0/16
&nbsp;&nbsp;&nbsp;&nbsp;D. 100.64.0.0/10

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Default VPC uses 10.0.0.0/16, providing 65,536 IP addresses.
</details>

---

### Question 139

Which service provides push notifications?

&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon SNS
&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon SQS
&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon SES
&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon Pinpoint

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** SNS provides pub/sub messaging for notifications and SMS.
</details>

---

### Question 140

What is Amazon CloudWatch?

&nbsp;&nbsp;&nbsp;&nbsp;A. Monitoring and observability service
&nbsp;&nbsp;&nbsp;&nbsp;B. Log management service
&nbsp;&nbsp;&nbsp;&nbsp;C. Both A and B
&nbsp;&nbsp;&nbsp;&nbsp;D. Security service

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** CloudWatch provides monitoring, logs, alarms, and events.
</details>

---

### Question 141

Which EC2 instance type is burstable?

&nbsp;&nbsp;&nbsp;&nbsp;A. M5
&nbsp;&nbsp;&nbsp;&nbsp;B. C5
&nbsp;&nbsp;&nbsp;&nbsp;C. T3
&nbsp;&nbsp;&nbsp;&nbsp;D. R5

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** T3 instances provide burstable CPU for variable workloads.
</details>

---

### Question 142

What is AWS Config?

&nbsp;&nbsp;&nbsp;&nbsp;A. Resource configuration tracking
&nbsp;&nbsp;&nbsp;&nbsp;B. Compliance monitoring
&nbsp;&nbsp;&nbsp;&nbsp;C. Both A and B
&nbsp;&nbsp;&nbsp;&nbsp;D. Cost tracking

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Config tracks resource configurations and compliance over time.
</details>

---

### Question 143

Which service provides fully managed PostgreSQL?

&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon RDS for PostgreSQL
&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon Aurora PostgreSQL
&nbsp;&nbsp;&nbsp;&nbsp;C. Both A and B
&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon DynamoDB

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Both RDS and Aurora provide managed PostgreSQL databases.
</details>

---

### Question 144

What is the AWS Well-Architected Tool?

&nbsp;&nbsp;&nbsp;&nbsp;A. Review service for best practices
&nbsp;&nbsp;&nbsp;&nbsp;B. Cost calculator
&nbsp;&nbsp;&nbsp;&nbsp;C. Migration tool
&nbsp;&nbsp;&nbsp;&nbsp;D. Security scanner

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Well-Architected Tool helps review workloads against framework best practices.
</details>

---

### Question 145

Which service provides API management?

&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon API Gateway
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS AppSync
&nbsp;&nbsp;&nbsp;&nbsp;C. Both A and B
&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon Route 53

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** API Gateway for REST/HTTP APIs, AppSync for GraphQL APIs.
</details>

---

### Question 146

What is AWS Systems Manager?

&nbsp;&nbsp;&nbsp;&nbsp;A. Patch management
&nbsp;&nbsp;&nbsp;&nbsp;B. Configuration management
&nbsp;&nbsp;&nbsp;&nbsp;C. Session management
&nbsp;&nbsp;&nbsp;&nbsp;D. All of the above

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** Systems Manager provides operational management for EC2 and on-premises.
</details>

---

### Question 147

Which service provides serverless workflows?

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Step Functions
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Lambda
&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon States Language
&nbsp;&nbsp;&nbsp;&nbsp;D. All of the above

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Step Functions coordinates multiple AWS services into serverless workflows.
</details>

---

### Question 148

What is the default internet access for EC2 in default VPC?

&nbsp;&nbsp;&nbsp;&nbsp;A. No internet access
&nbsp;&nbsp;&nbsp;&nbsp;B. Public IP assigned
&nbsp;&nbsp;&nbsp;&nbsp;C. Private subnet only
&nbsp;&nbsp;&nbsp;&nbsp;D. NAT required

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Default VPC subnets are public with auto-assigned public IPs.
</details>

---

### Question 149

Which service provides business analytics?

&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon QuickSight
&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon Athena
&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon Redshift
&nbsp;&nbsp;&nbsp;&nbsp;D. All of the above

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** QuickSight for BI dashboards, Athena for SQL queries, Redshift for data warehouse.
</details>

---

### Question 150

What is the AWS Cloud Adoption Framework (CAF)?

&nbsp;&nbsp;&nbsp;&nbsp;A. Migration methodology
&nbsp;&nbsp;&nbsp;&nbsp;B. Structured guidance for cloud adoption
&nbsp;&nbsp;&nbsp;&nbsp;C. Cost optimization tool
&nbsp;&nbsp;&nbsp;&nbsp;D. Security framework

<details><summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** AWS CAF provides guidance across business, people, governance, and technical perspectives for successful cloud adoption.
</details>

---
