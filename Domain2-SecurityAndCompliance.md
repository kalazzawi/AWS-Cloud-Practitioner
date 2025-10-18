# Security and Compliance

---

### Question 1

You have noticed that several critical Amazon EC2 instances have been terminated. Which of the following AWS services would help you determine who took this action?

&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon Inspector.  
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS CloudTrail.  
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Trusted Advisor.  
&nbsp;&nbsp;&nbsp;&nbsp;D. EC2 Instance Usage Report.

<details><summary>Click to reveal</summary><br>**Correct Answer:** B<br><br>**Explanation:** AWS CloudTrail logs all API calls and actions in your AWS account, allowing you to track who terminated the instances by reviewing the event history. Amazon Inspector is for vulnerability assessment, Trusted Advisor for optimization, and EC2 Usage Report for billing info.</details>

---

### Question 2

Which statement is true regarding the AWS Shared Responsibility Model?

&nbsp;&nbsp;&nbsp;&nbsp;A. Responsibilities vary depending on the services used.  
&nbsp;&nbsp;&nbsp;&nbsp;B. Security of the IaaS services is the responsibility of AWS.  
&nbsp;&nbsp;&nbsp;&nbsp;C. Patching the guest OS is always the responsibility of AWS.  
&nbsp;&nbsp;&nbsp;&nbsp;D. Security of the managed services is the responsibility of the customer.

<details><summary>Click to reveal</summary><br>**Correct Answer:** A<br><br>**Explanation:** The shared responsibility model defines that AWS manages security of the cloud (hardware, infrastructure), while customers manage security in the cloud (data, applications). Responsibilities vary by service; for example, in EC2 (IaaS), customers patch the OS, but in RDS (managed), AWS does. Option B is true for IaaS, but not complete; C is false for EC2; D is false, AWS handles managed services security.</details>

---

### Question 3

An organization has a large number of technical employees who operate their AWS Cloud infrastructure. What does AWS provide to help organize them into teams and then assign the appropriate permissions for each team?

&nbsp;&nbsp;&nbsp;&nbsp;A. IAM roles.  
&nbsp;&nbsp;&nbsp;&nbsp;B. IAM users.  
&nbsp;&nbsp;&nbsp;&nbsp;C. IAM user groups.  
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Organizations.

<details><summary>Click to reveal</summary><br>**Correct Answer:** C<br><br>**Explanation:** IAM user groups allow grouping users and assigning permissions via policies to the group, simplifying management for teams. Roles are for temporary access, users are individual accounts, Organizations is for multi-account management.</details>

---

### Question 4

What should you do in order to keep the data on EBS volumes safe? (Choose TWO)

&nbsp;&nbsp;&nbsp;&nbsp;A. Regularly update firmware on EBS devices.  
&nbsp;&nbsp;&nbsp;&nbsp;B. Create EBS snapshots.  
&nbsp;&nbsp;&nbsp;&nbsp;C. Ensure that EBS data is encrypted at rest.  
&nbsp;&nbsp;&nbsp;&nbsp;D. Store a backup daily in an external drive.  
&nbsp;&nbsp;&nbsp;&nbsp;E. Prevent any unauthorized access to AWS data centers.

<details><summary>Click to reveal</summary><br>**Correct Answer:** B, C<br><br>**Explanation:** EBS snapshots provide point-in-time backups for data recovery, and encryption at rest protects data from unauthorized access. Option A is not customer responsibility, D is not scalable, E is AWS responsibility.</details>

---

### Question 5

What does the "Principle of Least Privilege" refer to?

&nbsp;&nbsp;&nbsp;&nbsp;A. You should grant your users only the permissions they need when they need them and nothing more.  
&nbsp;&nbsp;&nbsp;&nbsp;B. All IAM users should have at least the necessary permissions to access the core AWS services.  
&nbsp;&nbsp;&nbsp;&nbsp;C. All trusted IAM users should have access to any AWS service in the respective AWS account.  
&nbsp;&nbsp;&nbsp;&nbsp;D. IAM users should not be granted any permissions; to keep your account safe.

<details><summary>Click to reveal</summary><br>**Correct Answer:** A<br><br>**Explanation:** The principle of least privilege is a security best practice that limits users' access rights to the minimum permissions they need to perform their work, reducing the risk of accidental or malicious misuse. Options B, C, D are contrary to this principle.</details>

---

### Question 6

Hundreds of thousands of DDoS attacks are recorded every month worldwide. What service does AWS provide to help protect AWS Customers from these attacks? (Choose TWO)

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Shield.  
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Config.  
&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon Cognito.  
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS WAF.  
&nbsp;&nbsp;&nbsp;&nbsp;E. AWS KMS.

<details><summary>Click to reveal</summary><br>**Correct Answer:** A, D<br><br>**Explanation:** AWS Shield provides managed DDoS protection, and AWS WAF is a web application firewall that helps protect against common web exploits like SQL injection and cross-site scripting, which can lead to DDoS. Config is for configuration, Cognito for authentication, KMS for encryption.</details>

---

### Question 7

