# Security and Compliance

**Total Questions: 50**  

---

### Question 1

You have noticed that several critical Amazon EC2 instances have been terminated. Which of the following AWS services would help you determine who took this action?

&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon Inspector.
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS CloudTrail.
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Trusted Advisor.
&nbsp;&nbsp;&nbsp;&nbsp;D. EC2 Instance Usage Report.

<details>
<summary>Click to reveal answer.</summary>
  **Correct Answer:** B
  > **Explanation:** AWS CloudTrail logs all API calls and actions in your AWS account, allowing you to track who terminated the instances by reviewing the event history. Amazon Inspector is for vulnerability assessment, Trusted Advisor for optimization, and EC2 Usage Report for billing info.
</details>

---

### Question 2

Which statement is true regarding the AWS Shared Responsibility Model?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Responsibilities vary depending on the services used.
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Security of the IaaS services is the responsibility of AWS.
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Patching the guest OS is always the responsibility of AWS.
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Security of the managed services is the responsibility of the customer.
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
<br><br>
> **Explanation:** The shared responsibility model defines that AWS manages security of the cloud (hardware, infrastructure), while customers manage security in the cloud (data, applications). Responsibilities vary by service; for example, in EC2 (IaaS), customers patch the OS, but in RDS (managed), AWS does. Option B is true for IaaS, but not complete; C is false for EC2; D is false, AWS handles managed services security.
</details>

---

### Question 3

An organization has a large number of technical employees who operate their AWS Cloud infrastructure. What does AWS provide to help organize them into teams and then assign the appropriate permissions for each team?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. IAM roles.
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. IAM users.
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. IAM user groups.
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Organizations.
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** C
<br><br>
> **Explanation:** IAM user groups allow grouping users and assigning permissions via policies to the group, simplifying management for teams. Roles are for temporary access, users are individual accounts, Organizations is for multi-account management.
</details>

---

### Question 4

What should you do in order to keep the data on EBS volumes safe? (Choose TWO)
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Regularly update firmware on EBS devices.
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Create EBS snapshots.
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Ensure that EBS data is encrypted at rest.
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Store a backup daily in an external drive.
<br>&nbsp;&nbsp;&nbsp;&nbsp;E. Prevent any unauthorized access to AWS data centers.
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** B, C
<br><br>
> **Explanation:** EBS snapshots provide point-in-time backups for data recovery, and encryption at rest protects data from unauthorized access. Option A is not customer responsibility, D is not scalable, E is AWS responsibility.
</details>

---

### Question 5

What does the “Principle of Least Privilege” refer to?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. You should grant your users only the permissions they need when they need them and nothing more.
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. All IAM users should have at least the necessary permissions to access the core AWS services.
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. All trusted IAM users should have access to any AWS service in the respective AWS account.
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. IAM users should not be granted any permissions; to keep your account safe.
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
<br><br>
> **Explanation:** The principle of least privilege is a security best practice that limits users' access rights to the minimum permissions they need to perform their work, reducing the risk of accidental or malicious misuse. Options B, C, D are contrary to this principle.
</details>

---

### Question 6

Hundreds of thousands of DDoS attacks are recorded every month worldwide. What service does AWS provide to help protect AWS Customers from these attacks? (Choose TWO)
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Shield.
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Config.
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon Cognito.
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. AWS WAF.
<br>&nbsp;&nbsp;&nbsp;&nbsp;E. AWS KMS.
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A, D
<br><br>
> **Explanation:** AWS Shield provides managed DDoS protection, and AWS WAF is a web application firewall that helps protect against common web exploits like SQL injection and cross-site scripting, which can lead to DDoS. Config is for configuration, Cognito for authentication, KMS for encryption.
</details>

---

### Question 7

A company has moved to AWS recently. Which of the following AWS Services will help ensure that they have the proper security settings? (Choose TWO)
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Trusted Advisor.
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon Inspector.
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon SNS.
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon CloudWatch.
<br>&nbsp;&nbsp;&nbsp;&nbsp;E. Concierge Support Team.
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A, B
<br><br>
> **Explanation:** Trusted Advisor checks for best practices in security, and Amazon Inspector assesses applications for vulnerabilities and deviations from best practices. SNS is for notifications, CloudWatch for monitoring, Concierge is for billing support in Enterprise plan.
</details>

