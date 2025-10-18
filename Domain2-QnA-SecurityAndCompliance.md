# Security and Compliance

**Total Questions: 50**  

---

### Question 1
You have noticed that several critical Amazon EC2 instances have been terminated. Which of the following AWS services would help you determine who took this action?
&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon Inspector.
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS CloudTrail.
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Trusted Advisor.
&nbsp;&nbsp;&nbsp;&nbsp;D. EC2 Instance Usage Report.
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** B
> **Explanation:** AWS CloudTrail logs all API calls and actions in your AWS account, allowing you to track who terminated the instances by reviewing the event history. Amazon Inspector is for vulnerability assessment, Trusted Advisor for optimization, and EC2 Usage Report for billing info.
</details>

---

### Question 2
Which statement is true regarding the AWS Shared Responsibility Model?
&nbsp;&nbsp;&nbsp;&nbsp;A. Responsibilities vary depending on the services used.
&nbsp;&nbsp;&nbsp;&nbsp;B. Security of the IaaS services is the responsibility of AWS.
&nbsp;&nbsp;&nbsp;&nbsp;C. Patching the guest OS is always the responsibility of AWS.
&nbsp;&nbsp;&nbsp;&nbsp;D. Security of the managed services is the responsibility of the customer.
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
> **Explanation:** The shared responsibility model defines that AWS manages security of the cloud (hardware, infrastructure), while customers manage security in the cloud (data, applications). Responsibilities vary by service; for example, in EC2 (IaaS), customers patch the OS, but in RDS (managed), AWS does. Option B is true for IaaS, but not complete; C is false for EC2; D is false, AWS handles managed services security.
</details>

---

### Question 3
An organization has a large number of technical employees who operate their AWS Cloud infrastructure. What does AWS provide to help organize them into teams and then assign the appropriate permissions for each team?
&nbsp;&nbsp;&nbsp;&nbsp;A. IAM roles.
&nbsp;&nbsp;&nbsp;&nbsp;B. IAM users.
&nbsp;&nbsp;&nbsp;&nbsp;C. IAM user groups.
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Organizations.
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** C
> **Explanation:** IAM user groups allow grouping users and assigning permissions via policies to the group, simplifying management for teams. Roles are for temporary access, users are individual accounts, Organizations is for multi-account management.
</details>

---

### Question 4
What should you do in order to keep the data on EBS volumes safe? (Choose TWO)
&nbsp;&nbsp;&nbsp;&nbsp;A. Regularly update firmware on EBS devices.
&nbsp;&nbsp;&nbsp;&nbsp;B. Create EBS snapshots.
&nbsp;&nbsp;&nbsp;&nbsp;C. Ensure that EBS data is encrypted at rest.
&nbsp;&nbsp;&nbsp;&nbsp;D. Store a backup daily in an external drive.
&nbsp;&nbsp;&nbsp;&nbsp;E. Prevent any unauthorized access to AWS data centers.
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** B, C
> **Explanation:** EBS snapshots provide point-in-time backups for data recovery, and encryption at rest protects data from unauthorized access. Option A is not customer responsibility, D is not scalable, E is AWS responsibility.
</details>

---

### Question 5
What does the “Principle of Least Privilege” refer to?
&nbsp;&nbsp;&nbsp;&nbsp;A. You should grant your users only the permissions they need when they need them and nothing more.
&nbsp;&nbsp;&nbsp;&nbsp;B. All IAM users should have at least the necessary permissions to access the core AWS services.
&nbsp;&nbsp;&nbsp;&nbsp;C. All trusted IAM users should have access to any AWS service in the respective AWS account.
&nbsp;&nbsp;&nbsp;&nbsp;D. IAM users should not be granted any permissions; to keep your account safe.
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
> **Explanation:** The principle of least privilege is a security best practice that limits users' access rights to the minimum permissions they need to perform their work, reducing the risk of accidental or malicious misuse. Options B, C, D are contrary to this principle.
</details>

---

