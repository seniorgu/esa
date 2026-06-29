# ESA Mapping with Cloud Platforms

In reality, many enterprise solutions are complex, beyond the cloud platform solutions. Even when your enterprise fully depends on the cloud platform, you still need to have a clear ESA for a better understanding of your IT architecture, beyond the technical platform. 
Cloud platforms basically provide a bunch of cloud-based middleware or services. Instead of developing and hosting on your own, you depend on the cloud platform as a service, whether SaaS, PaaS or IaaS. 

Through a mapping between your solution and your chosen cloud service (iteratively for the changes), you can achieve the following:

- Choose the cloud middleware products as part of your architectural trade-off analysis through an ESA modeling mapping, as each solution has a different focus and therefore different mapping considerations.
- Focus on the middleware that matters more to your enterprise solution, especially as part of your value, governance, risk, and data service/store considerations.
  1. Focus less on the basic middleware of technical nature, which is part of your solution’s operational infrastructure – the platform takes care of the details.
  2. Pay more attention to your use case and metric elements for the business benefits. The cloud platform provides strong capabilities for monitoring and statistics, but it’s up to you to make the solution decisions.
  3. Especially when you're hosting your solution applications on a cloud platform, your application architecture and deployment strategy still matter as in-house development, because the hard part of scalability often sits at the application layer.
- Have an overall picture of how the cloud platform is integrated with your solution, and what the long-term impact (adaptability and cost-effectiveness).
  1. Instead of solely relying on the architectural views generated from the cloud platform, you need to walk through your significant case scenario(s) for validation and governance decisions.
  2. Keep all critical solution architecture info in the ESA model, rather than relying on detailed and unmanageable documentation. An effective and visual model amplifies your architectural thinking process.

In short, for your cloud-based solution, do an initial mapping of the cloud middleware (see the following example), build your ESA model views via iterations, and have a systematic view (intent, functional, operational, and integration) of your solutions.

---

## A Brief Example Mapping between the Google Cloud and ESA