---

### Question 8

What is the AWS feature that provides an additional level of security above the default authentication mechanism of usernames and passwords?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Encrypted keys.
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Email verification.
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. AWS KMS.
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. AWS MFA.
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** D
<br><br>
> **Explanation:** AWS Multi-Factor Authentication (MFA) adds an extra layer by requiring a second authentication factor, like a code from a device, beyond username and password. Encrypted keys are for data, email verification is for account setup, KMS is for key management.
</details>

---

### Question 9

According to the AWS Shared responsibility model, which of the following are the responsibility of the customer? (Choose TWO)
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Managing environmental events of AWS data centers.
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Protecting the confidentiality of data in transit in Amazon S3.
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Controlling physical access to AWS Regions.
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Ensuring that the underlying EC2 host is configured properly.
<br>&nbsp;&nbsp;&nbsp;&nbsp;E. Patching applications installed on Amazon EC2.
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** B, E
<br><br>
> **Explanation:** Customers are responsible for data security in transit and patching applications on EC2. Option A and C are AWS responsibilities, D is AWS for the host, customer for the guest OS.
</details>

---

### Question 10

Which of the following helps a customer view the Amazon EC2 billing activity for the past month?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Budgets.
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Pricing Calculator.
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Systems Manager.
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Cost & Usage Reports.
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** D
<br><br>
> **Explanation:** AWS Cost & Usage Reports provide comprehensive billing data including EC2 usage for the past month, delivered to S3. Budgets is for alerts, Pricing Calculator for estimates, Systems Manager for operations.
</details>

---

### Question 11

Your company wants to ensure that all EC2 instances are launched from approved AMIs only. Which service helps accomplish this?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Config
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Trusted Advisor
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon Inspector
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Systems Manager
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
<br><br>
> **Explanation:** AWS Config can track resource configurations and ensure EC2 instances use approved AMIs through conformance packs and rules. Trusted Advisor provides recommendations, Inspector scans for vulnerabilities, Systems Manager manages instances but doesn't enforce AMI policies.
</details>

---

### Question 12

Which AWS service helps you identify which users have made configuration changes to your AWS resources?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Config
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. AWS CloudTrail
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon CloudWatch
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Trusted Advisor
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** B
<br><br>
> **Explanation:** AWS CloudTrail records API calls including who made configuration changes. Config records configuration states but not who made changes, CloudWatch monitors metrics/logs, Trusted Advisor provides recommendations.
</details>

---

### Question 13

A company needs to encrypt data at rest in S3 buckets. Which service should they use?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. AWS KMS
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Certificate Manager
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Secrets Manager
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. AWS IAM
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
<br><br>
> **Explanation:** AWS Key Management Service (KMS) provides keys for encrypting data at rest in S3. Certificate Manager is for SSL/TLS, Secrets Manager for credentials, IAM for access control.
</details>

---

### Question 14

What is the PRIMARY benefit of using AWS Shield Standard?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Web application firewall
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. DDoS protection
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Encryption at rest
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Vulnerability scanning
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** B
<br><br>
> **Explanation:** AWS Shield Standard provides always-on DDoS protection at no additional charge for all AWS customers. WAF is separate, encryption is KMS, scanning is Inspector.
</details>

---

### Question 15

Which service helps you assess whether your AWS environment complies with security best practices?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Trusted Advisor
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon Inspector
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Config
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. AWS CloudTrail
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
<br><br>
> **Explanation:** AWS Trusted Advisor provides real-time guidance across security best practices. Inspector assesses vulnerabilities, Config tracks compliance, CloudTrail logs activity.
</details>

---

### Question 16

Which of the following is the customer's responsibility under the AWS Shared Responsibility Model?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Patching underlying infrastructure
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Physical security of data centers
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Configuring server-side encryption on S3
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Managing network infrastructure
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** C
<br><br>
> **Explanation:** Customers are responsible for data encryption, while AWS handles infrastructure.
</details>

---

### Question 17
Which AWS service provides a virtual private network connection to the AWS cloud?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Direct Connect
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. AWS VPN
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon Connect
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Global Accelerator
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** B
<br><br>
> **Explanation:** AWS VPN provides secure IPSec VPN connections from on-premises to AWS.
</details>