### Question 6
Hundreds of thousands of DDoS attacks are recorded every month worldwide. What service does AWS provide to help protect AWS Customers from these attacks? (Choose TWO)
&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Shield.
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Config.
&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon Cognito.
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS WAF.
&nbsp;&nbsp;&nbsp;&nbsp;E. AWS KMS.
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A, D
> **Explanation:** AWS Shield provides managed DDoS protection, and AWS WAF is a web application firewall that helps protect against common web exploits like SQL injection and cross-site scripting, which can lead to DDoS. Config is for configuration, Cognito for authentication, KMS for encryption.
</details>

---

### Question 7
A company has moved to AWS recently. Which of the following AWS Services will help ensure that they have the proper security settings? (Choose TWO)
&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Trusted Advisor.
&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon Inspector.
&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon SNS.
&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon CloudWatch.
&nbsp;&nbsp;&nbsp;&nbsp;E. Concierge Support Team.
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A, B
> **Explanation:** Trusted Advisor checks for best practices in security, and Amazon Inspector assesses applications for vulnerabilities and deviations from best practices. SNS is for notifications, CloudWatch for monitoring, Concierge is for billing support in Enterprise plan.
</details>

---

### Question 8
What is the AWS feature that provides an additional level of security above the default authentication mechanism of usernames and passwords?
&nbsp;&nbsp;&nbsp;&nbsp;A. Encrypted keys.
&nbsp;&nbsp;&nbsp;&nbsp;B. Email verification.
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS KMS.
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS MFA.
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** D
> **Explanation:** AWS Multi-Factor Authentication (MFA) adds an extra layer by requiring a second authentication factor, like a code from a device, beyond username and password. Encrypted keys are for data, email verification is for account setup, KMS is for key management.
</details>

---

### Question 9
According to the AWS Shared responsibility model, which of the following are the responsibility of the customer? (Choose TWO)
&nbsp;&nbsp;&nbsp;&nbsp;A. Managing environmental events of AWS data centers.
&nbsp;&nbsp;&nbsp;&nbsp;B. Protecting the confidentiality of data in transit in Amazon S3.
&nbsp;&nbsp;&nbsp;&nbsp;C. Controlling physical access to AWS Regions.
&nbsp;&nbsp;&nbsp;&nbsp;D. Ensuring that the underlying EC2 host is configured properly.
&nbsp;&nbsp;&nbsp;&nbsp;E. Patching applications installed on Amazon EC2.
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** B, E
> **Explanation:** Customers are responsible for data security in transit and patching applications on EC2. Option A and C are AWS responsibilities, D is AWS for the host, customer for the guest OS.
</details>

---

### Question 10
Which of the following helps a customer view the Amazon EC2 billing activity for the past month?
&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Budgets.
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Pricing Calculator.
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Systems Manager.
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Cost & Usage Reports.
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** D
> **Explanation:** AWS Cost & Usage Reports provide comprehensive billing data including EC2 usage for the past month, delivered to S3. Budgets is for alerts, Pricing Calculator for estimates, Systems Manager for operations.
</details>

---

### Question 11
Your company wants to ensure that all EC2 instances are launched from approved AMIs only. Which service helps accomplish this?
&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Config
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Trusted Advisor
&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon Inspector
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Systems Manager
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
> **Explanation:** AWS Config can track resource configurations and ensure EC2 instances use approved AMIs through conformance packs and rules. Trusted Advisor provides recommendations, Inspector scans for vulnerabilities, Systems Manager manages instances but doesn't enforce AMI policies.
</details>

---

### Question 12
Which AWS service helps you identify which users have made configuration changes to your AWS resources?
&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Config
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS CloudTrail
&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon CloudWatch
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Trusted Advisor
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** B
> **Explanation:** AWS CloudTrail records API calls including who made configuration changes. Config records configuration states but not who made changes, CloudWatch monitors metrics/logs, Trusted Advisor provides recommendations.
</details>

---