A company has moved to AWS recently. Which of the following AWS Services will help ensure that they have the proper security settings? (Choose TWO)

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Trusted Advisor.  
&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon Inspector.  
&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon SNS.  
&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon CloudWatch.  
&nbsp;&nbsp;&nbsp;&nbsp;E. Concierge Support Team.

<details><summary>Click to reveal</summary><br>**Correct Answer:** A, B<br><br>**Explanation:** Trusted Advisor checks for best practices in security, and Amazon Inspector assesses applications for vulnerabilities and deviations from best practices. SNS is for notifications, CloudWatch for monitoring, Concierge is for billing support in Enterprise plan.</details>

---

### Question 8

What is the AWS feature that provides an additional level of security above the default authentication mechanism of usernames and passwords?

&nbsp;&nbsp;&nbsp;&nbsp;A. Encrypted keys.  
&nbsp;&nbsp;&nbsp;&nbsp;B. Email verification.  
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS KMS.  
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS MFA.

<details><summary>Click to reveal</summary><br>**Correct Answer:** D<br><br>**Explanation:** AWS Multi-Factor Authentication (MFA) adds an extra layer by requiring a second authentication factor, like a code from a device, beyond username and password. Encrypted keys are for data, email verification is for account setup, KMS is for key management.</details>

---

### Question 9

According to the AWS Shared responsibility model, which of the following are the responsibility of the customer? (Choose TWO)

&nbsp;&nbsp;&nbsp;&nbsp;A. Managing environmental events of AWS data centers.  
&nbsp;&nbsp;&nbsp;&nbsp;B. Protecting the confidentiality of data in transit in Amazon S3.  
&nbsp;&nbsp;&nbsp;&nbsp;C. Controlling physical access to AWS Regions.  
&nbsp;&nbsp;&nbsp;&nbsp;D. Ensuring that the underlying EC2 host is configured properly.  
&nbsp;&nbsp;&nbsp;&nbsp;E. Patching applications installed on Amazon EC2.

<details><summary>Click to reveal</summary><br>**Correct Answer:** B, E<br><br>**Explanation:** Customers are responsible for data security in transit and patching applications on EC2. Option A and C are AWS responsibilities, D is AWS for the host, customer for the guest OS.</details>

---

### Question 10

Which of the following helps a customer view the Amazon EC2 billing activity for the past month?

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Budgets.  
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Pricing Calculator.  
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Systems Manager.  
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Cost & Usage Reports.

<details><summary>Click to reveal</summary><br>**Correct Answer:** D<br><br>**Explanation:** AWS Cost & Usage Reports provide comprehensive billing data including EC2 usage for the past month, delivered to S3. Budgets is for alerts, Pricing Calculator for estimates, Systems Manager for operations.</details>

---

### Question 11

Your company wants to ensure that all EC2 instances are launched from approved AMIs only. Which service helps accomplish this?

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Config  
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Trusted Advisor  
&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon Inspector  
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Systems Manager

<details><summary>Click to reveal</summary><br>**Correct Answer:** A<br><br>**Explanation:** AWS Config can track resource configurations and ensure EC2 instances use approved AMIs through conformance packs and rules. Trusted Advisor provides recommendations, Inspector scans for vulnerabilities, Systems Manager manages instances but doesn't enforce AMI policies.</details>

---

### Question 12

Which AWS service helps you identify which users have made configuration changes to your AWS resources?

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Config  
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS CloudTrail  
&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon CloudWatch  
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Trusted Advisor

<details><summary>Click to reveal</summary><br>**Correct Answer:** B<br><br>**Explanation:** AWS CloudTrail records API calls including who made configuration changes. Config records configuration states but not who made changes, CloudWatch monitors metrics/logs, Trusted Advisor provides recommendations.</details>

---

### Question 13

A company needs to encrypt data at rest in S3 buckets. Which service should they use?

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS KMS  
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Certificate Manager  
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Secrets Manager  
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS IAM

<details><summary>Click to reveal</summary><br>**Correct Answer:** A<br><br>**Explanation:** AWS Key Management Service (KMS) provides keys for encrypting data at rest in S3. Certificate Manager is for SSL/TLS, Secrets Manager for credentials, IAM for access control.</details>

---

### Question 14

What is the PRIMARY benefit of using AWS Shield Standard?

&nbsp;&nbsp;&nbsp;&nbsp;A. Web application firewall  
&nbsp;&nbsp;&nbsp;&nbsp;B. DDoS protection  
&nbsp;&nbsp;&nbsp;&nbsp;C. Encryption at rest  
&nbsp;&nbsp;&nbsp;&nbsp;D. Vulnerability scanning

<details><summary>Click to reveal</summary><br>**Correct Answer:** B<br><br>**Explanation:** AWS Shield Standard provides always-on DDoS protection at no additional charge for all AWS customers. WAF is separate, encryption is KMS, scanning is Inspector.</details>

---

### Question 15

Which service helps you assess whether your AWS environment complies with security best practices?

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Trusted Advisor  
&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon Inspector  
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Config  
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS CloudTrail

<details><summary>Click to reveal</summary><br>**Correct Answer:** A<br><br>**Explanation:** AWS Trusted Advisor provides real-time guidance across security best practices. Inspector assesses vulnerabilities, Config tracks compliance, CloudTrail logs activity.</details>

---
