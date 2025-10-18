# AWS Services

# Domain 1 — Cloud Concepts
## Compute
| Service (short) | Description | What it offers |
|---|---|---|
| **App Runner** | Fully managed service to build and run web apps and APIs from source code or containers. | HTTPS by default • Autoscaling • No servers to manage • VPC connectivity |
| **Auto Scaling (EC2 ASG)** | Automatically scale EC2 capacity based on demand or schedules. | Target/step policies • Health checks • Multi-AZ resilience |
| **Batch** | Managed batch computing for efficiently running hundreds of thousands of batch jobs. | Queues & compute envs • Spot integration • EC2/Fargate backends |
| **EC2** | Resizable virtual servers in the cloud with the broadest compute portfolio. | Instance families & sizes • EBS/EFA/GPUs/Graviton • Nitro security • Placement groups |
| **EC2 Image Builder** | Automate creation, hardening, testing, and distribution of AMIs and container images. | Pipelines • Tests & compliance • Multi-Region distribution |
| **Elastic Beanstalk** | Orchestrated PaaS for deploying and operating web applications. | Managed capacity & OS • Health monitoring • Rolling/blue‑green |
| **Fargate** | Serverless compute engine for containers on ECS/EKS. | Per-task billing • No node management • Scales automatically |
| **Lambda** | Serverless, event-driven functions that scale automatically. | Millisecond billing • Event integrations • Provisioned concurrency |
| **Lightsail** | Simplified VPS, databases, and containers with predictable pricing. | Fixed bundles • Snapshots • Blueprints |
| **Outposts** | Run AWS infrastructure and services on-premises for low-latency or local data processing. | Same APIs/tools on-prem • Local compute & storage |
| **Serverless Application Repository** | Discover, deploy, and publish serverless applications and components. | One-click deploy • Sharing & versioning • SAM integration |
| **Wavelength** | Run applications at the 5G edge with ultra-low latency. | 5G MEC zones • VPC subnets at the edge |
| **VMware Cloud on AWS** | VMware SDDC running on AWS infrastructure. | vMotion & HCX • Integrates with native AWS |
## Containers
| Service (short) | Description | What it offers |
|---|---|---|
| **App Mesh** | Service mesh that provides application-level networking for microservices. | Traffic shifting • mTLS/observability • Envoy-based |
| **ECR** | Private, secure, and scalable container image registry. | Vulnerability scanning • Immutable tags • Cross-account sharing |
| **ECS** | Highly scalable container orchestration service. | Tasks/services • Capacity providers • EC2/Fargate launch types |
| **EKS** | Managed Kubernetes control plane. | Managed node groups • Fargate pods • EKS add-ons |
## Storage
| Service (short) | Description | What it offers |
|---|---|---|
| **AWS Backup** | Centralized backup across AWS services and on-premises. | Backup plans & vaults • Cross-Region/Account copy • Compliance reporting |
| **DataSync** | Online data transfer and sync between on‑premises, edge, and AWS storage. | NFS/SMB/Object • Incremental & verified • Task scheduling |
| **EBS** | Block storage volumes for EC2. | SSD/HDD families • Snapshots & fast snapshot restore • KMS encryption |
| **EFS** | Serverless, elastic NFS file system for Linux workloads. | Multi-AZ • Burst & provisioned modes • POSIX semantics |
| **FSx for Lustre** | High‑performance file system for HPC, ML, and media workflows. | POSIX • S3 integration • Sub‑ms latency |
| **FSx for NetApp ONTAP** | Fully managed NetApp ONTAP file systems. | NFS/SMB/iSCSI • Snapshots/SnapMirror • Multi-protocol access |
| **FSx for OpenZFS** | Managed OpenZFS file systems. | Low-latency • Snapshots • POSIX |
| **FSx for Windows File Server** | Fully managed, native Windows file systems backed by Windows Server. | SMB & AD integration • DFS namespaces • Shadow copies |
| **S3** | Scalable object storage with high durability, availability, and security. | Storage classes (IA, Intelligent‑Tiering, One Zone, Glacier) • Versioning & lifecycle • Bucket policies |
| **S3 Glacier** | Low‑cost archival storage tiers for long‑term retention. | Flexible/Standard/Deep Archive • Vault Lock • Minutes‑to‑hours retrievals |
| **Storage Gateway** | Hybrid storage with file, volume, and tape gateways. | NFS/SMB • Cached/stored volumes • VTL |
| **Transfer Family** | SFTP, FTPS, FTP, and AS2 endpoints backed by S3/EFS. | IdP federation • VPC access • Workflows & PGP |
## Databases
| Service (short) | Description | What it offers |
|---|---|---|
| **Aurora** | MySQL- and PostgreSQL-compatible relational database built for the cloud. | Global Database • Backtrack • Serverless options |
| **Database Migration Service (DMS)** | Migrate and replicate databases with minimal downtime. | CDC • Heterogeneous migrations • Validation |
| **DocumentDB (MongoDB-compatible)** | Managed document database compatible with MongoDB APIs. | Auto-scaling storage • Backup & metrics • Security & VPC |
| **DynamoDB** | Serverless key‑value and document database. | Single‑digit ms latency • Global tables • DAX in‑memory cache |
| **ElastiCache** | In‑memory cache compatible with Redis and Memcached. | Sub‑ms performance • Sharding/replicas • Auto failover |
| **Keyspaces (for Apache Cassandra)** | Serverless, managed Apache Cassandra‑compatible database. | CQL • Autoscaling • No servers to manage |
| **MemoryDB for Redis** | Durable, Redis‑compatible in‑memory database for ultra‑fast performance. | Multi‑AZ durability • Redis APIs • Sub‑ms reads |
| **Neptune** | Fully managed graph database supporting property graph and RDF. | Gremlin/SPARQL • High performance • ACID transactions |
| **QLDB** | Immutable, cryptographically verifiable ledger database. | Append‑only journal • PartiQL • History queries |
| **RDS** | Managed relational databases (MySQL, PostgreSQL, MariaDB, Oracle, SQL Server). | Multi‑AZ & read replicas • Auto backups/patching • Performance Insights |
| **Redshift** | Managed, petabyte‑scale data warehouse. | RA3/Serverless • Spectrum (S3) • Materialized views |
| **Timestream** | Serverless time‑series database for IoT and operations. | Time functions • Tiered storage • SQL‑compatible |
## Networking & Content Delivery
| Service (short) | Description | What it offers |
|---|---|---|
| **API Gateway** | Create, publish, secure, and monitor APIs at any scale. | REST/HTTP/WebSocket • Throttling & auth • Usage plans |
| **CloudFront** | Global content delivery network (CDN). | Edge caching • Functions/Lambda@Edge • TLS & geo controls |
| **Cloud WAN** | Centralized, policy‑based global WAN service. | Segmented networks • Telemetry & insights • Integrated TGW/VPN/DC |
| **Direct Connect** | Dedicated network connections from on‑premises to AWS. | Consistent latency • Private connectivity • VIFs & LAGs |
| **Elastic Load Balancing (ALB/NLB/GWLB)** | Distribute traffic across targets at L7/L4 and service appliances. | ALB/NLB/GWLB • Cross‑zone • Advanced routing |
| **Global Accelerator** | Global anycast accelerator for TCP/UDP apps. | Static anycast IPs • Health‑based routing • Traffic dials |
| **PrivateLink** | Private access to AWS/partner services via interface endpoints. | No public IPs • ENI endpoints • Cross‑account/services |
| **Route 53** | Highly available and scalable DNS with domain registration and health checks. | Traffic policies • Geolocation/latency routing • Resolver & endpoints |
| **Site‑to‑Site VPN** | IPSec VPN connectivity between on‑premises and AWS. | Redundant tunnels • BGP dynamic routing |
| **Transit Gateway** | Hub‑and‑spoke network connectivity for VPCs and on‑premises. | Inter‑VPC routing • Multicast support • Network Manager |
| **VPC** | Isolated virtual network for AWS resources. | Subnets/NACLs/SGs • Route tables • Gateway & interface endpoints |
# Domain 2 — Security & Compliance
## Identity, Access & Account Governance
| Service (short) | Description | What it offers |
|---|---|---|
| **Artifact** | On‑demand access to AWS compliance reports and agreements. | SOC/PCI/ISO reports • Agreements • Audit support |
| **Audit Manager** | Continuously audit AWS usage to simplify risk and compliance assessments. | Automated evidence • Frameworks • Assessments & reports |
| **Cognito** | User sign‑up/sign‑in and identity federation for web and mobile apps. | User & identity pools • OIDC/SAML/social • Hosted UI |
| **Control Tower** | Set up and govern a secure, multi‑account AWS environment (landing zone). | Guardrails • Account vending • Blueprints |
| **IAM** | Fine‑grained access control for AWS services and resources. | Users/roles/policies • MFA • Access Analyzer |
| **IAM Identity Center (AWS SSO)** | Single sign‑on and user provisioning for AWS accounts and applications. | Permission sets • SCIM • SAML federation |
| **Organizations** | Multi‑account orchestration and consolidated billing with service control policies. | OUs & SCPs • Trusted access • Cost visibility |
| **Resource Access Manager (RAM)** | Share AWS resources across accounts and organizations. | Centralized sharing • Supports many services |
| **Service Quotas** | View and manage service limits (quotas) for AWS services. | Quota increase requests • Monitoring & alarms |
| **Verified Permissions** | Fine‑grained authorization with Cedar‑based policy engine for apps. | Cedar policies • Policy decision API • Auditability |
## Data Protection & Cryptography
| Service (short) | Description | What it offers |
|---|---|---|
| **ACM (Certificate Manager)** | Provision, manage, and deploy public and private TLS/SSL certificates. | Managed renewal • Private CA • Automation |
| **CloudHSM** | Managed hardware security modules in your VPC. | FIPS 140‑2 L3 • Exclusive tenant control • High availability |
| **KMS** | Managed key management and encryption service. | Symmetric/asymmetric keys • HSM‑backed • Envelope encryption |
| **Secrets Manager** | Rotate, manage, and retrieve database credentials, API keys, and secrets. | Automatic rotation • Fine‑grained access • Audit with CloudTrail |
## Detection, Monitoring & Response
| Service (short) | Description | What it offers |
|---|---|---|
| **CloudTrail** | Governance, compliance, and operational auditing of account activity across AWS. | Event history & trails • CloudTrail Lake • S3/Athena integration |
| **Config** | Assess, audit, and evaluate configurations of your AWS resources. | Conformance packs • Rules & remediation • Change history |
| **Detective** | Security investigation service using behavior graphs and ML. | Linked to GuardDuty • Entity relationships • Root cause analysis |
| **Firewall Manager** | Centralized management of firewall policies across accounts and resources. | Org‑wide enforcement • Audit & remediations |
| **GuardDuty** | Intelligent threat detection and continuous monitoring for malicious activity. | Findings for EC2/EKS/S3/RDS/IAM • Malware protection • EKS runtime |
| **Inspector** | Automated vulnerability management for compute and container resources. | EC2/ECR/ECS/EKS scans • SBOMs • Risk scoring |
| **Macie** | Data security and privacy service that uses ML to discover and protect sensitive data in S3. | PII detection • Automated classification • Detailed findings |
| **Network Firewall** | Managed, stateful network firewall for VPCs. | Suricata rules • Traffic filtering • Logging & metrics |
| **Security Hub** | Centralized security posture management with standards and controls. | CIS/PCI frameworks • Findings aggregation • Insights & automation |
| **Shield (Standard/Advanced)** | DDoS protection for applications running on AWS. | L3‑L7 protection • 24/7 DRT (Advanced) • Cost protection |
| **Verified Access** | Zero‑trust secure access to internal applications without a VPN. | Identity & device posture • Policy‑based • No client VPN required |
| **WAF** | Protect web applications from common exploits and bots. | Managed rules • Bot control • Rate‑based rules |
# Domain 3 — Technology
## Analytics, Data & Integration
| Service (short) | Description | What it offers |
|---|---|---|
| **Athena** | Serverless interactive SQL over S3 and federated sources. | Pay‑per‑query • Open table formats • Federated connectors |
| **Data Exchange** | Find, subscribe to, and use third‑party data in the cloud. | Subscriptions • Entitlements • Delivery to S3/Redshift |
| **Data Pipeline** | Orchestrate data movement and processing across compute services. | Scheduling & retries • Dependable pipelines |
| **DataZone** | Data management service for governed sharing across domains. | Business data portal • Projects • Approvals & lineage |
| **EMR** | Managed big data platform for frameworks like Spark, Hive, and Presto. | EC2/EKS/Serverless • Autoscaling • EMRFS & notebooks |
| **Glue** | Serverless data integration, ETL, and centralized Data Catalog. | Crawlers & jobs • Studio & Workflows • Integration with Athena/Redshift |
| **Glue DataBrew** | Visual data preparation for analytics and ML. | Transformations • Profiles • No code |
| **Kinesis (Analytics/Firehose/Streams/Video)** | Real‑time data ingestion, processing, and delivery. | Stream processing • Managed delivery • Video ingestion |
| **Lake Formation** | Build secure data lakes with fine‑grained access control. | Blueprints • LF‑TAGs • Row/column‑level security |
| **MSK (Managed Streaming for Apache Kafka)** | Fully managed Apache Kafka. | Provisioned & Serverless • Ecosystem compatibility |
| **OpenSearch Service** | Search, log analytics, and observability with OpenSearch. | Dashboards • UltraWarm/Cold • Serverless collections |
| **QuickSight** | Serverless BI, dashboards, and embedded analytics. | SPICE • Row‑level security • Reader session pricing |
| **Entity Resolution** | Match and link related records across data sources. | Prebuilt ML/Rule matching • Schema mapping • Metrics & tuning |
| **Clean Rooms** | Privacy‑safe data collaboration without sharing raw data. | SQL queries • Cryptographic computing • Collaboration controls |
## Application Integration & Orchestration
| Service (short) | Description | What it offers |
|---|---|---|
| **AppFlow** | Secure, no‑code integration with SaaS applications. | Bidirectional flows • Mapping/Transform • PrivateLink options |
| **EventBridge** | Serverless event bus for app, AWS, and SaaS events. | Rules & buses • Pipes • Scheduler |
| **MQ (ActiveMQ/RabbitMQ)** | Managed message brokers compatible with popular protocols. | HA brokers • JMS/AMQP/MQTT • Managed upgrades |
| **SNS** | Highly available pub/sub messaging. | Fan‑out • SMS/email/mobile push • Message filtering |
| **SQS** | Fully managed message queues. | Standard & FIFO • DLQs • Exactly‑once for FIFO |
| **Step Functions** | Visual workflows for distributed applications. | Standard & Express • 200+ service integrations • Map/parallel states |
| **SWF** | Task coordination and state management for background jobs. | Workers/deciders • Durable state • At‑least‑once tasks |
## Developer Tools & Platform
| Service (short) | Description | What it offers |
|---|---|---|
| **Amplify** | Frontend and mobile development platform with hosting and backend building blocks. | CI/CD hosting • Auth/Data/Storage UI • Observability |
| **AppConfig** | Feature flags and application configuration with safe deployments. | Validators • Automated rollouts • Rollback |
| **CDK (Cloud Development Kit)** | Define cloud infrastructure in code using familiar languages. | Constructs • Synth to CloudFormation • Reusable patterns |
| **Cloud9** | Browser‑based IDE for code, build, and debug. | Collaboration • Preconfigured envs • EC2 or SSH hosts |
| **CodeBuild** | Fully managed build service. | On‑demand containers • Parallel builds • Reports |
| **CodeCatalyst** | Cloud‑native DevOps platform for planning through delivery. | Issues/Boards • CI/CD • Spaces & blueprints |
| **CodeCommit** | Secure, highly scalable private Git repositories. | Fine‑grained IAM • Notifications • Code reviews |
| **CodeDeploy** | Automated deployments to EC2/ECS/Lambda/on‑prem. | Blue/green • Hooks • Rollbacks |
| **CodePipeline** | Continuous delivery service for release automation. | Stages/actions • Integrations • Manual approvals |
| **Device Farm** | Test web and mobile apps on real devices. | Parallel runs • Remote access • CI integration |
| **Proton** | Self‑service platform and app delivery with templates. | Environment/service pipelines • Standards enforcement |
| **X‑Ray** | Distributed tracing for production applications. | Service maps • Sampling • Trace analytics |
## Management, Governance & Observability
| Service (short) | Description | What it offers |
|---|---|---|
| **AWS Health Dashboard (Personal/Org)** | Visibility into AWS events that impact your resources. | Proactive alerts • Org aggregation • Integrates with SSM/Chatbot |
| **Application Discovery Service** | Discover on‑premises servers, usage, and dependencies. | Agent/agentless • Migration planning |
| **Billing Conductor** | Customize, allocate, and present billing to business units. | Pro forma billing • Billing groups • Chargeback/showback |
| **CloudFormation** | Model and provision AWS resources with templates. | Stacks/StackSets • Drift detection • Registry |
| **CloudWatch** | Observability suite for metrics, logs, alarms, dashboards, RUM, and Synthetics. | Alarms & Events • Logs Insights • Application Signals |
| **Managed Grafana** | Fully managed Grafana workspaces for visualization. | SSO & RBAC • Alerting • Many data sources |
| **Managed Service for Prometheus (AMP)** | Managed Prometheus‑compatible monitoring. | Scrape/remote write • Queries & alerting |
| **License Manager** | Track, manage, and enforce software licenses. | Discovery • Enforcement • BYOL |
| **Migration Hub** | Plan, track, and orchestrate application migrations. | Strategy recommendations • Orchestrator runbooks |
| **OpsWorks** | Configuration management using Chef Automate or Puppet. | Stacks/layers • Auto healing |
| **Service Catalog** | Curate and govern approved AWS/third‑party products. | Portfolios • Constraints • TagOptions |
| **Systems Manager (SSM)** | Operations suite for fleet management and automation. | Run/State/Patch Manager • Inventory • Parameter Store |
| **Trusted Advisor** | Best‑practice checks for cost, security, performance, and resilience. | Recommendations • Org view • Exports & alerts |
| **Well‑Architected Tool** | Review workloads against AWS best‑practice pillars. | Lenses • Improvement plans • Reports |
## Machine Learning & Generative AI
| Service (short) | Description | What it offers |
|---|---|---|
| **Amazon Q (Business/Developer)** | Generative AI assistant for work content and code. | Connectors & retrieval • IDE/Console integrations • Guardrails |
| **Bedrock** | Foundation model service to build and scale generative AI applications. | Model access (Amazon/partners) • Agents • Guardrails |
| **CodeWhisperer** | AI coding companion for real‑time code suggestions. | Inline suggestions • Security scans • IDE plugins |
| **Comprehend** | Natural language processing (NLP) for text insights. | Entities/sentiment/key phrases • Custom models |
| **Forecast** | Time‑series forecasting using ML. | AutoML • Probabilistic output • Related time‑series |
| **Fraud Detector** | Identify potential online fraud with ML. | Rules + models • Real‑time scoring |
| **Kendra** | Intelligent enterprise search with relevance tuning. | Connectors • Semantic ranking • Q&A |
| **Lex** | Conversational AI for chat and voice. | NLU/ASR • Multi‑lang • Contact center integration |
| **Lookout for Equipment** | Detect equipment anomalies using sensor data. | Time‑series ML • Diagnostics |
| **Lookout for Metrics** | Automatically detect anomalies in business metrics. | Explainability • Alerts & actions |
| **Lookout for Vision** | Automated visual inspection for image defects. | Model training • Edge deployment |
| **Personalize** | Real‑time personalization and recommendations. | User/item/context • A/B testing |
| **Polly** | Text‑to‑speech with lifelike voices. | Neural voices • Lexicons/SSML |
| **Rekognition** | Image and video analysis. | Labels/faces/unsafe content • Celebrity recognition |
| **SageMaker** | End‑to‑end ML platform for building, training, and deploying models. | Studio/JumpStart • Pipelines • Model registry |
| **Textract** | Intelligent OCR for forms, tables, and documents. | Key‑value pairs • Expense/ID analysis |
| **Transcribe** | Automatic speech‑to‑text. | Call analytics • Custom vocabulary |
| **Translate** | Neural machine translation. | Batch/real‑time • Custom terminology |
## IoT, Edge & Robotics
| Service (short) | Description | What it offers |
|---|---|---|
| **FreeRTOS** | Open‑source RTOS and libraries for microcontrollers. | OTA updates • MQTT/TLS • Edge libraries |
| **IoT Analytics** | Analytics for IoT data at scale. | Pipelines & stores • Jupyter notebooks |
| **IoT Core** | Secure device connectivity and messaging. | Pub/Sub messaging • Device shadows • Rules engine |
| **IoT Device Defender** | Audit and monitor IoT configurations and behaviors. | Detect anomalies • Mitigation actions |
| **IoT Device Management** | Fleet provisioning, jobs, and indexing. | OTA updates • Fleet indexing • Secure tunneling |
| **IoT Events** | Detect and respond to events from IoT sensors and apps. | Detectors • Actions & integrations |
| **IoT FleetWise** | Collect, transform, and transfer vehicle data to the cloud. | Vehicle modeling • Edge agents • Efficient ingestion |
| **IoT Greengrass** | Local compute, messaging, and ML inference for edge devices. | Component model • Secure comms • Offline operation |
| **IoT SiteWise** | Collect, organize, and monitor industrial equipment data. | Asset models • Portals • Metrics |
| **IoT TwinMaker** | Build digital twins of real‑world systems. | 3D scenes • Connectors • Time‑series sync |
| **RoboMaker** | Robotics simulation and application deployment (ROS). | Gazebo sim • Fleet mgmt |
| **Snow Family (Snowcone/Snowball/Snowmobile)** | Edge and migration devices for rugged or disconnected environments. | Offline transfer • Edge compute/ML • Petabyte scale |
## Media, Communications & Business Apps
| Service (short) | Description | What it offers |
|---|---|---|
| **Chime SDK / SDK Media Services** | Real‑time audio/video and messaging APIs. | WebRTC • PSTN via Voice Connector |
| **Connect** | Omnichannel, cloud‑based contact center. | Agent workspace • IVR/Chat/Voice • Wisdom & Tasks |
| **Elemental MediaConnect** | Reliable, secure transport for live video. | Contribution/distribution • Encryption |
| **Elemental MediaConvert** | File‑based video transcoding. | Broadcast‑grade • OTT packaging |
| **Elemental MediaLive** | Live video encoding. | Redundancy • Adaptive bitrate |
| **Elemental MediaPackage** | Just‑in‑time packaging and origin. | HLS/DASH/CMAF • DRM |
| **Elemental MediaStore** | Media‑optimized storage with low latency. | HTTP origin • Consistent performance |
| **Elemental MediaTailor** | Server‑side ad insertion (SSAI). | Personalized ads • Measurement |
| **Deadline Cloud** | Managed render farm control plane for media & VFX. | Burst to cloud • Queue mgmt • Licensing integration |
| **Nimble Studio** | Build creative studios in the cloud. | Remote workstations • Collaboration |
| **Pinpoint** | Customer engagement for SMS, email, push, and in‑app messaging. | Journeys • Segmentation • Personalization |
| **SES** | Scalable, reliable email sending and receiving. | Deliverability tools • Inbound processing |
## Blockchain, Quantum, Satellite & GameTech
| Service (short) | Description | What it offers |
|---|---|---|
| **Braket** | Fully managed service for quantum computing and hybrid jobs. | Managed notebooks • Simulators • Devices |
| **Ground Station** | Satellite communications as a service. | Antenna time • Downlink to S3/EC2 |
| **Managed Blockchain** | Managed Hyperledger Fabric and (where available) Ethereum. | Network setup • CA/orderers • Scaling |
| **GameLift** | Managed dedicated game servers at scale. | Matchmaking • Autoscaling • FleetIQ |
## End‑User Computing & Productivity
| Service (short) | Description | What it offers |
|---|---|---|
| **AppStream 2.0** | Stream desktop applications securely to any browser. | GPU support • Scaling fleets • DCV streaming |
| **WorkDocs** | Secure content collaboration and file sharing. | Versioning • Permissions • SDK |
| **WorkMail** | Secure business email and calendaring. | Interop with Exchange • Mobile access |
| **WorkSpaces / WorkSpaces Web** | Persistent cloud desktops and secure browser access. | Windows/Linux desktops • Browser isolation |
## Migration & Transfer
| Service (short) | Description | What it offers |
|---|---|---|
| **Application Migration Service (MGN)** | Lift‑and‑shift server migration with block‑level replication. | Low downtime • Test cutovers • Orchestration |
| **Database Migration Service (DMS)** | Migrate and replicate databases continuously. | CDC • Validation • Heterogeneous targets |
| **Mainframe Modernization** | Tools and managed runtime to modernize and run mainframe workloads. | Refactor/replatform • Blu Age & Micro Focus runtimes |
| **Migration Hub** | Centralize and track migrations across tools and services. | Strategy recommendations • Orchestrator playbooks |
| **Snow Family** | Edge devices for data migration and edge compute. | Offline transfer • Edge ML/IoT |
| **Transfer Family** | Managed SFTP/FTPS/FTP and AS2 to S3/EFS. | Workflows • PGP • Directory/IdP integration |
# Domain 4 — Billing & Pricing
## Cost Management & Optimization
| Service (short) | Description | What it offers |
|---|---|---|
| **AWS Cost & Usage Report (CUR)** | Granular billing and usage data delivered to S3. | Athena/QuickSight ready • Hourly/daily detail • Cost categories |
| **Budgets** | Set custom cost and usage budgets with alerts and actions. | Cost/Usage/RI/SP coverage • Notifications • Auto adjustments |
| **Compute Optimizer** | ML‑based right‑sizing and optimization recommendations. | EC2/EBS/EKS/ASG • Cost vs performance |
| **Cost Explorer** | Visualize, analyze, and forecast AWS costs and usage. | Filtering & grouping • Forecasts • Anomaly detection |
| **Savings Plans** | Flexible pricing for compute usage (EC2, Fargate, Lambda). | 1/3‑year terms • Compute/EC2 plans • Coverage reports |
| **Reserved Instances** | Pricing discounts and (optionally) capacity reservations for eligible services. | Standard/Convertible • Zonal/Regional |
## Billing, Accounts & Marketplace
| Service (short) | Description | What it offers |
|---|---|---|
| **AWS Billing Console** | Manage payments, invoices, tax settings, and account billing preferences. | Budgets & alerts • Cost categories • Tax & credits |
| **Consolidated Billing (via Organizations)** | Single invoice and shared discounts across accounts. | Central visibility • Volume discounts |
| **Marketplace** | Catalog of third‑party software and data products with AWS‑integrated billing. | Private offers • AMI/SaaS contracts • Seller reports |