### Question 13
A company needs to encrypt data at rest in S3 buckets. Which service should they use?
&nbsp;&nbsp;&nbsp;&nbsp;A. AWS KMS
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Certificate Manager
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Secrets Manager
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS IAM
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
> **Explanation:** AWS Key Management Service (KMS) provides keys for encrypting data at rest in S3. Certificate Manager is for SSL/TLS, Secrets Manager for credentials, IAM for access control.
</details>

---

### Question 14
What is the PRIMARY benefit of using AWS Shield Standard?
&nbsp;&nbsp;&nbsp;&nbsp;A. Web application firewall
&nbsp;&nbsp;&nbsp;&nbsp;B. DDoS protection
&nbsp;&nbsp;&nbsp;&nbsp;C. Encryption at rest
&nbsp;&nbsp;&nbsp;&nbsp;D. Vulnerability scanning
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** B
> **Explanation:** AWS Shield Standard provides always-on DDoS protection at no additional charge for all AWS customers. WAF is separate, encryption is KMS, scanning is Inspector.
</details>

---

### Question 15
Which service helps you assess whether your AWS environment complies with security best practices?
&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Trusted Advisor
&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon Inspector
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Config
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS CloudTrail
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
> **Explanation:** AWS Trusted Advisor provides real-time guidance across security best practices. Inspector assesses vulnerabilities, Config tracks compliance, CloudTrail logs activity.
</details>

---

### Question 16
Which of the following is the customer's responsibility under the AWS Shared Responsibility Model?
&nbsp;&nbsp;&nbsp;&nbsp;A. Patching underlying infrastructure
&nbsp;&nbsp;&nbsp;&nbsp;B. Physical security of data centers
&nbsp;&nbsp;&nbsp;&nbsp;C. Configuring server-side encryption on S3
&nbsp;&nbsp;&nbsp;&nbsp;D. Managing network infrastructure
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** C
> **Explanation:** Customers are responsible for data encryption, while AWS handles infrastructure.
</details>

---

### Question 17
Which AWS service provides a virtual private network connection to the AWS cloud?
&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Direct Connect
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS VPN
&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon Connect
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Global Accelerator
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** B
> **Explanation:** AWS VPN provides secure IPSec VPN connections from on-premises to AWS.
</details>

---

### Question 18
What is an IAM policy?
&nbsp;&nbsp;&nbsp;&nbsp;A. JSON document defining permissions
&nbsp;&nbsp;&nbsp;&nbsp;B. User authentication method
&nbsp;&nbsp;&nbsp;&nbsp;C. Role assumption process
&nbsp;&nbsp;&nbsp;&nbsp;D. Group membership list
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
> **Explanation:** IAM policies are JSON documents that define access permissions for users, groups, and roles.
</details>

---

### Question 19
Which service monitors for malicious activity in AWS accounts?
&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon GuardDuty
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Shield
&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon Inspector
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS WAF
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
> **Explanation:** GuardDuty uses ML to analyze logs for threats like reconnaissance or crypto mining.
</details>

---

### Question 20
What is the recommended way to secure the AWS root account?
&nbsp;&nbsp;&nbsp;&nbsp;A. Enable MFA and avoid access keys
&nbsp;&nbsp;&nbsp;&nbsp;B. Use for daily operations
&nbsp;&nbsp;&nbsp;&nbsp;C. Share credentials with admins
&nbsp;&nbsp;&nbsp;&nbsp;D. Create multiple root users
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
> **Explanation:** Root account should have MFA and no access keys; use IAM for daily tasks.
</details>

---

### Question 21
Which service provides centralized key management?
&nbsp;&nbsp;&nbsp;&nbsp;A. AWS KMS
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Secrets Manager
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Certificate Manager
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS IAM
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
> **Explanation:** KMS manages encryption keys for data at rest and in transit.
</details>

---

### Question 22
What is AWS Artifact used for?
&nbsp;&nbsp;&nbsp;&nbsp;A. Compliance reports
&nbsp;&nbsp;&nbsp;&nbsp;B. Cost reports
&nbsp;&nbsp;&nbsp;&nbsp;C. Usage reports
&nbsp;&nbsp;&nbsp;&nbsp;D. Performance reports
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
> **Explanation:** Artifact provides on-demand access to AWS compliance documentation.
</details>

