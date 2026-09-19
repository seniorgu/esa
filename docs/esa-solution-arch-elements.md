# Solution Architecture Elements

> Part of Enterprise Solution Architecture (ESA) Elements

| Category               | Element          | Prefix | Implication    | Base Mapping          |
| ---------------------- | ---------------- | ------ | --------------------------------------------------- | --------------------- |
| Intent/Metrics         | User             | RO     | Stakeholder, Actor                                  | Role                  |
| Intent/Metrics         | Task             | TK     | Activity, Event                                     | Task                  |
| Intent/Metrics         | Requirement      | RQ     | Intent, Usa Case, Non-functional Requirement        | Requirement           |
| Intent/Metrics         | Decision         | KC     | Key Consideration, Governance                       | Key Choice            |
| Intent/Metrics         | Grouping         | GP     | Domain                                              | Grouping              |
| Functional/Application | App              | AP     | Agent                                               | Application           |
| Functional/Application | Access Interface | UI     | CLI, UI                                             | User/Access Interface |
| Functional/Application | Process          | PS     | Flow, Lifecycle                                     | Process               |
| Functional/Application | App Controller   | AS     | AI Coordinator                                      | App Logic Service     |
| Functional/Application | Data Module      | DS     | Knowledge Access                                    | Data Service          |
| Functional/Application | AI Model         | ML     | LLM                                                 | Data Service          |
| Functional/Application | Context          | CN     | State, Memory                                       | Data Service          |
| Functional/Application | Message          | MG     | Event Service                                       | Data Service          |
| Functional/Application | Utility Service  | TS     | Tool                                                | Tech Service          |
| Functional/Application | Microservice     | MS     | Service, Domain                                     | Deployment Package    |
| Operational/Middleware | Frontend Device  | FE     | Mobile Device, PC Device                            | System/Device         |
| Operational/Middleware | System           | SY     | Device, ERP App                                     | System                |
| Operational/Middleware | Database         | DB     | Storage                                             | Data Store            |
| Operational/Middleware | Node             | ND     | Server, Deployment Unit                             | Node                  |
| Operational/Middleware | Message Broker   | SB     | Service Broker                                      | Middleware            |
| Operational/Middleware | Observability    | GO     | Governance Control, Analytics, Quality & Adaptation | Middleware            |
| Operational/Middleware | Gateway          | GW     | API Gateway, Router                                 | Middleware            |
| Operational/Middleware | Firewall         | FI     | Security Threat                                     | Middleware            |
| Operational/Middleware | Cache            | CA     | CDN                                                 | Middleware            |
| Operational/Middleware | Cloud            | CL     | Cloud Service, Cloud Platform                       | Domain                |