# Domain 4 - Billing, Pricing, and Support

**Total Questions: 132** 

---

### Question 1

You have set up consolidated billing for several AWS accounts. One of the accounts has purchased a number of reserved instances for 3 years. Which of the following is true regarding this scenario?

&nbsp;&nbsp;&nbsp;&nbsp;A. The Reserved Instance discounts can only be shared with the master account.
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. All accounts can receive the hourly cost benefit of the Reserved Instances.
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. The purchased instances will have better performance than On-demand instances.
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. There are no cost benefits from using consolidated billing; It is for informational purposes only.
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** With consolidated billing in AWS Organizations, Reserved Instance discounts are shared across all accounts in the organization, providing cost savings. Performance is the same as On-Demand, and consolidated billing does provide cost benefits through volume discounts.
</details>

---

### Question 2

A company has an AWS Enterprise Support plan. They want quick and efficient guidance with their billing and account inquiries. Which of the following should the company use?

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Health Dashboard.
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Support Concierge.
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Customer Service.
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Operations Support.
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** The Support Concierge is part of Enterprise Support for billing and account inquiries. Health Dashboard is for service health, Customer Service is general, Operations Support is not a service.
</details>

---

### Question 3

What do you gain from setting up consolidated billing for five different AWS accounts under another master account?

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS services' costs will be reduced to half the original price.
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. The consolidated billing feature is just for organizational purpose.
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Each AWS account gets volume discounts.
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Each AWS account gets five times the free-tier services capacity.
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Consolidated billing aggregates usage for volume discounts and shared free tier. No halving costs, it's more than organizational, free tier isn't multiplied.
</details>

---

### Question 4

A startup company is operating on limited funds and is extremely concerned about cost overruns. Which of the below options can be used to notify the company when their monthly AWS bill exceeds $2000?
 (Choose TWO)
&nbsp;&nbsp;&nbsp;&nbsp;A. Setup a CloudWatch billing alarm that triggers an SNS notification when the threshold is exceeded.
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Configure the Amazon Simple Email Service to send billing alerts to their email address on a daily basis.
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Configure the AWS Budgets Service to alert the company when the threshold is exceeded.
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Configure AWS CloudTrail to automatically delete all AWS resources when the threshold is exceeded.
<br>&nbsp;&nbsp;&nbsp;&nbsp;E. Configure the Amazon Connect Service to alert the company when the threshold is exceeded.
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A, C
> **Explanation:** CloudWatch billing alarms and AWS Budgets both can monitor costs and notify via SNS or email when thresholds are exceeded. SES is for sending emails but not billing alerts, CloudTrail is for logging, Connect is for contact centers.
</details>

---

### Question 5

You want to run a questionnaire application for only one day (without interruption), which Amazon EC2 purchase option should you use?

&nbsp;&nbsp;&nbsp;&nbsp;A. Reserved instances.
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Spot instances.
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Dedicated instances.
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. On-demand instances.
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** On-demand instances are ideal for short-term, uninterrupted workloads with no long-term commitment. Reserved are for long-term, Spot for interruptible, Dedicated for dedicated hardware.
</details>

---

### Question 6

You are working on a project that involves creating thumbnails of millions of images. Consistent uptime is not an issue, and continuous processing is not required. Which EC2 buying option would be the most cost-effective?

&nbsp;&nbsp;&nbsp;&nbsp;A. Reserved Instances.
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. On-demand Instances.
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Dedicated Instances.
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Spot Instances.
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** Spot Instances offer significant savings for interruptible workloads like batch processing. Reserved are for steady state, On-demand for general, Dedicated for compliance.
</details>

---

### Question 7

Which of the following is NOT correct regarding Amazon EC2 On-demand instances?

&nbsp;&nbsp;&nbsp;&nbsp;A. You have to pay a start-up fee when launching a new instance for the first time.
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. The on-demand instances follow the AWS pay-as-you-go pricing model.
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. With on-demand instances, no longer-term commitments or upfront payments are needed.
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. When using on-demand Linux instances, you are charged per second based on an hourly rate.
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** There is no start-up fee for On-demand instances; you pay only for the seconds or hours used. The rest are correct: pay-as-you-go, no commitments, per-second billing for Linux.
</details>

---

### Question 8

A company is introducing a new product to their customers, and is expecting a surge in traffic to their web application. As part of their Enterprise Support plan, which of the following provides the company with architectural and scaling guidance?

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Knowledge Center.
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Health Dashboard.
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Infrastructure Event Management.
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Support Concierge Service.
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Infrastructure Event Management in Enterprise Support provides architecture and scaling guidance for events like product launches. Knowledge Center is docs, Health Dashboard for service status, Concierge for billing.
</details>

---

### Question 9

Which of the following EC2 instance purchasing options supports the Bring Your Own License (BYOL) model for almost every BYOL scenario?