---

### Question 23
Which IAM best practice should be followed?
&nbsp;&nbsp;&nbsp;&nbsp;A. Use groups for permissions
&nbsp;&nbsp;&nbsp;&nbsp;B. Attach policies to users directly
&nbsp;&nbsp;&nbsp;&nbsp;C. Use root for all tasks
&nbsp;&nbsp;&nbsp;&nbsp;D. Share access keys
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
> **Explanation:** Groups simplify permission management by assigning policies to groups.
</details>

---

### Question 24
What is Amazon Macie?
&nbsp;&nbsp;&nbsp;&nbsp;A. Data classification and protection
&nbsp;&nbsp;&nbsp;&nbsp;B. Vulnerability scanner
&nbsp;&nbsp;&nbsp;&nbsp;C. Firewall service
&nbsp;&nbsp;&nbsp;&nbsp;D. Logging service
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
> **Explanation:** Macie discovers and protects sensitive data in S3 using ML.
</details>

---

### Question 25
Which service provides automated vulnerability management for EC2?
&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon Inspector
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS GuardDuty
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Config
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Shield
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
> **Explanation:** Inspector assesses EC2 and Lambda for vulnerabilities and deviations.
</details>

---

### Question 26
What is the function of security groups in VPC?
&nbsp;&nbsp;&nbsp;&nbsp;A. Stateful firewall for instances
&nbsp;&nbsp;&nbsp;&nbsp;B. Stateless firewall for subnets
&nbsp;&nbsp;&nbsp;&nbsp;C. Encryption for traffic
&nbsp;&nbsp;&nbsp;&nbsp;D. Routing tables
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
> **Explanation:** Security groups act as stateful firewalls at the instance level.
</details>

---

### Question 27
What is a NACL?
&nbsp;&nbsp;&nbsp;&nbsp;A. Stateless firewall for subnets
&nbsp;&nbsp;&nbsp;&nbsp;B. Stateful firewall for instances
&nbsp;&nbsp;&nbsp;&nbsp;C. Key management service
&nbsp;&nbsp;&nbsp;&nbsp;D. User authentication
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
> **Explanation:** Network ACLs are stateless firewalls at the subnet level.
</details>

---

### Question 28
Which service provides secrets storage?
&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Secrets Manager
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS KMS
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Parameter Store
&nbsp;&nbsp;&nbsp;&nbsp;D. Both A and C
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** D
> **Explanation:** Secrets Manager and Parameter Store (in Systems Manager) store secrets securely.
</details>

---

### Question 29
What is AWS Cognito?
&nbsp;&nbsp;&nbsp;&nbsp;A. User authentication service
&nbsp;&nbsp;&nbsp;&nbsp;B. Encryption service
&nbsp;&nbsp;&nbsp;&nbsp;C. Monitoring service
&nbsp;&nbsp;&nbsp;&nbsp;D. Database service
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
> **Explanation:** Cognito provides user sign-up, sign-in, and access control for apps.
</details>

---

### Question 30
Which compliance program does AWS support?
&nbsp;&nbsp;&nbsp;&nbsp;A. HIPAA
&nbsp;&nbsp;&nbsp;&nbsp;B. PCI DSS
&nbsp;&nbsp;&nbsp;&nbsp;C. SOC 2
&nbsp;&nbsp;&nbsp;&nbsp;D. All of the above
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** D
> **Explanation:** AWS supports multiple compliance certifications including HIPAA, PCI, SOC.
</details>

---

### Question 31
What is the AWS Abuse team for?
&nbsp;&nbsp;&nbsp;&nbsp;A. Reporting misuse of AWS resources
&nbsp;&nbsp;&nbsp;&nbsp;B. Billing inquiries
&nbsp;&nbsp;&nbsp;&nbsp;C. Technical support
&nbsp;&nbsp;&nbsp;&nbsp;D. Compliance audits
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
> **Explanation:** Report abuse like spam or malware to the AWS Abuse team.
</details>

