# Karim Al-Azzawi's AWS Certified Cloud Practitioner (CLF-C02) Study Guide

Welcome to my **AWS Certified Cloud Practitioner Study Guide**! This comprehensive resource is designed to help you ace the AWS Certified Cloud Practitioner exam (CLF-C02), a foundational certification validating your understanding of AWS Cloud concepts, services, security, and economics. Ideal for beginners with up to 6 months of AWS exposure. As of October 18, 2025, CLF-C02 is the current exam version. Expect 20-40 study hours; aim for a 700/1000 passing score.

---

## 1. Exam Overview

From the [official AWS Exam Guide](https://d1.awsstatic.com/training-and-certification/docs-cloud-practitioner/AWS-Certified-Cloud-Practitioner_Exam-Guide.pdf):

### Key Exam Details

| Aspect | Details |
|--------|---------|
| **Exam Code** | CLF-C02 |
| **Number of Questions** | 65 (50 scored + 15 unscored; unscored for future evaluation) |
| **Question Types** | Multiple choice (1 correct out of 4) or multiple response (2+ correct out of 5+); mostly scenario-based |
| **Duration** | 90 minutes |
| **Passing Score** | 700 (scaled 100-1000; compensatory scoring) |
| **Cost** | $100 USD (plus taxes; check for free retake promotions) |
| **Languages** | English, Arabic, Bahasa, French, German, Italian, Japanese, Korean, Portuguese (Brazil), Simplified Chinese, Spanish (Latin America/Spain), Traditional Chinese |
| **Testing Options** | Pearson VUE center or online proctored |
| **Validity** | 3 years; recertify via exam or AWS Cloud Quest: Recertify (free beta until mid-2025) |

**Notes:** Unanswered questions count as incorrect—no guessing penalty. Out-of-scope: coding, architecture design, troubleshooting, implementation, load/performance testing.

### Exam Domains and Weightings

Aggregated from [official guide](https://d1.awsstatic.com/training-and-certification/docs-cloud-practitioner/AWS-Certified-Cloud-Practitioner_Exam-Guide.pdf) and [Tutorials Dojo](https://tutorialsdojo.com/aws-cloud-practitioner-clf-c02-exam-guide/):

| Domain | Weighting | Focus Areas |
|--------|-----------|-------------|
| **1: Cloud Concepts** | 24% | AWS value proposition, Well-Architected Framework, migration strategies (AWS CAF, Snowball), cloud economics (fixed vs. variable costs, rightsizing, automation). |
| **2: Security and Compliance** | 30% | Shared responsibility model, compliance/governance (Artifact, Config), access management (IAM, MFA), security resources (GuardDuty, Inspector, WAF). |
| **3: Cloud Technology and Services** | 34% | Deployment methods (IaC, CLI), global infrastructure (Regions, AZs, edge locations), core services: compute (EC2, Lambda), databases (RDS, DynamoDB), networking (VPC, Route 53), storage (S3, EBS), AI/ML/analytics (SageMaker, Athena). |
| **4: Billing, Pricing, and Support** | 12% | Pricing models (On-Demand, Reserved, Spot, Savings Plans), cost tools (Cost Explorer, Budgets), support plans (Basic to Enterprise), technical resources (Trusted Advisor, Partners). |

**Pro Tip:** Focus on Domains 2 and 3 (60% combined). Know in-scope services (EC2, S3, IAM) vs. out-of-scope (advanced ML).

---

## 2. Study Plan

A 4-6 week plan with tips from [Tutorials Dojo](https://tutorialsdojo.com/aws-cloud-practitioner-clf-c02-exam-guide/) and [Cheatography](https://cheatography.com/sokoctopus/cheat-sheets/aws-ccp-clf-c02/). Track with Anki.

| Week | Focus | Activities | Estimated Time |
|------|-------|------------|----------------|
| **1: Foundations** | Exam overview + Domain 1 | Read exam guide; AWS Cloud Practitioner Essentials course; whitepapers (Well-Architected, AWS Overview); review migration strategies. | 5-7 hours |
| **2: Security Deep Dive** | Domain 2 | Labs on IAM, shared model; study compliance tools (Artifact, GuardDuty); review encryption. | 6-8 hours |
| **3: Core Services** | Domain 3 | Free Tier hands-on (VPC, EC2, S3); Cloud Quest; explore AI/ML services; review deployment models. | 7-10 hours |
| **4: Economics & Review** | Domain 4 + Full Review | Pricing Calculator; flashcards; 2 practice exams; compare pricing models. | 6-8 hours |
| **5-6: Practice & Polish** | All Domains | 3-5 practice exams; weak areas (services via cheat sheets); simulations; community Q&A. | 5-7 hours/week |

**Daily Habits:** 30-60 min flashcards (mnemonics below). Join [r/AWSCertifications](https://www.reddit.com/r/AWSCertifications/), AWS re:Post. Hands-on: Build VPC with EC2/S3; use CLI/SDKs.

**Tips:** Read questions carefully; flag unknowns. Use process of elimination. Review AWS whitepapers (AWS CAF). HPC: AWS eliminates queues/costs.

---

## 3. Core Study Topics

Aggregated from [official guide](https://d1.awsstatic.com/training-and-certification/docs-cloud-practitioner/AWS-Certified-Cloud-Practitioner_Exam-Guide.pdf), [Cheatography](https://cheatography.com/sokoctopus/cheat-sheets/aws-ccp-clf-c02/), [Whizlabs](https://media.whizlabs.com/website/AWS-Certified-Cloud-Practitioner-03-09-2021.pdf), [Khaledelhannat](https://khaledelhannat.github.io/aws-certification-practice-hub/assets/ccp_cs.htm), and [Tutorials Dojo](https://tutorialsdojo.com/aws-cloud-practitioner-clf-c02-exam-guide/).

### Domain 1: Cloud Concepts (24%)

- **Benefits:** Economies of scale, global infra (low latency, redundancy), elasticity, high availability (99.99%+). No CapEx; OpEx model. Speed via virtualization.
- **Design Principles:** Well-Architected Framework: Operational Excellence (automation), Security (IAM), Reliability (failure management), Performance Efficiency (resource selection), Cost Optimization (spend control), Sustainability (efficient hardware). "Stop guessing capacity."
- **Migration Strategies:** AWS CAF (risk reduction, ESG); strategies: rehost, replatform, refactor. Tools: Migration Hub, DMS/SCT, Snow Family.
- **Cloud Economics:** Fixed vs. variable costs; rightsizing, automation (CloudFormation), managed services (RDS).

>_Mnemonic:_ **"OSR PCS"** (Operational Excellence, Security, Reliability, Performance, Cost, Sustainability). **Cheatography:** "AWS Delivers Elastic, Scalable Clouds" (Agility, Durability, Elasticity, Scalability, Cost Savings).

### Domain 2: Security and Compliance (30%)

- **Shared Responsibility Model:** AWS: Infrastructure. Customer: Data, OS patching, encryption. Applies to IaaS/PaaS/SaaS.
- **Security, Governance, Compliance:** Artifact (GDPR, HIPAA); Config (checks); encryption (KMS); CloudTrail (logs); GuardDuty, Inspector, Shield, WAF, Security Hub, CloudHSM, RAM.
- **Access Management:** IAM (users/roles/policies, MFA); Identity Center (SSO); Secrets Manager; federated access (SAML, AD).
- **Security Resources:** Security groups/NACLs; Marketplace; Trusted Advisor; Knowledge Center.

>_Mnemonic:_ **"SIAM Guards Secrets"** (Security, IAM, Artifact, Monitoring/GuardDuty). **Khaled:** Access Analyzer, Cognito.

### Domain 3: Cloud Technology and Services (34%)

- **Global Infrastructure:** Regions (e.g., us-east-1), AZs (HA), Edge Locations (CloudFront). Outposts, Local Zones, Wavelength.
- **Deployment Methods:** Console, CLI, SDKs, IaC (CloudFormation); cloud/hybrid/on-prem; VPN/Direct Connect.
- **Compute:** EC2 (instances, AMI); ECS/EKS; Lambda/Fargate; Auto Scaling; ELB; Lightsail; Batch; HPC.
- **Databases:** RDS/Aurora (relational); DynamoDB (NoSQL); DocumentDB; ElastiCache; Keyspaces; DMS/SCT.
- **Networking:** VPC (subnets, IGW, NACLs/SGs); Route 53; CloudFront/Global Accelerator; API Gateway.
- **Storage:** S3 (Standard/IA/Glacier/Intelligent-Tiering); EBS; EFS/FSx; Instance Store; Storage Gateway; Snowball; Backup.
- **AI/ML & Analytics:** SageMaker; Lex/Kendra; Athena; EMR; Kinesis; MSK; Redshift; Glue; Lake Formation; QuickSight.
- **Other:** EventBridge, SNS, SQS; Connect, SES; CodeBuild/Deploy/Pipeline; AppStream, WorkSpaces; Amplify; IoT Core.

>_Mnemonic:_ **"CDNSA + AIM"** (Compute, Databases, Networking, Storage, AI/ML). **Whizlabs:** Athena (SQL), EMR (Hadoop), Kinesis (streams).

### Domain 4: Billing, Pricing, and Support (12%)

- **Pricing Models:** On-Demand; Reserved/Savings Plans; Spot; Dedicated; data transfer (in free, out charged).
- **Cost Management:** Cost Explorer; Budgets; Billing Console; CUR; Pricing Calculator; tags; Organizations.
- **Support:** Basic (free); Developer (24h); Business (1h critical); Enterprise (15min, TAM). Resources: Health Dashboard, Partners.

>_Mnemonic:_ **"OPBS"** (On-Demand, Pricing, Budgets, Support). **Khaled:** Enterprise: TAM, <15min.

---

## 4. Recommended Resources

### Free Resources

- **Official:**
  - [Exam Guide](https://d1.awsstatic.com/training-and-certification/docs-cloud-practitioner/AWS-Certified-Cloud-Practitioner_Exam-Guide.pdf)
  - Cloud Practitioner Essentials (6h)
  - Cloud Quest (12h)
  - Practice Set (20 questions)
  - Well-Architected whitepaper
  - Free Tier labs
- **Community:**
  - [r/AWSCertifications](https://www.reddit.com/r/AWSCertifications/)
  - re:Post
  - Twitch
  - [Khaledelhannat cheat sheet](https://khaledelhannat.github.io/aws-certification-practice-hub/assets/ccp_cs.htm)
  - [Cheatography](https://cheatography.com/sokoctopus/cheat-sheets/aws-ccp-clf-c02/)

### Paid/Community Resources

| Resource Type | Recommendations | Cost | Why It's Great |
|---------------|-----------------|------|----------------|
| **Courses** | Udemy: Neal Davis CLF-C02 (16h, 300+ questions); FreeCodeCamp: Andrew Brown (15h YouTube) | ~$15 | Covers domains, tips. |
| **Practice Exams** | Tutorials Dojo (4 modes, cheat sheets); Neal Davis (600+) | $49-69 | Realistic, explanations. |
| **Books** | Piper's Study Guide (C02); Tutorials Dojo eBook | $30 | In-depth, flashcards. |
| **Other** | Pluralsight; Whizlabs PDF cheat sheet (2021) | Subscription | Paths, trials. |

### Cheat Sheets Summary

- **S3 Classes:** Standard (frequent), IA (infrequent), One Zone-IA (single AZ), Glacier (archive: Instant/Flexible/Deep), Intelligent-Tiering (auto).
- **Instance Options:** On-Demand, Reserved, Savings Plans, Spot.
- **Support Plans:** Basic (free), Developer (24h), Business (1h critical), Enterprise (15min, TAM).

---

d) Health Dashboard  

**4. Domain 3:** Primary benefit of multi-AZs?  
a) Latency reduction  
b) Sovereignty  
c) **HA/fault tolerance**  
d) Cost savings  

**Full Answers & Explanations:** [Questions and Answers Page](questions-answers.md)

More: [Tutorials Dojo](https://tutorialsdojo.com/aws-cloud-practitioner-clf-c02-exam-guide/), Whizlabs sets.

---

## 5. Exam Day Tips

- Sleep well; arrive early.
- Read fully; eliminate options; flag/skip.
- Guess if stuck.
- **Post-exam:** Immediate score; Credly badge.

---

## 6. Why Get Certified? Career Benefits

- Entry to AWS path (e.g., Solutions Architect).
- 84% job increase; $90K-120K entry-level.
- Demonstrates fluency for non-tech roles (sales, PM).

---

You've got this! Use this guide for success. Questions? Visit [AWS forums](https://www.reddit.com/r/AWSCertifications/). Good luck! 🚀
