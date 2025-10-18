# Cloud Concepts

---

### Question 1

AWS allows users to manage their resources using a web based user interface. What is the name of this interface?

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS CLI.  
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS API.  
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS SDK.  
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Management Console.

<details><summary>Click to reveal answer.</summary>


**Correct Answer:** D

> **Explanation:** The AWS Management Console is a web-based user interface that allows users to interact with AWS services graphically without the need for coding. It is accessible via a web browser and provides a user-friendly way to manage resources. In contrast, the AWS CLI is a command-line tool for managing services via scripts, AWS API is the underlying application programming interface for programmatic interactions, and AWS SDK is a set of libraries for integrating AWS services into applications in various programming languages.
</details>

---

### Question 2

Which of the following is an example of horizontal scaling in the AWS Cloud?

&nbsp;&nbsp;&nbsp;&nbsp;A. Replacing an existing EC2 instance with a larger, more powerful one.  
&nbsp;&nbsp;&nbsp;&nbsp;B. Increasing the compute capacity of a single EC2 instance to address the growing demands of an application.  
&nbsp;&nbsp;&nbsp;&nbsp;C. Adding more RAM capacity to an EC2 instance.  
&nbsp;&nbsp;&nbsp;&nbsp;D. Adding more EC2 instances of the same size to handle an increase in traffic.

<details><summary>Click to reveal answer.</summary><br>**Correct Answer:** D<br><br>**Explanation:** Horizontal scaling, also known as scaling out, involves adding more instances to distribute the load across multiple servers, which enhances availability and fault tolerance. This is a key principle of cloud architecture. Options A, B, and C describe vertical scaling, or scaling up, where you increase the resources of a single instance, which has limits and can create single points of failure.</details>

---

### Question 3

Which of the below options are related to the reliability of AWS? (Choose TWO)

&nbsp;&nbsp;&nbsp;&nbsp;A. Applying the principle of least privilege to all AWS resources.  
&nbsp;&nbsp;&nbsp;&nbsp;B. Automatically provisioning new resources to meet demand.  
&nbsp;&nbsp;&nbsp;&nbsp;C. All AWS services are considered Global Services, and this design helps customers serve their international users.  
&nbsp;&nbsp;&nbsp;&nbsp;D. Providing compensation to customers if issues occur.  
&nbsp;&nbsp;&nbsp;&nbsp;E. Ability to recover quickly from failures.

<details><summary>Click to reveal answer.</summary><br>**Correct Answer:** B, E<br><br>**Explanation:** Reliability in AWS refers to the ability of a system to recover from infrastructure or service disruptions and dynamically acquire computing resources to meet demand. Automatic provisioning (B) is achieved through services like Auto Scaling, and quick recovery (E) is supported by features like Multi-AZ deployments. Option A is security-related, C is about global reach but not directly reliability, and D is about SLA compensation, not reliability itself.</details>

---

### Question 4

Adjusting compute capacity dynamically to reduce cost is an implementation of which AWS cloud best practice?

&nbsp;&nbsp;&nbsp;&nbsp;A. Build security in every layer.  
&nbsp;&nbsp;&nbsp;&nbsp;B. Parallelize tasks.  
&nbsp;&nbsp;&nbsp;&nbsp;C. Implement elasticity.  
&nbsp;&nbsp;&nbsp;&nbsp;D. Adopt monolithic architecture.

<details><summary>Click to reveal answer.</summary><br>**Correct Answer:** C<br><br>**Explanation:** Elasticity is the ability to automatically add or remove resources based on demand, which optimizes costs by ensuring you only pay for what you use. This is a core AWS best practice under the Well-Architected Framework. Option A is security, B is for performance, and D is the opposite of recommended microservices architecture.</details>

---

### Question 5

What are the benefits of having infrastructure hosted in AWS? (Choose TWO)

&nbsp;&nbsp;&nbsp;&nbsp;A. Increasing speed and agility.  
&nbsp;&nbsp;&nbsp;&nbsp;B. There is no need to worry about security.  
&nbsp;&nbsp;&nbsp;&nbsp;C. Gaining complete control over the physical infrastructure.  
&nbsp;&nbsp;&nbsp;&nbsp;D. Operating applications on behalf of customers.  
&nbsp;&nbsp;&nbsp;&nbsp;E. All of the physical security and most of the data/network security are taken care of for you.