---

### Question 32
Which IAM entity should be used for temporary access?
&nbsp;&nbsp;&nbsp;&nbsp;A. Users
&nbsp;&nbsp;&nbsp;&nbsp;B. Groups
&nbsp;&nbsp;&nbsp;&nbsp;C. Roles
&nbsp;&nbsp;&nbsp;&nbsp;D. Policies
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** C
> **Explanation:** IAM roles provide temporary access without long-term credentials.
</details>

---

### Question 33
What is AWS Directory Service?
&nbsp;&nbsp;&nbsp;&nbsp;A. Managed Active Directory
&nbsp;&nbsp;&nbsp;&nbsp;B. User management
&nbsp;&nbsp;&nbsp;&nbsp;C. Both A and B
&nbsp;&nbsp;&nbsp;&nbsp;D. Encryption service
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** C
> **Explanation:** Directory Service provides managed Microsoft AD or Simple AD.
</details>

---

### Question 34
Which service provides DDoS protection at Layer 7?
&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Shield Advanced
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS WAF
&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon GuardDuty
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Firewall Manager
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** B
> **Explanation:** WAF protects against Layer 7 attacks like SQL injection.
</details>

---

### Question 35
What is the default encryption for S3?
&nbsp;&nbsp;&nbsp;&nbsp;A. SSE-S3
&nbsp;&nbsp;&nbsp;&nbsp;B. SSE-KMS
&nbsp;&nbsp;&nbsp;&nbsp;C. SSE-C
&nbsp;&nbsp;&nbsp;&nbsp;D. None
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** D
> **Explanation:** S3 does not encrypt by default; you must enable SSE.
</details>

---

### Question 36
Which tool checks for public S3 buckets?
&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Trusted Advisor
&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon Inspector
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Config
&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon Macie
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
> **Explanation:** Trusted Advisor checks for unrestricted S3 bucket access.
</details>

---

### Question 37
What is AWS Firewall Manager?
&nbsp;&nbsp;&nbsp;&nbsp;A. Central management for WAF rules
&nbsp;&nbsp;&nbsp;&nbsp;B. Network firewall
&nbsp;&nbsp;&nbsp;&nbsp;C. Host firewall
&nbsp;&nbsp;&nbsp;&nbsp;D. VPN manager
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
> **Explanation:** Firewall Manager centralizes WAF, Shield, and security groups across accounts.
</details>

---

### Question 38
Which service provides SSL/TLS certificates?
&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Certificate Manager
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS KMS
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Secrets Manager
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS IAM
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
> **Explanation:** ACM provisions and manages SSL/TLS certificates for AWS services.
</details>

---

### Question 39
What is the purpose of VPC flow logs?
&nbsp;&nbsp;&nbsp;&nbsp;A. Monitor network traffic
&nbsp;&nbsp;&nbsp;&nbsp;B. Audit API calls
&nbsp;&nbsp;&nbsp;&nbsp;C. Encrypt data
&nbsp;&nbsp;&nbsp;&nbsp;D. Manage users
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
> **Explanation:** VPC flow logs capture IP traffic information for troubleshooting.
</details>

---

### Question 40
Which compliance standard is for payment card data?
&nbsp;&nbsp;&nbsp;&nbsp;A. PCI DSS
&nbsp;&nbsp;&nbsp;&nbsp;B. HIPAA
&nbsp;&nbsp;&nbsp;&nbsp;C. GDPR
&nbsp;&nbsp;&nbsp;&nbsp;D. SOC 1
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
> **Explanation:** PCI DSS is for handling credit card information securely.
</details>

---

### Question 41
What is Amazon GuardDuty's data source?
&nbsp;&nbsp;&nbsp;&nbsp;A. VPC Flow Logs
&nbsp;&nbsp;&nbsp;&nbsp;B. CloudTrail logs
&nbsp;&nbsp;&nbsp;&nbsp;C. DNS logs
&nbsp;&nbsp;&nbsp;&nbsp;D. All of the above
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** D
> **Explanation:** GuardDuty analyzes multiple logs for threat detection.
</details>