| Category                            | Produce & Service                            | ESA Base Mapping  | ESA Assistive Mapping |
| ----------------------------------- | -------------------------------------------- | ----------------- | --------------------- |
| Cross-product tools                 | Cloud Billing                                | Value             | Analytics             |
| Cross-product tools                 | Cloud Identity                               | Risk              | Security              |
| Cross-product tools                 | Cloud Quotas                                 | Value             | Analytics             |
| Cross-product tools                 | Config Connector                             | Middleware        |                       |
| Cross-product tools                 | Deployment Manager                           | Deployment Unit   |                       |
| Cross-product tools                 | Identity Platform                            | Risk              | Security              |
| Cross-product tools                 | Infra Manager                                | Node              |                       |
| Cross-product tools                 | Managed Microsoft AD                         | Middleware        |                       |
| Cross-product tools                 | Recommender                                  | Middleware        | Analytics             |
| Cross-product tools                 | Service Catalog                              | Data Store        |                       |
| Cross-product tools                 | Service Usage                                | Governance        | Analytics             |
| AI and ML                           | Cloud TPU                                    | Node              |                       |
| AI and ML                           | Colab Enterprise                             | Middleware        |                       |
| AI and ML                           | Deep Learning Containers                     | Middleware        |                       |
| AI and ML                           | Deep Learning VM                             | Middleware        |                       |
| AI and ML                           | DocAI                                        | Middleware        |                       |
| AI and ML                           | Enterprise Knowledge Graph                   | Middleware        |                       |
| AI and ML                           | Speech-to-Text                               | Middleware        |                       |
| AI and ML                           | TensorFlow Enterprise                        | Middleware        |                       |
| AI and ML                           | Text-to-Speech                               | Middleware        |                       |
| AI and ML                           | Translation                                  | Middleware        |                       |
| AI and ML                           | Vertex AI                                    | Middleware        |                       |
| AI and ML                           | Vertex AI Vision                             | Middleware        |                       |
| AI and ML                           | Vertex AI Workbench                          | Domain            | Platform              |
| AI and ML                           | Vision API                                   | Service Interface |                       |
| App development                     | API Gateway                                  | Middleware        |                       |
| App development                     | Apigee                                       | Middleware        |                       |
| App development                     | App Hub                                      | Middleware        | Analytics             |
| App development                     | Application Integration                      | Middleware        |                       |
| App development                     | Artifact Analysis                            | Risk              | Analytics             |
| App development                     | Cloud Build                                  | Domain            | Platform              |
| App development                     | Cloud Code                                   | Middleware        |                       |
| App development                     | Cloud Deploy                                 | Middleware        |                       |
| App development                     | Cloud Scheduler                              | Middleware        |                       |
| App development                     | Cloud Shell                                  | Middleware        |                       |
| App development                     | Cloud Tasks                                  | Middleware        |                       |
| App development                     | Cloud Workstations                           | Middleware        |                       |
| App development                     | Developer Connect                            | Middleware        |                       |
| App development                     | Eventarc                                     | Middleware        |                       |
| App development                     | gcloud CLI                                   | Middleware        |                       |
| App development                     | Integration Connectors                       | Middleware        |                       |
| App development                     | Pub/Sub                                      | Middleware        |                       |
| App development                     | Secure Source Manager                        | Middleware        |                       |
| App development                     | Service Infrastructure                       | Domain            | Platform              |
| App development                     | Software supply chain security               | Requirement       | Security              |
| App development                     | Workflows                                    | Process           |                       |
| App hosting                         | App Engine                                   | Node              |                       |
| App hosting                         | Blockchain Node Engine                       | Node              |                       |
| App hosting                         | Blockchain RPC                               | Middleware        |                       |
| App hosting                         | Cloud Run                                    | Node              | Virtual Node          |
| App hosting                         | Google Kubernetes Engine (GKE)               | Node              | Virtual Node          |
| Compute                             | AI Hypercomputer                             | Node              |                       |
| Compute                             | Batch                                        | Middleware        |                       |
| Compute                             | Capacity Planner                             | Middleware        |                       |
| Compute                             | Cluster toolkit                              | Deployment Unit   |                       |
| Compute                             | Compute Engine                               | Node              |                       |
| Compute                             | Migrate to Containers                        | View Frame        |                       |
| Compute                             | Migrate to VMs                               | View Frame        |                       |
| Compute                             | Migration Center                             | View Frame        |                       |
| Compute                             | Shielded VMs                                 | Node              | Security              |
| Compute                             | VM Manager                                   | Node              | Virtual Node          |
| Compute                             | VMware Engine                                | Node              | Virtual Node          |
| Compute                             | Workload Manager                             | Node              | Rule                  |
| Data analytics and pipelines        | BigQuery                                     | Data Service      | Analytics             |
| Data analytics and pipelines        | Blockchain Analytics                         | Data Service      | Analytics             |
| Data analytics and pipelines        | Cloud Data Fusion                            | Data Service      | Analytics             |
| Data analytics and pipelines        | Dataflow                                     | Data Service      | Analytics             |
| Data analytics and pipelines        | Dataform                                     | Data Service      | Analytics             |
| Data analytics and pipelines        | Datastream                                   | Data Service      | Analytics             |
| Data analytics and pipelines        | Knowledge Catalog                            | Data Service      | Analytics             |
| Data analytics and pipelines        | Lakehouse                                    | Data Service      | Analytics             |
| Data analytics and pipelines        | Looker                                       | Data Service      | Analytics             |
| Data analytics and pipelines        | Managed Service for Apache Airflow           | Data Service      | Analytics             |
| Data analytics and pipelines        | Managed Service for Apache Spark             | Data Service      | Analytics             |
| Databases                           | AlloyDB for PostgreSQL                       | Data Store        | Analytics             |
| Databases                           | Bigtable                                     | Data Store        | Analytics             |
| Databases                           | Cloud SQL                                    | Data Store        | Analytics             |
| Databases                           | Database Migration Service                   | Data Store        | Analytics             |
| Databases                           | Firestore                                    | Data Store        | Analytics             |
| Databases                           | Memorystore for Memcached                    | Data Store        | Analytics             |
| Databases                           | Spanner                                      | Data Store        | Analytics             |
| Distributed, hybrid, and multicloud | GKE Multi-Cloud                              | Domain            | Platform              |
| Industry solutions                  | Anti Money Laundering AI (AML AI)            | Use Case          |                       |
| Industry solutions                  | Healthcare Data Engine                       | Use Case          |                       |
| Industry solutions                  | Talent Solutions                             | Use Case          |                       |
| Industry solutions                  | Telecom Network Automation                   | Use Case          |                       |
| Industry solutions                  | Telecom Subscriber Insights API              | Use Case          |                       |
| Industry solutions                  | Vertex AI Search for retail                  | Use Case          |                       |
| Networking                          | Cloud CDN                                    | Network           | Cloud                 |
| Networking                          | Cloud DNS                                    | Network           | Cloud                 |
| Networking                          | Cloud Intrusion Detection System (Cloud IDS) | Network           | Cloud                 |
| Networking                          | Cloud Interconnect                           | Network           | Cloud                 |
| Networking                          | Cloud Load Balancing                         | Network           | Cloud                 |
| Networking                          | Cloud NAT                                    | Network           | Cloud                 |
| Networking                          | Cloud Next Generation Firewall (Cloud NGFW)  | Network           | Cloud                 |
| Networking                          | Cloud Router                                 | Network           | Cloud                 |
| Networking                          | Cloud Service Mesh                           | Network           | Cloud                 |
| Networking                          | Cloud VPN                                    | Network           | Cloud                 |
| Networking                          | Google Cloud Armor                           | Network           | Cloud                 |
| Networking                          | Media CDN                                    | Network           | Cloud                 |
| Networking                          | Network Connectivity Center                  | Network           | Cloud                 |
| Networking                          | Network Intelligence Center                  | Network           | Cloud                 |
| Networking                          | Network Service Tiers                        | Network           | Cloud                 |
| Networking                          | Secure Web Proxy                             | Network           | Cloud                 |
| Networking                          | Service Extensions                           | Network           | Cloud                 |
| Networking                          | Virtual Private Cloud (VPC)                  | Network           | Cloud                 |
| Networking                          | VPC Service Controls                         | Network           | Cloud                 |
| Observability and monitoring        | Error Reporting                              |                   | Quality & Adaptation  |
| Observability and monitoring        | Logging                                      |                   | Quality & Adaptation  |
| Observability and monitoring        | Monitoring                                   |                   | Quality & Adaptation  |
| Observability and monitoring        | Profiler                                     |                   | Quality & Adaptation  |
| Observability and monitoring        | Trace                                        |                   | Quality & Adaptation  |
| Security                            | Access Context Manager                       | Middleware        | Quality & Adaptation  |
| Security                            | Access Transparency                          | Middleware        | Quality & Adaptation  |
| Security                            | Advisory Notifications                       | Middleware        | Quality & Adaptation  |
| Security                            | Assured OSS                                  | Middleware        | Security              |
| Security                            | Binary Authorization                         | Middleware        | Security              |
| Security                            | Certificate Authority                        | Middleware        | Security              |
| Security                            | Certificate Manager                          | Middleware        | Security              |
| Security                            | Chrome Enterprise Premium                    | Middleware        | Security              |
| Security                            | Cloud Asset Inventory                        | Middleware        | Security              |
| Security                            | Cloud KMS                                    | Middleware        | Security              |
| Security                            | Confidential VM                              | Middleware        | Security              |
| Security                            | Endpoint Verification                        | Middleware        | Security              |
| Security                            | Google SecOps                                | Governance        | Security              |
| Security                            | Identity and Access Management (IAM)         | Middleware        | Security              |
| Security                            | Identity-Aware Proxy                         | Middleware        | Security              |
| Security                            | Policy Intelligence                          | Governance        | Security              |
| Security                            | reCAPTCHA                                    | Middleware        | Security              |
| Security                            | Resource Manager                             | Governance        | Security              |
| Security                            | Secret Manager                               | Governance        | Security              |
| Security                            | Security Command Center                      | Risk              | Security              |
| Security                            | Sensitive Data Protection                    | Governance        | Security              |
| Security                            | Service Health                               | Governance        | Security              |
| Security                            | Web Risk                                     | Risk              | Security              |
| Storage                             | Backup and DR Service                        | Data Store        | Storage               |
| Storage                             | Cloud Storage                                | Data Store        | Storage               |
| Storage                             | Filestore                                    | Data Store        | Storage               |

## Source

- [Google Cloud products at a glance]([Google Cloud products at a glance  |  Google Cloud Documentation](https://docs.cloud.google.com/docs/product-list))
