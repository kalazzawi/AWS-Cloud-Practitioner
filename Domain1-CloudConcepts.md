# Cloud Concepts

### Question 1

AWS allows users to manage their resources using a web based user interface. What is the name of this interface?

A. AWS CLI.

B. AWS API.

C. AWS SDK.

D. AWS Management Console.

<details><summary>Click to reveal</summary><br>**Correct:** D<br><br>**Explanation:** The AWS Management Console is a web-based user interface that allows users to interact with AWS services graphically without the need for coding. It is accessible via a web browser and provides a user-friendly way to manage resources. In contrast, the AWS CLI is a command-line tool for managing services via scripts, AWS API is the underlying application programming interface for programmatic interactions, and AWS SDK is a set of libraries for integrating AWS services into applications in various programming languages.</details>

### Question 2

Which of the following is an example of horizontal scaling in the AWS Cloud?

A. Replacing an existing EC2 instance with a larger, more powerful one.

B. Increasing the compute capacity of a single EC2 instance to address the growing demands of an application.

C. Adding more RAM capacity to an EC2 instance.

D. Adding more EC2 instances of the same size to handle an increase in traffic.

<details><summary>Click to reveal</summary><br>**Correct:** D<br><br>**Explanation:** Horizontal scaling, also known as scaling out, involves adding more instances to distribute the load across multiple servers, which enhances availability and fault tolerance. This is a key principle of cloud architecture. Options A, B, and C describe vertical scaling, or scaling up, where you increase the resources of a single instance, which has limits and can create single points of failure.</details>

### Question 3

Which of the below options are related to the reliability of AWS? (Choose TWO)

A. Applying the principle of least privilege to all AWS resources.

B. Automatically provisioning new resources to meet demand.

C. All AWS services are considered Global Services, and this design helps customers serve their international users.

D. Providing compensation to customers if issues occur.

E. Ability to recover quickly from failures.

<details><summary>Click to reveal</summary><br>**Correct:** B, E<br><br>**Explanation:** Reliability in AWS refers to the ability of a system to recover from infrastructure or service disruptions and dynamically acquire computing resources to meet demand. Automatic provisioning (B) is achieved through services like Auto Scaling, and quick recovery (E) is supported by features like Multi-AZ deployments. Option A is security-related, C is about global reach but not directly reliability, and D is about SLA compensation, not reliability itself.</details>

### Question 4

Adjusting compute capacity dynamically to reduce cost is an implementation of which AWS cloud best practice?

A. Build security in every layer.

B. Parallelize tasks.

C. Implement elasticity.

D. Adopt monolithic architecture.

<details><summary>Click to reveal</summary><br>**Correct:** C<br><br>**Explanation:** Elasticity is the ability to automatically add or remove resources based on demand, which optimizes costs by ensuring you only pay for what you use. This is a core AWS best practice under the Well-Architected Framework. Option A is security, B is for performance, and D is the opposite of recommended microservices architecture.</details>

### Question 5

What are the benefits of having infrastructure hosted in AWS? (Choose TWO)

A. Increasing speed and agility.

B. There is no need to worry about security.

C. Gaining complete control over the physical infrastructure.

D. Operating applications on behalf of customers.

E. All of the physical security and most of the data/network security are taken care of for you.

<details><summary>Click to reveal</summary><br>**Correct:** A, E<br><br>**Explanation:** AWS provides speed and agility by allowing rapid provisioning of resources, and handles physical and network security under the shared responsibility model, freeing customers to focus on application-level security. Option B is incorrect as customers are responsible for security in the cloud, C is not true as AWS manages physical infrastructure, and D is not a benefit as customers manage their own applications.</details>

### Question 6

What is the advantage of the AWS-recommended practice of “decoupling” applications?

A. Allows treating an application as a single, cohesive unit.

B. Reduces inter-dependencies so that failures do not impact other components of the application.

C. Allows updates of any monolithic application quickly and easily.

D. Allows tracking of any API call made to any AWS service.

<details><summary>Click to reveal</summary><br>**Correct:** B<br><br>**Explanation:** Decoupling reduces dependencies between components, making the system more resilient to failures, easier to scale, and simpler to update individual parts without affecting the whole. This aligns with microservices architecture. Option A describes monolithic, C is also monolithic, and D is CloudTrail's function.</details>

### Question 7

One of the most important AWS best-practices to follow is the cloud architecture principle of elasticity. How does this principle improve your architecture’s design?

A. By automatically scaling your on-premises resources based on changes in demand.

B. By automatically scaling your AWS resources using an Elastic Load Balancer.

C. By reducing interdependencies between application components wherever possible.

D. By automatically provisioning the required AWS resources based on changes in demand.

<details><summary>Click to reveal</summary><br>**Correct:** D<br><br>**Explanation:** Elasticity allows resources to be provisioned and released automatically based on demand, optimizing costs and performance. Services like Auto Scaling and ELB enable this, but the principle is the automatic provisioning. Option A is not AWS, B is specific to ELB, C is decoupling.</details>

### Question 8

Which of the following does NOT belong to the AWS Cloud Computing models?

A. Platform as a Service (PaaS).

B. Infrastructure as a Service (IaaS).

C. Software as a Service (SaaS).

D. Networking as a Service (NaaS).

<details><summary>Click to reveal</summary><br>**Correct:** D<br><br>**Explanation:** AWS supports IaaS (e.g., EC2), PaaS (e.g., Elastic Beanstalk), and SaaS (e.g., WorkSpaces). NaaS is not a standard AWS model; networking is part of IaaS.</details>

### Question 9

A global company with a large number of AWS accounts is seeking a way in which they can centrally manage billing and security policies across all accounts. Which AWS Service will assist them in meeting these goals?

A. AWS Organizations.

B. AWS Trusted Advisor.

C. IAM User Groups.

D. AWS Config.

<details><summary>Click to reveal</summary><br>**Correct:** A<br><br>**Explanation:** AWS Organizations allows central management of multiple accounts, including consolidated billing and service control policies for security. Trusted Advisor is for optimization, IAM Groups are for user permissions within an account, AWS Config is for resource configuration.</details>

### Question 10

Which of the below is a best-practice when building applications on AWS?

A. Invest heavily in architecting your environment, as it is not easy to change your design later.

B. Use AWS reservations to reduce costs when testing your production environment.

C. Automate wherever possible to make architectural experimentation easier.

D. Provision a large compute capacity to handle any spikes in load

<details><summary>Click to reveal</summary><br>**Correct:** C<br><br>**Explanation:** Automation using tools like CloudFormation makes it easier to experiment, test, and iterate on architectures, aligning with AWS best practices for agility. Option A is contrary to cloud flexibility, B is for cost, D is overprovisioning, which is inefficient.</details>