&nbsp;&nbsp;&nbsp;&nbsp;A. Dedicated Instances.
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Dedicated Hosts.
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. On-demand Instances.
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Reserved Instances.
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Dedicated Hosts allow BYOL by providing dedicated physical servers, complying with per-socket or per-core licensing. Dedicated Instances are dedicated tenancy but not physical host visibility.
</details>

---

### Question 10

A company is migrating an application that is running non-interruptible workloads for a three-year time frame. Which pricing construct would provide the MOST cost-effective solution?

&nbsp;&nbsp;&nbsp;&nbsp;A. Amazon EC2 Spot Instances.
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Amazon EC2 Dedicated Instances.
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Amazon EC2 On-Demand Instances.
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Amazon EC2 Reserved Instances.
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** Reserved Instances offer significant savings for long-term, steady workloads with 1- or 3-year commitments. Spot is interruptible, Dedicated for compliance, On-Demand for flexibility but higher cost.
</details>

---

### Question 11

Which AWS support plan provides access to a dedicated Technical Account Manager?

&nbsp;&nbsp;&nbsp;&nbsp;A. Basic Support
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Developer Support
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Business Support
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Enterprise Support
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** Enterprise Support includes a dedicated Technical Account Manager (TAM) for proactive guidance. Basic is community, Developer/Business have support but no dedicated TAM.
</details>

---

### Question 12

What is the BEST tool to estimate monthly AWS costs before deployment?

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Cost Explorer
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Pricing Calculator
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Budgets
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Trusted Advisor
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** AWS Pricing Calculator estimates costs for planned architectures. Cost Explorer analyzes historical data, Budgets sets alerts, Trusted Advisor provides optimization recommendations.
</details>

---

### Question 13

A company wants to save 75% on EC2 costs for interruptible batch processing. Which option should they choose?

&nbsp;&nbsp;&nbsp;&nbsp;A. Reserved Instances
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. On-Demand Instances
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Spot Instances
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Savings Plans
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Spot Instances offer up to 90% savings for interruptible workloads. Reserved/Savings Plans require commitment, On-Demand is full price.
</details>

---

### Question 14

Which service provides detailed cost and usage reports delivered to S3?

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Budgets
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Cost Explorer
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Cost & Usage Reports
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. AWS Pricing Calculator
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Cost & Usage Reports provide comprehensive CSV reports to S3. Budgets is alerts, Cost Explorer is visualization, Calculator is estimates.
</details>

---

### Question 15

What benefit does the AWS Free Tier provide?

&nbsp;&nbsp;&nbsp;&nbsp;A. Free Enterprise Support
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Always free services
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. 12 months free usage limits
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. All of the above
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Free Tier offers 12 months of limited free usage for 20+ services, plus always free offers. Support is paid, not all services free.
</details>

---

### Question 16

Which EC2 pricing model offers up to 90% discount compared to On-Demand?

&nbsp;&nbsp;&nbsp;&nbsp;A. Reserved Instances
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Savings Plans
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Spot Instances
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Dedicated Hosts
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Spot Instances provide up to 90% discount for interruptible workloads, determined by supply/demand.
</details>

---

### Question 17

What is the maximum discount for 3-year Reserved Instances with All Upfront payment?

&nbsp;&nbsp;&nbsp;&nbsp;A. 40%
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. 55%
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. 72%
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. 75%
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** 3-year RIs with All Upfront offer up to 75% discount vs On-Demand.
</details>

---

### Question 18

Which tool provides recommendations to reduce costs?

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Cost Explorer
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Trusted Advisor
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. AWS Budgets
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. All of the above
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** All provide cost optimization: Explorer for analysis, Trusted Advisor for recommendations, Budgets for alerts.
</details>

---

### Question 19

What is AWS Savings Plans?

&nbsp;&nbsp;&nbsp;&nbsp;A. Flexible commitment across EC2, Lambda, Fargate
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Only for EC2 Reserved Instances
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Spot Instance replacement
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Free tier extension
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Savings Plans offer 66-72% savings with flexible compute usage across services.
</details>

---

### Question 20

Which support plan includes Infrastructure Event Management?

&nbsp;&nbsp;&nbsp;&nbsp;A. Developer
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Business
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Enterprise On-Ramp
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Enterprise
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** Infrastructure Event Management is exclusive to Enterprise Support for major events.
</details>

---

### Question 21

What is the billing increment for Windows EC2 instances?

&nbsp;&nbsp;&nbsp;&nbsp;A. Per second
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Per minute
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Per hour
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Per month
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Windows instances are billed per hour, while Linux is per second.
</details>

---

### Question 22

Which service helps track costs by tags?

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Cost Explorer
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Budgets
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Cost & Usage Reports
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. All of the above
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** All support cost allocation tagging for tracking by project/team.
</details>

---

### Question 23

What is the AWS Free Tier limit for S3 storage?

&nbsp;&nbsp;&nbsp;&nbsp;A. 5 GB Standard
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. 10 GB Standard
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. 20 GB Standard
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Unlimited
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Free Tier includes 5 GB Standard storage, 20,000 GET, 2,000 PUT requests.
</details>