<details><summary>Click to reveal answer.</summary><br>**Correct Answer:** A, E<br><br>**Explanation:** AWS provides speed and agility by allowing rapid provisioning of resources, and handles physical and network security under the shared responsibility model, freeing customers to focus on application-level security. Option B is incorrect as customers are responsible for security in the cloud, C is not true as AWS manages physical infrastructure, and D is not a benefit as customers manage their own applications.</details>

---

### Question 6

What is the advantage of the AWS-recommended practice of "decoupling" applications?

&nbsp;&nbsp;&nbsp;&nbsp;A. Allows treating an application as a single, cohesive unit.  
&nbsp;&nbsp;&nbsp;&nbsp;B. Reduces inter-dependencies so that failures do not impact other components of the application.  
&nbsp;&nbsp;&nbsp;&nbsp;C. Allows updates of any monolithic application quickly and easily.  
&nbsp;&nbsp;&nbsp;&nbsp;D. Allows tracking of any API call made to any AWS service.

<details><summary>Click to reveal answer.</summary><br>**Correct Answer:** B<br><br>**Explanation:** Decoupling reduces dependencies between components, making the system more resilient to failures, easier to scale, and simpler to update individual parts without affecting the whole. This aligns with microservices architecture. Option A describes monolithic, C is also monolithic, and D is CloudTrail's function.</details>

---

### Question 7

One of the most important AWS best-practices to follow is the cloud architecture principle of elasticity. How does this principle improve your architecture's design?

&nbsp;&nbsp;&nbsp;&nbsp;A. By automatically scaling your on-premises resources based on changes in demand.  
&nbsp;&nbsp;&nbsp;&nbsp;B. By automatically scaling your AWS resources using an Elastic Load Balancer.  
&nbsp;&nbsp;&nbsp;&nbsp;C. By reducing interdependencies between application components wherever possible.  
&nbsp;&nbsp;&nbsp;&nbsp;D. By automatically provisioning the required AWS resources based on changes in demand.

<details><summary>Click to reveal answer.</summary><br>**Correct Answer:** D<br><br>**Explanation:** Elasticity allows resources to be provisioned and released automatically based on demand, optimizing costs and performance. Services like Auto Scaling and ELB enable this, but the principle is the automatic provisioning. Option A is not AWS, B is specific to ELB, C is decoupling.</details>

---

### Question 8

Which of the following does NOT belong to the AWS Cloud Computing models?

&nbsp;&nbsp;&nbsp;&nbsp;A. Platform as a Service (PaaS).  
&nbsp;&nbsp;&nbsp;&nbsp;B. Infrastructure as a Service (IaaS).  
&nbsp;&nbsp;&nbsp;&nbsp;C. Software as a Service (SaaS).  
&nbsp;&nbsp;&nbsp;&nbsp;D. Networking as a Service (NaaS).

<details><summary>Click to reveal answer.</summary><br>**Correct Answer:** D<br><br>**Explanation:** AWS supports IaaS (e.g., EC2), PaaS (e.g., Elastic Beanstalk), and SaaS (e.g., WorkSpaces). NaaS is not a standard AWS model; networking is part of IaaS.</details>

---

### Question 9

A global company with a large number of AWS accounts is seeking a way in which they can centrally manage billing and security policies across all accounts. Which AWS Service will assist them in meeting these goals?

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Organizations.  
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Trusted Advisor.  
&nbsp;&nbsp;&nbsp;&nbsp;C. IAM User Groups.  
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Config.

<details><summary>Click to reveal answer.</summary><br>**Correct Answer:** A<br><br>**Explanation:** AWS Organizations allows central management of multiple accounts, including consolidated billing and service control policies for security. Trusted Advisor is for optimization, IAM Groups are for user permissions within an account, AWS Config is for resource configuration.</details>

---

### Question 10

Which of the below is a best-practice when building applications on AWS?