---

### Question 18

What is an IAM policy?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. JSON document defining permissions
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. User authentication method
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Role assumption process
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Group membership list
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
<br><br>
> **Explanation:** IAM policies are JSON documents that define access permissions for users, groups, and roles.
</details>

---

### Question 19

Which service monitors for malicious activity in AWS accounts?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon GuardDuty
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Shield
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon Inspector
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. AWS WAF
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
<br><br>
> **Explanation:** GuardDuty uses ML to analyze logs for threats like reconnaissance or crypto mining.
</details>

---

### Question 20

What is the recommended way to secure the AWS root account?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Enable MFA and avoid access keys
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Use for daily operations
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Share credentials with admins
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Create multiple root users
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
<br><br>
> **Explanation:** Root account should have MFA and no access keys; use IAM for daily tasks.
</details>

---

### Question 21

Which service provides centralized key management?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. AWS KMS
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Secrets Manager
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Certificate Manager
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. AWS IAM
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
<br><br>
> **Explanation:** KMS manages encryption keys for data at rest and in transit.
</details>

---

### Question 22

What is AWS Artifact used for?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Compliance reports
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Cost reports
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Usage reports
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Performance reports
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
<br><br>
> **Explanation:** Artifact provides on-demand access to AWS compliance documentation.
</details>

---

### Question 23

Which IAM best practice should be followed?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Use groups for permissions
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Attach policies to users directly
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Use root for all tasks
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Share access keys
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
<br><br>
> **Explanation:** Groups simplify permission management by assigning policies to groups.
</details>

---

### Question 24

What is Amazon Macie?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Data classification and protection
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Vulnerability scanner
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Firewall service
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Logging service
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
<br><br>
> **Explanation:** Macie discovers and protects sensitive data in S3 using ML.
</details>

---

### Question 25

Which service provides automated vulnerability management for EC2?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon Inspector
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. AWS GuardDuty
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Config
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Shield
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
<br><br>
> **Explanation:** Inspector assesses EC2 and Lambda for vulnerabilities and deviations.
</details>

---

### Question 26

What is the function of security groups in VPC?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Stateful firewall for instances
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Stateless firewall for subnets
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Encryption for traffic
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Routing tables
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
<br><br>
> **Explanation:** Security groups act as stateful firewalls at the instance level.
</details>

---

### Question 27

What is a NACL?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Stateless firewall for subnets
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Stateful firewall for instances
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Key management service
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. User authentication
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
<br><br>
> **Explanation:** Network ACLs are stateless firewalls at the subnet level.
</details>

---

### Question 28

Which service provides secrets storage?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Secrets Manager
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. AWS KMS
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Parameter Store
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Both A and C
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** D
<br><br>
> **Explanation:** Secrets Manager and Parameter Store (in Systems Manager) store secrets securely.
</details>

---

### Question 29

What is AWS Cognito?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. User authentication service
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Encryption service
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Monitoring service
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Database service
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
<br><br>
> **Explanation:** Cognito provides user sign-up, sign-in, and access control for apps.
</details>

---

### Question 30

Which compliance program does AWS support?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. HIPAA
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. PCI DSS
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. SOC 2
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. All of the above
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** D
<br><br>
> **Explanation:** AWS supports multiple compliance certifications including HIPAA, PCI, SOC.
</details>

---

### Question 31

What is the AWS Abuse team for?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Reporting misuse of AWS resources
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Billing inquiries
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Technical support
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Compliance audits
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
<br><br>
> **Explanation:** Report abuse like spam or malware to the AWS Abuse team.
</details>

---

### Question 32

Which IAM entity should be used for temporary access?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Users
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Groups
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Roles
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Policies
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** C
<br><br>
> **Explanation:** IAM roles provide temporary access without long-term credentials.
</details>

---

### Question 33

What is AWS Directory Service?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Managed Active Directory
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. User management
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Both A and B
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Encryption service
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** C
<br><br>
> **Explanation:** Directory Service provides managed Microsoft AD or Simple AD.
</details>

---

### Question 34