---

### Question 24

Which pricing model requires no upfront payment?

&nbsp;&nbsp;&nbsp;&nbsp;A. Reserved Instances (All Upfront)
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Reserved Instances (No Upfront)
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Savings Plans (Partial Upfront)
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Spot Instances
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** Spot Instances require no upfront payment; pay only while running.
</details>

---

### Question 25

What is AWS Support Concierge?

&nbsp;&nbsp;&nbsp;&nbsp;A. Billing/account guidance for Enterprise
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Technical TAM
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. 24/7 phone support
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Developer forums
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Concierge provides billing optimization and account guidance for Enterprise customers.
</details>

---

### Question 26

Which tool compares on-premises vs AWS costs?

&nbsp;&nbsp;&nbsp;&nbsp;A. Pricing Calculator
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. TCO Calculator
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Cost Explorer
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Budgets
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Total Cost of Ownership Calculator estimates 5-year savings from AWS migration.
</details>

---

### Question 27

What is the minimum commitment for Compute Savings Plans?

&nbsp;&nbsp;&nbsp;&nbsp;A. 1 month
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. 1 year
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. 3 years
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. No minimum
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Compute Savings Plans require 1 or 3-year commitment for 66% savings.
</details>

---

### Question 28

Which service sends cost alerts via email?

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Budgets
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. CloudWatch Alarms
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Cost Explorer
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Both A and B
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** Budgets for budget alerts, CloudWatch for billing alarms via SNS.
</details>

---

### Question 29

What is the free tier for Lambda?

&nbsp;&nbsp;&nbsp;&nbsp;A. 1 million requests/month
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. 400,000 GB-seconds/month
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Both A and B
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Unlimited
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** 1M free requests + 400K GB-seconds of compute time monthly.
</details>

---

### Question 30

Which support plan has 24/7 phone/chat?

&nbsp;&nbsp;&nbsp;&nbsp;A. Basic
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Developer
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Business
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Enterprise
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Business and Enterprise have 24/7 phone/chat; Developer has business hours.
</details>

---

### Question 31

What is EC2 Instance Savings Plans?

&nbsp;&nbsp;&nbsp;&nbsp;A. Specific instance family commitment
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Any compute service
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Spot replacement
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Free tier
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Instance Savings Plans commit to specific instance family/Region/OS.
</details>

---

### Question 32

Which report provides line-item billing detail?

&nbsp;&nbsp;&nbsp;&nbsp;A. Monthly Bill
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Cost & Usage Reports
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Cost Explorer
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Budgets
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** CUR provides detailed CSV files with all line items to S3.
</details>

---

### Question 33

What is the discount for 1-year Reserved Instance (Partial Upfront)?

&nbsp;&nbsp;&nbsp;&nbsp;A. 40%
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. 50%
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. 60%
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. 72%
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** 1-year Partial Upfront RIs offer ~40% discount vs On-Demand.
</details>

---

### Question 34

Which plan includes Well-Architected reviews?

&nbsp;&nbsp;&nbsp;&nbsp;A. Business
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Enterprise On-Ramp
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Enterprise
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. All above
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** Business+ plans include Well-Architected Tool reviews.
</details>

---

### Question 35

What is AWS Cost Categories?

&nbsp;&nbsp;&nbsp;&nbsp;A. Group costs by custom dimensions
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Budget creation
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Alert system
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Report generator
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Cost Categories group costs beyond tags for custom reporting.
</details>

---

### Question 36

Which service stops unused resources to save costs?

&nbsp;&nbsp;&nbsp;&nbsp;A. AWS Instance Scheduler
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. AWS Budgets
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Cost Explorer
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Trusted Advisor
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Instance Scheduler automates EC2 start/stop for cost savings.
</details>

---

### Question 37

What is the free tier for EC2?

&nbsp;&nbsp;&nbsp;&nbsp;A. 750 hours t2.micro/month
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. 1000 hours t3.micro/month
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. 500 hours m5.large/month
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Unlimited
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** 750 hours t2.micro or t3.micro per month for 12 months.
</details>

---

### Question 38

Which provides 99.99% SLA for single AZ RDS?

&nbsp;&nbsp;&nbsp;&nbsp;A. Basic Support
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Business Support
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Enterprise Support
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. No SLA
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Business Support required for RDS single-AZ 99.99% SLA credits.
</details>

---

### Question 39

What is the discount range for SageMaker Savings Plans?

&nbsp;&nbsp;&nbsp;&nbsp;A. 20-40%
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. 50-64%
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. 66-72%
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Up to 90%
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** SageMaker Savings Plans offer 66-72% savings on training/inference.
</details>

---

### Question 40

Which tool forecasts future costs?

&nbsp;&nbsp;&nbsp;&nbsp;A. Cost Explorer
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Budgets
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Pricing Calculator
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. TCO Calculator
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Cost Explorer provides 12-month cost forecasts based on historical data.
</details>

