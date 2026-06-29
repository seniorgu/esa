# Enterprise Solution Architecture (ESA) - Assistive Element Options

These assistive element options (Part 3) are additional elements beyond the foundational (base) elements and assistive elements ([Part 1 & Part 2 Elements](esa-element-definition.md)). They are not required in ESA but are often used for habitual diagramming or easier understanding.

## Part 3. Assistive Elements Options

| Category    | Assistive Element Option         | Base Element Mapping              | Implication              |
| ----------- | -------------------------------- | --------------------------------- | ------------------------ |
| Business    | Value Stream                     | Value, Process                    |                          |
| Business    | Function                         | Generic Service                   | Business Service         |
| Business    | Analytics                        | Middleware                        |                          |
| Business    | Activity                         | Task                              |                          |
| Functional  | API                              | Service Interface                 | Gateway                  |
| Functional  | Bounded Context                  | Domain                            |                          |
| Functional  | Browser                          | User Interface                    |                          |
| Functional  | Domain Service                   | Generic Service                   |                          |
| Functional  | Domain Specific Language (DSL)   | Artifact                          |                          |
| Functional  | Entity                           | Artifact                          | Object                   |
| Functional  | Function (FaaS)                  | Service Component                 |                          |
| Functional  | Generic Implementation           | Tech Service                      | DevOps                   |
| Functional  | Message                          | Data Service                      |                          |
| Functional  | Model                            | Artifact                          |                          |
| Functional  | Session                          | Data Service                      |                          |
| Functional  | Trigger                          | Connection                        | Directional Relationship |
| General     | Collaboration                    | Virtual Service                   |                          |
| General     | Config File                      | Virtual Service                   |                          |
| General     | Document File                    | Artifact                          |                          |
| General     | Facility                         | Extension                         |                          |
| General     | Item(s)                          | Artifact                          |                          |
| General     | Material                         | Extension                         |                          |
| General     | Partition                        | Domain                            | Isolation                |
| General     | Resource Group                   | Grouping                          |                          |
| General     | Sample Data                      | Artifact                          |                          |
| General     | Tabular Data Info                | Artifact                          |                          |
| Metrics     | Arch Decision Record             | Artifact, Key Choice              |                          |
| Metrics     | Goal                             | Requirement, Intent               |                          |
| Metrics     | NFR                              | Requirement                       |                          |
| Metrics     | Rule                             | Requirement                       |                          |
| Ops & Infra | Cell                             | Domain                            |                          |
| Ops & Infra | Cluster                          | Domain                            |                          |
| Ops & Infra | Container                        | Virtual Service                   |                          |
| Ops & Infra | Environment                      | Domain                            |                          |
| Ops & Infra | Event Broker                     | Middleware                        | Service Broker           |
| Ops & Infra | Event Queue                      | Tech Service, Middleware          |                          |
| Ops & Infra | Message Broker                   | Middleware                        | Service Broker           |
| Ops & Infra | Message Queue                    | Tech Service, Middleware          |                          |
| Ops & Infra | Mobile Device                    | User Interface, System<br> Device |                          |
| Ops & Infra | OS                               | Node, Node Property               |                          |
| Ops & Infra | PC Device                        | User Interface, System<br> Device |                          |
| Ops & Infra | Platform                         | Domain                            |                          |
| Ops & Infra | Queue Manager                    | Middleware                        | Service Broker           |
| Ops & Infra | Region                           | Location, Domain                  |                          |
| Ops & Infra | Router                           | Middleware                        | Switch                   |
| Ops & Infra | Runtime Application              | Deployment Package, Application   |                          |
| Ops & Infra | Signal                           | Connection                        | Directional Relationship |
| Ops & Infra | Stream                           | Data Service                      | Workflow                 |
| Ops & Infra | Virtual Node                     | Virtual Service                   |                          |
| Ops & Infra | Firewall                         | Middleware, Extension             |                          |
| Ops & Infra | Switch                           | Middleware, Extension             |                          |
| Ops & Infra | Server                           | Middleware                        |                          |
| Ops & Infra | Device                           | System                            |                          |
| Ops & Infra | Storage                          | Data Store, Extension             |                          |
| Ops & Infra | Virtual Server                   | Virtual Service, Middleware       |                          |
| Ops & Infra | Security (Threat & Preventation) | Requirement, Governance           |                          |
| Ops & Infra | Rack                             | Extension                         |                          |