&nbsp;&nbsp;&nbsp;&nbsp;A. Invest heavily in architecting your environment, as it is not easy to change your design later.  
&nbsp;&nbsp;&nbsp;&nbsp;B. Use AWS reservations to reduce costs when testing your production environment.  
&nbsp;&nbsp;&nbsp;&nbsp;C. Automate wherever possible to make architectural experimentation easier.  
&nbsp;&nbsp;&nbsp;&nbsp;D. Provision a large compute capacity to handle any spikes in load

<details><summary>Click to reveal answer.</summary><br>**Correct Answer:** C<br><br>**Explanation:** Automation using tools like CloudFormation makes it easier to experiment, test, and iterate on architectures, aligning with AWS best practices for agility. Option A is contrary to cloud flexibility, B is for cost, D is overprovisioning, which is inefficient.</details>

---

### Question 11

The principle "design for failure and nothing will fail" is very important when designing your AWS Cloud architecture. Which of the following would help adhere to this principle? (Choose TWO)

&nbsp;&nbsp;&nbsp;&nbsp;A. Multi-factor authentication.  
&nbsp;&nbsp;&nbsp;&nbsp;B. Availability Zones.  
&nbsp;&nbsp;&nbsp;&nbsp;C. Elastic Load Balancing.  
&nbsp;&nbsp;&nbsp;&nbsp;D. Penetration testing.  
&nbsp;&nbsp;&nbsp;&nbsp;E. Vertical Scaling.

<details><summary>Click to reveal answer.</summary><br>**Correct Answer:** B, C<br><br>**Explanation:** Designing for failure means building redundancy and fault tolerance. Availability Zones provide isolated locations for high availability, and Elastic Load Balancing distributes traffic across multiple instances. MFA is security, penetration testing is assessment, vertical scaling creates single points of failure.</details>

---

### Question 12

Which of the following is equivalent to a user name and password and is used to authenticate your programmatic access to AWS services and APIs?

&nbsp;&nbsp;&nbsp;&nbsp;A. Instance Password.  
&nbsp;&nbsp;&nbsp;&nbsp;B. Key pairs.  
&nbsp;&nbsp;&nbsp;&nbsp;C. Access Keys.  
&nbsp;&nbsp;&nbsp;&nbsp;D. MFA.

<details><summary>Click to reveal answer.</summary><br>**Correct Answer:** C<br><br>**Explanation:** Access Keys (Access Key ID and Secret Access Key) are used for programmatic access via AWS CLI, SDKs, and APIs, similar to username/password for console access. Key pairs are for EC2 SSH/RDP, Instance Password for Windows, MFA is additional security.</details>

---

### Question 13

Which of the following AWS services scale automatically without your intervention? (Choose TWO)

&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon EC2.  
&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon S3.  
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Lambda.  
&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon EMR.  
&nbsp;&nbsp;&nbsp;&nbsp;E. Amazon EBS.

<details><summary>Click to reveal answer.</summary><br>**Correct Answer:** B, C<br><br>**Explanation:** Amazon S3 automatically scales storage and throughput, AWS Lambda automatically scales compute based on invocation rate. EC2 requires Auto Scaling configuration, EMR is managed Hadoop, EBS scales manually or via snapshots.</details>

---

### Question 14

Which of the following is one of the benefits of moving infrastructure from an on-premises data center to AWS?

&nbsp;&nbsp;&nbsp;&nbsp;A. Free support for all enterprise customers.  
&nbsp;&nbsp;&nbsp;&nbsp;B. Automatic data protection.  
&nbsp;&nbsp;&nbsp;&nbsp;C. Reduced Capital Expenditure (CapEx).  
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS holds responsibility for managing customer applications.

<details><summary>Click to reveal answer.</summary><br>**Correct Answer:** C<br><br>**Explanation:** Moving to AWS shifts from CapEx (buying hardware) to OpEx (pay-as-you-go), eliminating upfront infrastructure costs. Support is paid, data protection is customer responsibility, AWS doesn't manage customer applications.</details>

---

### Question 15

Which of the following are important design principles you should adopt when designing systems on AWS? (Choose TWO)