---

### Question 41

What is the billing minimum for Spot Instances?

&nbsp;&nbsp;&nbsp;&nbsp;A. 1 minute
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. 1 second
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. 1 hour
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. No minimum
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Spot Instances billed per second with 1-minute minimum.
</details>

---

### Question 42

Which support plan has <15 min response time?

&nbsp;&nbsp;&nbsp;&nbsp;A. Developer
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Business
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Enterprise
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. All above
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Enterprise has <15 min response for critical severity issues.
</details>

---

### Question 43

What are Cost Allocation Tags?

&nbsp;&nbsp;&nbsp;&nbsp;A. Track costs by project/team
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Security tags
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Performance tags
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Compliance tags
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Cost Allocation Tags enable cost tracking by business dimensions in reports.
</details>

---

### Question 44

Which provides credits for SLA violations?

&nbsp;&nbsp;&nbsp;&nbsp;A. Basic Support
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Developer Support
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Business Support
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Enterprise Support
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Business and Enterprise Support include SLA credits for eligible services.
</details>

---

### Question 45

What is the free tier duration?

&nbsp;&nbsp;&nbsp;&nbsp;A. 6 months
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. 12 months
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. 24 months
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Lifetime
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** 12 months free tier + always-free tier services.
</details>

---

### Question 46

Which Reserved Instance payment option has highest discount?

&nbsp;&nbsp;&nbsp;&nbsp;A. No Upfront
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Partial Upfront
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. All Upfront
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Monthly
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** All Upfront payment provides maximum discount (up to 75%).
</details>

---

### Question 47

What is AWS Cost Anomaly Detection?

&nbsp;&nbsp;&nbsp;&nbsp;A. ML-based unusual spending alerts
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Budget alerts
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Forecast tool
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Report generator
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** ML detects billing anomalies and sends proactive alerts.
</details>

---

### Question 48

Which service auto-scales to minimize costs?

&nbsp;&nbsp;&nbsp;&nbsp;A. Auto Scaling
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Spot Fleet
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Savings Plans
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Reserved Instances
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Spot Fleet automatically diversifies Spot pools for cost optimization.
</details>

---

### Question 49

What is the Developer Support response time?

&nbsp;&nbsp;&nbsp;&nbsp;A. <24 hours
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. <12 hours
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. <1 hour
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. 24/7 instant
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Developer Support: <24 hours business hours only.
</details>

---

### Question 50

Which provides RI marketplace?

&nbsp;&nbsp;&nbsp;&nbsp;A. Sell unused RIs
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Buy used RIs
&nbsp>&nbsp;&nbsp;&nbsp;C. Both A and B
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. None
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** RI Marketplace allows buying/selling unused Reserved Instances.
</details>

---


### Question 51

What is the free tier limit for DynamoDB?

&nbsp;&nbsp;&nbsp;&nbsp;A. 25 GB storage
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. 200 million requests
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Both A and B
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Unlimited reads
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** 25 GB storage + 200M request units per month.
</details>

---

### Question 52

Which plan includes 3 Well-Architected reviews/year?

&nbsp;&nbsp;&nbsp;&nbsp;A. Business
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Enterprise On-Ramp
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Enterprise
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Developer
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Enterprise On-Ramp includes 3 reviews; Enterprise unlimited.
</details>

---

### Question 53

What is AWS Compute Optimizer?

&nbsp;&nbsp;&nbsp;&nbsp;A. Rightsizing recommendations
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Cost forecasts
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Budget alerts
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Tag manager
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** ML-based recommendations for optimal EC2 instance types.
</details>

---

### Question 54

Which has 99.99% S3 SLA?

&nbsp;&nbsp;&nbsp;&nbsp;A. All customers
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Business Support
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Enterprise Support
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Developer Support
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** S3 SLA is 99.99% for all customers regardless of support plan.
</details>

---

### Question 55

What is the minimum Spot bid price?

&nbsp;&nbsp;&nbsp;&nbsp;A. $0.01
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Current Spot price
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. On-Demand price
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. No minimum
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Spot requests fulfill at or below current Spot price.
</details>

---

### Question 56

Which service shows RI utilization?

&nbsp;&nbsp;&nbsp;&nbsp;A. Cost Explorer
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. RI Dashboard
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Budgets
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Trusted Advisor
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Cost Explorer RI Utilization report shows coverage and savings.
</details>

---

### Question 57

What is AWS Budgets action?

&nbsp;&nbsp;&nbsp;&nbsp;A. Apply IAM policies
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Stop EC2 instances
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Send notifications only
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Create budgets
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Budget Actions can stop instances or apply IAM policies when thresholds hit.
</details>

---

### Question 58

Which has lowest effective cost for steady workloads?