---

### Question 42
Which IAM feature allows cross-account access?
&nbsp;&nbsp;&nbsp;&nbsp;A. Roles
&nbsp;&nbsp;&nbsp;&nbsp;B. Policies
&nbsp;&nbsp;&nbsp;&nbsp;C. Groups
&nbsp;&nbsp;&nbsp;&nbsp;D. Users
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
> **Explanation:** Roles can be assumed by users from other accounts for cross-account access.
</details>

---

### Question 43
What is AWS Security Hub?
&nbsp;&nbsp;&nbsp;&nbsp;A. Centralized security findings
&nbsp;&nbsp;&nbsp;&nbsp;B. Vulnerability scanner
&nbsp;&nbsp;&nbsp;&nbsp;C. Firewall
&nbsp;&nbsp;&nbsp;&nbsp;D. Encryption tool
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
> **Explanation:** Security Hub aggregates findings from various AWS security services.
</details>

---

### Question 44
Which service provides automated code reviews for security?
&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon CodeGuru
&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon Inspector
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS CodePipeline
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS CodeBuild
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
> **Explanation:** CodeGuru Reviewer detects security vulnerabilities in code.
</details>

---

### Question 45
What is the difference between security groups and NACLs?
&nbsp;&nbsp;&nbsp;&nbsp;A. SG stateful, NACL stateless
&nbsp;&nbsp;&nbsp;&nbsp;B. SG at subnet, NACL at instance
&nbsp;&nbsp;&nbsp;&nbsp;C. SG deny rules, NACL allow only
&nbsp;&nbsp;&nbsp;&nbsp;D. SG for outbound, NACL for inbound
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
> **Explanation:** Security groups are stateful (response traffic allowed), NACLs are stateless (explicit rules needed).
</details>

---

### Question 46
Which KMS key type is customer-managed?
&nbsp;&nbsp;&nbsp;&nbsp;A. AWS-owned
&nbsp;&nbsp;&nbsp;&nbsp;B. AWS-managed
&nbsp;&nbsp;&nbsp;&nbsp;C. Customer managed keys (CMK)
&nbsp;&nbsp;&nbsp;&nbsp;D. Data keys
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** C
> **Explanation:** CMKs are created and managed by customers in KMS.
</details>

---

### Question 47
What is AWS SSO?
&nbsp;&nbsp;&nbsp;&nbsp;A. Single Sign-On for AWS accounts
&nbsp;&nbsp;&nbsp;&nbsp;B. User authentication
&nbsp;&nbsp;&nbsp;&nbsp;C. Role assumption
&nbsp;&nbsp;&nbsp;&nbsp;D. Directory service
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
> **Explanation:** AWS SSO (now IAM Identity Center) provides central access to multiple accounts and apps.
</details>

---

### Question 48
Which service detects PII in S3?
&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon Macie
&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon GuardDuty
&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Security Hub
&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Config
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
> **Explanation:** Macie classifies sensitive data like PII using ML.
</details>

---

### Question 49
What is the root user in AWS?
&nbsp;&nbsp;&nbsp;&nbsp;A. Account owner with full access
&nbsp;&nbsp;&nbsp;&nbsp;B. IAM admin user
&nbsp;&nbsp;&nbsp;&nbsp;C. Billing user
&nbsp;&nbsp;&nbsp;&nbsp;D. Support user
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** A
> **Explanation:** The root user has complete access and should be secured with MFA.
</details>

---

### Question 50
Which policy type restricts resource actions?
&nbsp;&nbsp;&nbsp;&nbsp;A. Permissions boundary
&nbsp;&nbsp;&nbsp;&nbsp;B. SCP in Organizations
&nbsp;&nbsp;&nbsp;&nbsp;C. Session policy
&nbsp;&nbsp;&nbsp;&nbsp;D. All of the above
<details><summary>Click to reveal answer.</summary>
<br>
**Correct Answer:** D
> **Explanation:** These policies limit permissions in different contexts.
</details>

---