Which service provides DDoS protection at Layer 7?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Shield Advanced
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. AWS WAF
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon GuardDuty
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Firewall Manager
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** B
<br><br>
> **Explanation:** WAF protects against Layer 7 attacks like SQL injection.
</details>

---

### Question 35

What is the default encryption for S3?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. SSE-S3
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. SSE-KMS
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. SSE-C
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. None
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** D
<br><br>
> **Explanation:** S3 does not encrypt by default; you must enable SSE.
</details>

---

### Question 36

Which tool checks for public S3 buckets?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Trusted Advisor
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon Inspector
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Config
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon Macie
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
<br><br>
> **Explanation:** Trusted Advisor checks for unrestricted S3 bucket access.
</details>

---

### Question 37

What is AWS Firewall Manager?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Central management for WAF rules
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Network firewall
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Host firewall
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. VPN manager
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
<br><br>
> **Explanation:** Firewall Manager centralizes WAF, Shield, and security groups across accounts.
</details>

---

### Question 38

Which service provides SSL/TLS certificates?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Certificate Manager
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. AWS KMS
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Secrets Manager
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. AWS IAM
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
<br><br>
> **Explanation:** ACM provisions and manages SSL/TLS certificates for AWS services.
</details>

---

### Question 39

What is the purpose of VPC flow logs?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Monitor network traffic
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Audit API calls
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Encrypt data
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Manage users
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
<br><br>
> **Explanation:** VPC flow logs capture IP traffic information for troubleshooting.
</details>

---

### Question 40

Which compliance standard is for payment card data?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. PCI DSS
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. HIPAA
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. GDPR
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. SOC 1
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
<br><br>
> **Explanation:** PCI DSS is for handling credit card information securely.
</details>

---

### Question 41

What is Amazon GuardDuty's data source?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. VPC Flow Logs
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. CloudTrail logs
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. DNS logs
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. All of the above
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** D
<br><br>
> **Explanation:** GuardDuty analyzes multiple logs for threat detection.
</details>

---

### Question 42

Which IAM feature allows cross-account access?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Roles
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Policies
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Groups
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Users
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
<br><br>
> **Explanation:** Roles can be assumed by users from other accounts for cross-account access.
</details>

---

### Question 43

What is AWS Security Hub?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Centralized security findings
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Vulnerability scanner
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Firewall
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Encryption tool
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
<br><br>
> **Explanation:** Security Hub aggregates findings from various AWS security services.
</details>

---

### Question 44

Which service provides automated code reviews for security?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon CodeGuru
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon Inspector
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. AWS CodePipeline
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. AWS CodeBuild
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
<br><br>
> **Explanation:** CodeGuru Reviewer detects security vulnerabilities in code.
</details>

---

### Question 45

What is the difference between security groups and NACLs?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. SG stateful, NACL stateless
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. SG at subnet, NACL at instance
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. SG deny rules, NACL allow only
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. SG for outbound, NACL for inbound
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
<br><br>
> **Explanation:** Security groups are stateful (response traffic allowed), NACLs are stateless (explicit rules needed).
</details>

---

### Question 46

Which KMS key type is customer-managed?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. AWS-owned
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. AWS-managed
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Customer managed keys (CMK)
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Data keys
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** C
<br><br>
> **Explanation:** CMKs are created and managed by customers in KMS.
</details>

---

### Question 47

What is AWS SSO?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Single Sign-On for AWS accounts
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. User authentication
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Role assumption
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Directory service
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
<br><br>
> **Explanation:** AWS SSO (now IAM Identity Center) provides central access to multiple accounts and apps.
</details>

---

### Question 48

Which service detects PII in S3?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon Macie
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon GuardDuty
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Security Hub
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Config
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
<br><br>
> **Explanation:** Macie classifies sensitive data like PII using ML.
</details>

---

### Question 49

What is the root user in AWS?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Account owner with full access
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. IAM admin user
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Billing user
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Support user
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
<br><br>
> **Explanation:** The root user has complete access and should be secured with MFA.
</details>

---

### Question 50

Which policy type restricts resource actions?
<br>&nbsp;&nbsp;&nbsp;&nbsp;A. Permissions boundary
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. SCP in Organizations
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Session policy
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. All of the above
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** D
<br><br>
> **Explanation:** These policies limit permissions in different contexts.
</details>

---