&nbsp;&nbsp;&nbsp;&nbsp;A. On-Demand
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Spot
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. 1-year RI
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. 3-year RI All Upfront
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** 3-year All Upfront RI has lowest cost for predictable workloads.
</details>

---

### Question 59

What is Enterprise Support hourly rate?

&nbsp;&nbsp;&nbsp;&nbsp;A. Fixed monthly
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Usage-based
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. $0 for first $0-10K
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Per ticket
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Tiered pricing: free up to $10K spend, then % of monthly spend.
</details>

---

### Question 60

Which tracks Reserved Instance coverage?

&nbsp;&nbsp;&nbsp;&nbsp;A. Cost Explorer
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Budgets
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. CUR
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. All above
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** All can show RI coverage metrics.
</details>

---

### Question 61

What is the free tier for RDS?

&nbsp;&nbsp;&nbsp;&nbsp;A. 750 hours db.t2.micro
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. 20 GB storage
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. 20M I/O
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. All above
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** 750 hours + 20 GB + 20M I/O per month for 12 months.
</details>

---

### Question 62

Which plan includes TAM?

&nbsp;&nbsp;&nbsp;&nbsp;A. Business
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Developer
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Enterprise On-Ramp
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Enterprise
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** Only full Enterprise Support includes dedicated TAM.
</details>

---

### Question 63

What is Spot Block duration?

&nbsp;&nbsp;&nbsp;&nbsp;A. 1-6 hours
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Until interrupted
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. 24 hours
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. 1 month
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Spot Blocks guarantee capacity for 1-6 hours.
</details>

---

### Question 64

Which shows cost by service?

&nbsp;&nbsp;&nbsp;&nbsp;A. Monthly Bill PDF
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Cost Explorer
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Budgets
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Trusted Advisor
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Cost Explorer provides granular breakdowns by service/region.
</details>

---

### Question 65

What is the discount for EC2 3-year No Upfront RI?

&nbsp;&nbsp;&nbsp;&nbsp;A. 55%
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. 62%
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. 69%
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. 75%
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** 3-year No Upfront offers ~69% discount.
</details>

---

### Question 66

Which support case has <1 hour response?

&nbsp;&nbsp;&nbsp;&nbsp;A. Low
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Medium
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. High
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Enterprise only
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** Enterprise gets <1 hour for critical severity cases.
</details>

---

### Question 67

What is AWS Cost and Usage Report format?

&nbsp;&nbsp;&nbsp;&nbsp;A. PDF
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. CSV to S3
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Email
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Console dashboard
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Detailed CSV files delivered daily/hourly to S3 bucket.
</details>

---

### Question 68

Which free tier service has no limits?

&nbsp;&nbsp;&nbsp;&nbsp;A. S3
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Lambda
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. DynamoDB
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. None
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** All have usage limits; no unlimited free services.
</details>

---

### Question 69

What is RI modification?

&nbsp;&nbsp;&nbsp;&nbsp;A. Change instance type/size/zone
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Cancel RI
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Sell RI
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. All above
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** RIs can be modified, sold, or exchanged without penalty.
</details>

---

### Question 70

Which plan includes concierge?

&nbsp;&nbsp;&nbsp;&nbsp;A. Business
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Developer
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Enterprise
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Basic
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Only Enterprise Support includes Concierge service.
</details>

---

### Question 71

What is the free tier for EBS?

&nbsp;&nbsp;&nbsp;&nbsp;A. 30 GB
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. 20 GB
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. 1 GB
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. 100 GB
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** 30 GB General Purpose SSD + 2M I/O + 1 GB snapshot.
</details>

---

### Question 72

Which provides RI recommendations?

&nbsp;&nbsp;&nbsp;&nbsp;A. Cost Explorer
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Trusted Advisor
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Both
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Budgets
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Both provide RI purchase recommendations based on usage.
</details>

---

### Question 73

What is Spot interruption notice?

&nbsp;&nbsp;&nbsp;&nbsp;A. 30 seconds before termination
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. 2 minutes
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. 5 minutes
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. 24 hours
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** 2-minute warning sent to instance metadata service.
</details>

---

### Question 74

Which shows amortized RI costs?

&nbsp;&nbsp;&nbsp;&nbsp;A. Cost Explorer
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Monthly Bill
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. CUR
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. All above
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Cost Explorer can show unblended (amortized) RI costs.
</details>

---

### Question 75

What is Business Support response time?

&nbsp;&nbsp;&nbsp;&nbsp;A. <12 hours
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. <24 hours
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. <1 hour
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. 24/7 instant
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** <12 hours for all severities, 24/7 phone support.
</details>

---

### Question 76

Which free forever service?

&nbsp;&nbsp;&nbsp;&nbsp;A. S3 (5GB)
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Lambda (1M requests)
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. DynamoDB (25GB)
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. All above
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** Always-free tier: S3 5GB, Lambda 1M, DynamoDB 25GB monthly.
</details>

---

### Question 77

What is RI Scope?

