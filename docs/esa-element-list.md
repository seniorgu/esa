# Enterprise Solution Architecture (ESA) Element List

## Part 1. Foundational (Base) Element List

| Category                     | Element                 | Prefix | Implication                                                  | Base Mapping |
| ---------------------------- | ----------------------- | ------ | ------------------------------------------------------------ | ------------ |
| Intent & Metrics             | Intent  (Optional)      | IT     | Value, Objective                                             |              |
| Intent & Metrics             | Capability              | CP     | Value, Service  Capability                                   |              |
| Intent & Metrics             | Use Case                | UC     | Case Scenario,  User Story                                   |              |
| Intent & Metrics             | Principle               | PR     | Policy                                                       |              |
| Intent & Metrics             | Risk                    | RK     | Constraints                                                  |              |
| Intent & Metrics             | Requirement             | RQ     | Non-Functional  Requirement, Rule                            |              |
| Intent & Metrics             | Key Choice              | KC     | Key Decision and  Consideration                              |              |
| Intent & Metrics             | Governance              | GV     | Validation                                                   |              |
| Functional -Application      | Access  Interface       | UI     | GUI, CLI, Voice,  Media                                      |              |
| Functional / Application     | App Logic               | AS     |                                                              |              |
| Functional / Application     | Data Service            | DS     | Data Object, Data  Federation                                |              |
| Functional / Application     | Technical  Service      | TS     | Utility Service                                              |              |
| Functional / Application     | Interface               | SI     | Service  Interface, API                                      |              |
| Functional / Application     | Service  Component      | SC     |                                                              |              |
| Functional / Application     | Application             | AP     |                                                              |              |
| Operational / Infrastructure | Deployment  Package     | DP     | Deployment Unit                                              |              |
| Operational / Infrastructure | Data Store              | DB     |                                                              |              |
| Operational / Infrastructure | Middleware              | MW     |                                                              |              |
| Operational / Infrastructure | Node                    | ND     |                                                              |              |
| Operational / Infrastructure | System                  | SY     | Device                                                       |              |
| Operational / Infrastructure | Network                 | NW     |                                                              |              |
| Operational / Infrastructure | Location                | LO     |                                                              |              |
| General                      | Role                    | RO     | Actor,  Stakeholder                                          |              |
| General                      | Task                    | TK     | Activity, State                                              |              |
| General                      | Process                 | PS     | Workflow,  Composite Service                                 |              |
| General                      | Domain                  | DM     | Bounded Context,  Platform, Zone, etc.                       |              |
| General                      | Grouping                | GP     | Group                                                        |              |
| General                      | View Frame              | VF     | Partial View                                                 |              |
| General                      | Generic Service         | GS     | Conceptual  Service                                          |              |
| General                      | Virtual Service         | VS     | Configuration,  Collaboration                                |              |
| General                      | Deliverable  (Optional) | DL     |                                                              |              |
| General                      | Artifact                | AR     | Tangible Asset,  Document                                    |              |
| General                      | Note                    | NT     | Key Element  Properties                                      |              |
| General                      | Input  (Optional)       | IN     |                                                              |              |
| General                      | Output  (Optional)      | OU     |                                                              |              |
| General                      | Extension               | EX     | External  system/solution element                            |              |
| Connection                   | Association             | AN     |                                                              |              |
| Connection                   | Flow                    | FW     | Directional,  Access, Triggering, Serving,  Influence, Dependency. |              |
| Connection                   | Composition  (Optional) | CM     |                                                              |              |
| Connection                   | Realization  (Optional) | RN     |                                                              |              |

## Part 2. Assistive Element List

| Category                  | Element               | Prefix | Implication                          | Base Mapping                      |
| ------------------------- | --------------------- | ------ | ------------------------------------ | --------------------------------- |
| Solution Management       | Issue &  Constraint   | CS     | Problem                              | Risk                              |
| Solution Management       | Stage                 | ST     | Product, Solution  Model, View Frame | Deliverable                       |
| Architectural Style       | Frontend              | FE     |                                      | System Device                     |
| Architectural Style       | Cloud                 | CL     |                                      | Domain                            |
| Architectural Style       | Microservice          | MS     |                                      | Generic Service,  Deployment Unit |
| Architectural Style       | Event Service         | ES     |                                      | Tech Service                      |
| DevOps                    | Quality Metric        | QM     |                                      | Requirement                       |
| DevOps                    | Governance  Function  | GF     |                                      | Governance                        |
| DevOps                    | Quality &  Adaptation | QV     |                                      | Governance, View  Frame           |
| DevOps                    | Governance  Control   | GO     | Governance  Operation                | Governance                        |
| Software Design           | Object                | OB     | Entity, Component                    | Service Component                 |
| Software Design           | Module                | MO     |                                      | Domain                            |
| Software Design           | Data File             | TB     | Table, File,  Artifact               | Artifact                          |
| Software Design           | Schema                | SM     |                                      | Domain                            |
| Software Design           | Transaction           | TR     |                                      | Domain                            |
| Software Design           | Repository  & Library | RP     |                                      | Artifact                          |
| Integration & Scalability | Message Service       | MG     |                                      | Data Service                      |
| Integration & Scalability | Edge &  Adapter       | EG     |                                      | Middleware                        |
| Integration & Scalability | Gateway Service       | GW     |                                      | Middleware                        |
| Integration & Scalability | Service Broker        | SB     |                                      | Middleware                        |
| Integration & Scalability | Cache Service         | CA     |                                      | Data Service                      |
| AI-Specific               | Agent                 | AG     |                                      | Generic Service,  App Logic       |
| AI-Specific               | AI Coordinator        | AC     |                                      | Process                           |
| AI-Specific               | Context State         | CN     |                                      | Data Service                      |
| AI-Specific               | Model &  Reasoning    | ML     |                                      | Data Service                      |
| AI-Specific               | Knowledge  Access     | KA     |                                      | Data Service                      |
| AI-Specific               | Tool &  Action        | TL     |                                      | Tech Service                      |
| AI-Specific               | AI/ML Lifecycle       | AL     |                                      | Process,  Capability              |
| Business                  | Product               | PD     |                                      | Deliverable                       |
| Business                  | Value                 | VL     |                                      | Intent                            |
| Infrastructure            | Zone                  | ZN     | Domain                               | Group                             |
| Infrastructure            | Tier                  | TE     |                                      | Domain                            |
| Assistive Options         | OS                    | ND     |                                      | Node                              |
| Assistive Options         | Firewall              | NW     |                                      | Network                           |
| Assistive Options         | Switch                | NW     | Hub                                  | Network                           |
| Assistive Options         | Server                | MW     |                                      | Middleware                        |
| Assistive Options         | Device                | SY     |                                      | System                            |
| Assistive Options         | Storage               | SY     |                                      | Data Store,  System Device        |
| Assistive Options         | Virtual Server        | VS     |                                      | Virtual Service                   |
| Assistive Options         | Security Threat       | RK     |                                      | Risk                              |
| Assistive Options         | Rack                  | EX     |                                      | Extension                         |
| Assistive Options         | Function              | GS     |                                      | Generic Service,  Use Case        |
| Assistive Options         | Analytics             | MW     |                                      | Middleware                        |
| Assistive Options         | Activity              | TK     |                                      | Task                              |
| Assistive Options         | Value Stream          | PS     |                                      | Process                           |





