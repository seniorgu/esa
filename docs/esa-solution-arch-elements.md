# Solution Architecture Elements

> Part of Enterprise Solution Architecture (ESA) Elements

| Category               | Element         | Prefix | Implication                                                         | Base Mapping                           |
| ---------------------- | --------------- | ------ | ------------------------------------------------------------------- | -------------------------------------- |
| Intent/Metrics         | User            | RO     | Stakeholder, Actor                                                  | Role                                   |
| Intent/Metrics         | Task            | TK     | Activity, Event                                                     | Task                                   |
| Intent/Metrics         | Requirement     | RQ     | Intent, Non-functional Requirement                                  | Requirement                            |
| Intent/Metrics         | Decision        | KC     | Key Consideration, Governance                                       | Key Choice                             |
| Intent/Metrics         | Artifact        | AR     | Documentation, Repository, Code                                     | Artifact                               |
| Intent/Metrics         | Service         | GS     | Domain, Use Case                                                    | Generic Service, Service Definition    |
| Functional/Application | Application     | AP     | ERP App                                                             | Application                            |
| Functional/Application | AI Agent        | AG     | AI Bot                                                              | Agent                                  |
| Functional/Application | User Interface  | UI     | CLI, UI                                                             | User/Access Interface                  |
| Functional/Application | Process         | PS     | Flow, Lifecycle                                                     | Process                                |
| Functional/Application | App Controller  | AS     | AI Coordinator                                                      | App Logic Service                      |
| Functional/Application | Data Module     | DS     | Knowledge Access                                                    | Data Service                           |
| Functional/Application | AI Model        | ML     | LLM                                                                 | Data Service                           |
| Functional/Application | Context         | CN     | State, Memory                                                       | Data Service                           |
| Functional/Application | API Interface   | SC     |                                                                     | Service Interface                      |
| Functional/Application | Utility Service | TS     | Tool                                                                | Tech Service                           |
| Functional/Application | Component       | SC     | Object, Module                                                      | Service Component                      |
| Functional/Application | Microservice    | MS     | Self-contained Unit                                                 | Deployment Package                     |
| Operational/Middleware | Frontend        | FE     | Mobile Device, PC Device                                            | UI Service, Middleware                 |
| Operational/Middleware | System          | SY     | System Device                                                       | System                                 |
| Operational/Middleware | Database        | DB     | Storage                                                             | Data Store                             |
| Operational/Middleware | Deployment Unit | DP     |                                                                     | Deployment Package                     |
| Operational/Middleware | Node            | ND     | Server                                                              | Node                                   |
| Operational/Middleware | Service Broker  | SB     | Message Broker, Event Broker                                        | Middleware                             |
| Operational/Middleware | Message/Event   | MG     |                                                                     | Data Service, Tech Service, Middleware |
| Operational/Middleware | Monitoring      | GO     | Governance Control, Analytics, Observability,  Quality & Adaptation | Middleware, Governance                 |
| Operational/Middleware | Gateway         | GW     | API Gateway, Router                                                 | Middleware                             |
| Operational/Middleware | Security        | FI     | Security Threat, Virus Preventation Firewall                        | Middleware                             |
| Operational/Middleware | Caching         | CA     | CDN                                                                 | Middleware                             |
| Operational/Middleware | Cloud           | CL     | Cloud Service, Cloud Platform                                       | Domain, Location                       |