&nbsp;&nbsp;&nbsp;&nbsp;A. Regional vs Zonal
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Instance family
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Payment option
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. All above
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Regional RIs apply across AZs; Zonal only specific AZ.
</details>

---

### Question 78

Which tracks cost by linked account?

&nbsp;&nbsp;&nbsp;&nbsp;A. Consolidated billing
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Cost Explorer
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Both
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Budgets only
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Consolidated billing + Cost Explorer show multi-account costs.
</details>

---

### Question 79

What is the discount for 1-year All Upfront RI?

&nbsp;&nbsp;&nbsp;&nbsp;A. 40%
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. 50%
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. 60%
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. 75%
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** 1-year All Upfront offers ~40% discount.
</details>

---

### Question 80

Which plan includes GameDay exercises?

&nbsp;&nbsp;&nbsp;&nbsp;A. Business
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Enterprise On-Ramp
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Enterprise
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Developer
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Enterprise includes GameDay chaos engineering exercises.
</details>

---

### Question 81

What is the free tier for VPC?

&nbsp;&nbsp;&nbsp;&nbsp;A. 1000 NAT Gateway hours
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. 200M VPC Flow Log records
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Both
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Unlimited Gateways
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** 1000 NAT hours + 200M Flow Log records monthly.
</details>

---

### Question 82

Which shows unused EBS discounts?

&nbsp;&nbsp;&nbsp;&nbsp;A. Trusted Advisor
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Cost Explorer
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Budgets
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. CUR
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Trusted Advisor identifies low-utilization EBS volumes.
</details>

---

### Question 83

What is Spot Fleet?

&nbsp;&nbsp;&nbsp;&nbsp;A. Diversified Spot pool requests
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Single Spot request
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. RI replacement
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. On-Demand alternative
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Spot Fleet requests across multiple pools for availability.
</details>

---

### Question 84

Which support has white-glove onboarding?

&nbsp;&nbsp;&nbsp;&nbsp;A. Business
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Enterprise On-Ramp
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Enterprise
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Developer
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Enterprise On-Ramp includes onboarding workshop.
</details>

---

### Question 85

What is the billing for Elastic IP when not attached?

&nbsp;&nbsp;&nbsp;&nbsp;A. Free
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. $0.005/hour
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. $0.01/hour
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Per GB
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** $0.005/hour (~$3.60/month) when EIP not associated with running instance.
</details>

---

### Question 86

Which provides RI coverage reports?

&nbsp;&nbsp;&nbsp;&nbsp;A. Cost Explorer
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Trusted Advisor
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Both
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Pricing Calculator
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Both show RI utilization and coverage metrics.
</details>

---

### Question 87

What is the free tier for CloudWatch?

&nbsp;&nbsp;&nbsp;&nbsp;A. 10 metrics
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. 10 alarms
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. 1M API requests
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. All above
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** 10 custom metrics + 10 alarms + 1M API requests monthly.
</details>

---

### Question 88

Which plan includes Support Concierge?

&nbsp;&nbsp;&nbsp;&nbsp;A. Business
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Developer
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Enterprise
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Basic
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Enterprise-only billing/account advisory service.
</details>

---

### Question 89

What is the maximum Spot savings?

&nbsp;&nbsp;&nbsp;&nbsp;A. 50%
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. 75%
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. 90%
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. 100%
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Up to 90% off On-Demand when Spot price is low.
</details>

---

### Question 90

Which shows monthly bill PDF?

&nbsp;&nbsp;&nbsp;&nbsp;A. Billing Console
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Cost Explorer
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. CUR
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Budgets
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Billing Dashboard provides PDF summary of monthly charges.
</details>

---

### Question 91

What is 3-year Partial Upfront RI discount?

&nbsp;&nbsp;&nbsp;&nbsp;A. 60%
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. 65%
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. 70%
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. 75%
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** ~70% discount for 3-year Partial Upfront.
</details>

---

### Question 92

Which support plan is free?

&nbsp;&nbsp;&nbsp;&nbsp;A. Basic
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Developer
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Business
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Enterprise
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Basic Support is free with all accounts.
</details>

---

### Question 93

What is the free tier for EFS?

&nbsp;&nbsp;&nbsp;&nbsp;A. 5 GB Standard
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. 10 GB Standard
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. None
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. 1 GB
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** 5 GB Standard storage monthly always-free.
</details>

---

### Question 94

Which provides automatic RI renewals?

&nbsp;&nbsp;&nbsp;&nbsp;A. Cost Explorer
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. RI Dashboard
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Budgets
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. None
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** RI Dashboard manages renewals and modifications.
</details>

---

### Question 95

What is Business Support cost?

&nbsp;&nbsp;&nbsp;&nbsp;A. $29/month
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. 3% of spend
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. $100/month
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Usage-based
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** Minimum $100/month, then 3% of billed charges.
</details>

---

### Question 96

Which tracks Savings Plans utilization?