&nbsp;&nbsp;&nbsp;&nbsp;A. Always use Global Services in your architecture rather than Regional Services.  
&nbsp;&nbsp;&nbsp;&nbsp;B. Always choose to pay as you go.  
&nbsp;&nbsp;&nbsp;&nbsp;C. Treat servers as fixed resources.  
&nbsp;&nbsp;&nbsp;&nbsp;D. Automate wherever possible.  
&nbsp;&nbsp;&nbsp;&nbsp;E. Remove single points of failure.

<details><summary>Click to reveal answer.</summary><br>**Correct Answer:** D, E<br><br>**Explanation:** Automation enables rapid deployment and consistency (Well-Architected), removing single points of failure ensures reliability. Global vs Regional depends on use case, pay-as-you-go is pricing, treating servers as fixed contradicts elasticity.</details>

---

### Question 16

Which of the following are advantages of the AWS Cloud? (Choose TWO)

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS manages capacity planning for physical servers.  
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS manages the security of applications built on AWS.  
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS manages the development of applications on AWS.  
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS manages cost planning for virtual servers.  
&nbsp;&nbsp;&nbsp;&nbsp;E. AWS manages the maintenance of the cloud infrastructure.

<details><summary>Click to reveal answer.</summary><br>**Correct Answer:** A, E<br><br>**Explanation:** Under shared responsibility, AWS manages physical capacity planning and infrastructure maintenance. Customers manage application security and development, cost planning is customer responsibility.</details>

---

### Question 17

Which of the following statements describes the AWS Cloud's agility?

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS provides a low-cost virtual network infrastructure for your workloads.  
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS allows you to host your applications in multiple regions around the world.  
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS allows you to pay for what you use with no long-term commitments.  
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS allows you to provision capacity on the fly.

<details><summary>Click to reveal answer.</summary><br>**Correct Answer:** D<br><br>**Explanation:** Agility is the ability to rapidly provision and de-provision resources as needed. Low-cost networking is economy of scale, multi-region is global reach, pay-as-you-go is economic model.</details>

---

### Question 18

Which of the following does AWS provide to help reduce the complexity of managing multiple AWS accounts?

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Trusted Advisor.  
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Management Console.  
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Organizations.  
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS IAM.

<details><summary>Click to reveal answer.</summary><br>**Correct Answer:** C<br><br>**Explanation:** AWS Organizations centralizes management of multiple accounts with consolidated billing and policies. Trusted Advisor is optimization, Console is UI, IAM is within-account permissions.</details>

---

### Question 19

Which of the following does the AWS Cloud provide to its customers? (Choose TWO)

&nbsp;&nbsp;&nbsp;&nbsp;A. Physical networking.  
&nbsp;&nbsp;&nbsp;&nbsp;B. Secure data centers.  
&nbsp;&nbsp;&nbsp;&nbsp;C. Software firewalls.  
&nbsp;&nbsp;&nbsp;&nbsp;D. Multiple storage options.  
&nbsp;&nbsp;&nbsp;&nbsp;E. Virtual storage.

<details><summary>Click to reveal answer.</summary><br>**Correct Answer:** B, D<br><br>**Explanation:** AWS provides secure physical data centers and multiple storage options (S3, EBS, Glacier). Physical networking is abstracted, software firewalls and virtual storage are customer-managed.</details>

---

### Question 20

What are the benefits of using the AWS Cloud Adoption Framework (AWS CAF)?

&nbsp;&nbsp;&nbsp;&nbsp;A. Helps you understand how to use AWS to improve your business.  
&nbsp;&nbsp;&nbsp;&nbsp;B. Provides structured guidance to help customers build a cloud infrastructure.  
&nbsp;&nbsp;&nbsp;&nbsp;C. Provides a structured approach to help customers develop an agile methodology to move to the AWS Cloud.  
&nbsp;&nbsp;&nbsp;&nbsp;D. Provides a structured framework for large enterprises to achieve better business outcomes.

<details><summary>Click to reveal answer.</summary><br>**Correct Answer:** B<br><br>**Explanation:** AWS CAF provides structured guidance for building and migrating to cloud infrastructure across business, people, governance, and technical perspectives. Option D is partially correct but B is more precise.</details>

---