&nbsp;&nbsp;&nbsp;&nbsp;A. Cost Explorer
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. RI Dashboard
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Budgets
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Trusted Advisor
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Cost Explorer shows Savings Plans coverage metrics.
</details>

---

### Question 97

What is the free tier for ElastiCache?

&nbsp;&nbsp;&nbsp;&nbsp;A. 750 hours
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. None
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. 100 hours
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. 1 GB
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** No free tier for ElastiCache.
</details>

---

### Question 98

Which has <30 min response for critical?

&nbsp;&nbsp;&nbsp;&nbsp;A. Business
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Developer
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Enterprise
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Basic
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Enterprise: <30 min for critical severity.
</details>

---

### Question 99

What is the discount for 1-year No Upfront RI?

&nbsp;&nbsp;&nbsp;&nbsp;A. 30%
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. 40%
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. 50%
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. 60%
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** ~30% discount for 1-year No Upfront.
</details>

---

### Question 100

Which service schedules resource shutdown?

&nbsp;&nbsp;&nbsp;&nbsp;A. Instance Scheduler
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Budget Actions
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Cost Explorer
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Trusted Advisor
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Instance Scheduler automates EC2/RDS start/stop schedules.
</details>

---

### Question 101

What is Developer Support cost?

&nbsp;&nbsp;&nbsp;&nbsp;A. $29/month
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. 3% of spend
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Free
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. $100/month
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Flat $29/month for Developer Support.
</details>

---

### Question 102

Which shows cost anomalies?

&nbsp;&nbsp;&nbsp;&nbsp;A. Cost Anomaly Detection
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Budgets
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Cost Explorer
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Trusted Advisor
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** ML-powered anomaly detection with alerts.
</details>

---

### Question 103

What is the free tier for SNS?

&nbsp;&nbsp;&nbsp;&nbsp;A. 1M publishes
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. 100K HTTP deliveries
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. 1K email deliveries
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. All above
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** 1M publishes + 100K HTTP + 1K emails monthly.
</details>

---

### Question 104

Which RI type applies across Regions?

&nbsp;&nbsp;&nbsp;&nbsp;A. Regional
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Zonal
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Convertible
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Standard
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Regional RIs apply to any AZ in the Region.
</details>

---

### Question 105

What is Enterprise On-Ramp cost?

&nbsp;&nbsp;&nbsp;&nbsp;A. 3% minimum $1,500
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. 5% minimum $2,500
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. $29/month
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Free
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** 3% of spend, minimum $1,500/month.
</details>

---

### Question 106

Which tracks EBS volume optimization?

&nbsp;&nbsp;&nbsp;&nbsp;A. Trusted Advisor
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Cost Explorer
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Budgets
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. CUR
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Trusted Advisor identifies underutilized EBS volumes.
</details>

---

### Question 107

What is the free tier for SQS?

&nbsp;&nbsp;&nbsp;&nbsp;A. 1M requests
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. 40K retrievals
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. 100K queue hours
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. All above
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** 1 million SQS requests per month.
</details>

---

### Question 108

Which provides 99.5% EC2 SLA?

&nbsp;&nbsp;&nbsp;&nbsp;A. All customers
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Business Support
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Enterprise Support
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. No SLA
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** EC2 SLA 99.5% for all customers in single AZ.
</details>

---

### Question 109

What is the maximum RI term?

&nbsp;&nbsp;&nbsp;&nbsp;A. 1 year
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. 2 years
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. 3 years
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. 5 years
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Reserved Instances available for 1 or 3 years.
</details>

---

### Question 110

Which support includes Operations TAM?

&nbsp;&nbsp;&nbsp;&nbsp;A. Business
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Enterprise On-Ramp
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Enterprise
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Developer
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Enterprise includes dedicated Operations TAM.
</details>

---

### Question 111

What is the free tier for CloudFront?

&nbsp;&nbsp;&nbsp;&nbsp;A. 1 TB data transfer
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. 10M HTTP requests
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. 2M HTTPS requests
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. All above
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** 1 TB out + 10M HTTP + 2M HTTPS monthly.
</details>

---

### Question 112

Which shows Savings Plans recommendations?

&nbsp;&nbsp;&nbsp;&nbsp;A. Cost Explorer
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Trusted Advisor
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Both
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Budgets
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Cost Explorer provides Savings Plans purchase recommendations.
</details>

---

### Question 113

What is the cost of unused Elastic IP?

&nbsp;&nbsp;&nbsp;&nbsp;A. Free
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. $0.005/hour
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. $0.01/hour
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. $0.10/hour
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** B
> **Explanation:** $0.005/hr when not attached to running instance.
</details>

---

### Question 114

Which plan has 99.99% SLA credits?

&nbsp;&nbsp;&nbsp;&nbsp;A. Basic
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Developer
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Business
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Enterprise
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Business Support required for most SLA credits.
</details>

---

### Question 115

What is the free tier for API Gateway?

&nbsp;&nbsp;&nbsp;&nbsp;A. 1M REST calls
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. 750K WebSocket messages
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Both
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Unlimited
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** 1M REST + 750K WebSocket monthly.
</details>

---

### Question 116

Which provides automatic scaling recommendations?

&nbsp;&nbsp;&nbsp;&nbsp;A. Compute Optimizer
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Cost Explorer
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Trusted Advisor
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. All above
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Compute Optimizer recommends optimal instance types/configurations.
</details>

---

### Question 117

What is the discount for 2-year RI?

&nbsp;&nbsp;&nbsp;&nbsp;A. Not available
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. 50%
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. 60%
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. 65%
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** RIs only available for 1-year and 3-year terms.
</details>

---

### Question 118

Which tracks Data Transfer costs?

&nbsp;&nbsp;&nbsp;&nbsp;A. Cost Explorer
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. CUR
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Both
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Budgets
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Both break down Internet/Regional data transfer costs.
</details>

---

### Question 119

What is Basic Support?

&nbsp;&nbsp;&nbsp;&nbsp;A. Free, forums/documentation
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. $29/month
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. 3% of spend
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. TAM included
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Basic: Free with account, community forums only.
</details>

---

### Question 120

Which shows underutilized RDS?

&nbsp;&nbsp;&nbsp;&nbsp;A. Trusted Advisor
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Cost Explorer
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Compute Optimizer
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. All above
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** All identify low-utilization RDS instances.
</details>

---

### Question 121

What is the free tier for Redshift?

&nbsp;&nbsp;&nbsp;&nbsp;A. 750 hours dc2.large
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. None
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. 1 TB queries
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. 100 GB storage
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** 750 hours dc2.large node for 12 months.
</details>

---

### Question 122

Which provides 24/7 email support?

&nbsp;&nbsp;&nbsp;&nbsp;A. Basic
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Developer
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Business
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Enterprise
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Business Support includes 24/7 email/case support.
</details>

---

### Question 123

What is the cost of NAT Gateway?

&nbsp;&nbsp;&nbsp;&nbsp;A. $0.045/hour + $0.045/GB
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Free
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. $0.01/hour
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Per instance
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** $0.045/hr + $0.045/processed GB in each AZ.
</details>

---

### Question 124

Which shows Lambda cost optimization?

&nbsp;&nbsp;&nbsp;&nbsp;A. Compute Optimizer
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Cost Explorer
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Trusted Advisor
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. All above
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Compute Optimizer recommends optimal Lambda memory allocation.
</details>

---

### Question 125

What is the free tier for Kinesis?

&nbsp;&nbsp;&nbsp;&nbsp;A. 100K PUT records
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. None
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. 1 shard-hour
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. 50 GB ingested
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** 100K PUT payload units per month always-free.
</details>

---

### Question 126

Which support includes monthly business reviews?

&nbsp;&nbsp;&nbsp;&nbsp;A. Business
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Enterprise On-Ramp
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Enterprise
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Developer
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Enterprise includes monthly Business Reviews with TAM.
</details>

---

### Question 127

What is the discount for Savings Plans vs RI?

&nbsp;&nbsp;&nbsp;&nbsp;A. Same
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. 5% less
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. 10% less
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. More flexible
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** D
> **Explanation:** Same discount, but Savings Plans more flexible across services.
</details>

---

### Question 128

Which tracks Elastic Load Balancer costs?

&nbsp;&nbsp;&nbsp;&nbsp;A. Cost Explorer
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Trusted Advisor
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Both
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Budgets
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Both show ELB load balancer and LCU costs.
</details>

---

### Question 129

What is the free tier for VPC Endpoints?

&nbsp;&nbsp;&nbsp;&nbsp;A. 100,000 requests
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. 1 GB data
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Both
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Unlimited
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** 100K requests + 1 GB data processing monthly.
</details>

---

### Question 130

Which provides third-party billing support?

&nbsp;&nbsp;&nbsp;&nbsp;A. Concierge
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. TAM
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Partner Network
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. All above
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** Concierge helps with complex third-party billing issues.
</details>

---

### Question 131

What is the cost of S3 data transfer out (first 100GB)?

&nbsp;&nbsp;&nbsp;&nbsp;A. Free
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. $0.09/GB
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. $0.02/GB
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. $0.01/GB
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** A
> **Explanation:** First 100 GB/month Internet data transfer out is free.
</details>

---

### Question 132

Which support plan is recommended for production workloads?

&nbsp;&nbsp;&nbsp;&nbsp;A. Basic
<br>&nbsp;&nbsp;&nbsp;&nbsp;B. Developer
<br>&nbsp;&nbsp;&nbsp;&nbsp;C. Business
<br>&nbsp;&nbsp;&nbsp;&nbsp;D. Enterprise
<details>
<summary>Click to reveal answer.</summary>
<br>

**Correct Answer:** C
> **Explanation:** Business Support recommended for production with 24/7 access and SLA credits.
</details>

---
 

