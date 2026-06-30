# Enterprise Solution Architecture (ESA) - Assistive Element Options

These assistive element options (Part 3) are additional elements beyond the foundational (base) elements and assistive elements ([Part 1 & Part 2 Elements](esa-element-definition.md)). They are not required in ESA but were selectively used for habitual diagramming or easier understanding in specific profile modes.

## Part 3. Assistive Elements Options

| Category    | Assistive Element Option         | Prefix | Base Element Mapping              | Implication              |
| ----------- | -------------------------------- | ------ | --------------------------------- | ------------------------ |
| Business    | Value Stream                     | VP     | Value, Process                    |                          |
| Business    | Function                         | BF     | Generic Service                   | Business Service         |
| Business    | Analytics                        | AA     | Middleware                        |                          |
| Business    | Activity                         | AV     | Task                              |                          |
| Functional  | API                              | PI     | Service Interface                 | Gateway                  |
| Functional  | Bounded Context                  | BC     | Domain                            |                          |
| Functional  | Browser                          | BR     | User Interface                    |                          |
| Functional  | Domain Service                   | DE     | Generic Service                   |                          |
| Functional  | Domain Specific Language (DSL)   | SL     | Artifact                          |                          |
| Functional  | Entity                           | EN     | Artifact                          | Object                   |
| Functional  | Function (FaaS)                  | FC     | Service Component                 |                          |
| Functional  | Implementation                   | IM     | Tech Service                      | DevOps                   |
| Functional  | Message                          | MG     | Data Service                      |                          |
| Functional  | Model                            | ML     | Artifact                          |                          |
| Functional  | Session                          | SS     | Data Service                      |                          |
| Functional  | Trigger                          | TG     | Connection                        | Directional Relationship |
| General     | Collaboration                    | VC     | Virtual Service                   |                          |
| General     | Config File                      | CF     | Virtual Service                   |                          |
| General     | Document File                    | DF     | Artifact                          |                          |
| General     | Facility                         | FA     | Extension                         |                          |
| General     | Item(s)                          | II     | Artifact                          |                          |
| General     | Material                         | MA     | Extension                         |                          |
| General     | Partition                        | PA     | Domain                            | Isolation                |
| General     | Resource Group                   | RS     | Grouping                          |                          |
| General     | Sample Data                      | SD     | Artifact                          |                          |
| General     | Tabular Data Info                | TD     | Artifact                          |                          |
| Metrics     | Arch Decision Record             | AD     | Artifact, Key Choice              |                          |
| Metrics     | Goal                             | GL     | Requirement, Intent               |                          |
| Metrics     | NFR                              | NF     | Requirement                       | RQ-NFR                   |
| Metrics     | Rule                             | RL     | Requirement                       | RQ-RL                    |
| Ops & Infra | Cell                             | CE     | Domain                            |                          |
| Ops & Infra | Cluster                          | CT     | Domain                            |                          |
| Ops & Infra | Container                        | CR     | Virtual Service, Domain           |                          |
| Ops & Infra | Environment                      | EV     | Domain                            |                          |
| Ops & Infra | Event Broker                     | EB     | Middleware                        | Service Broker           |
| Ops & Infra | Event Queue                      | EQ     | Tech Service, Middleware          |                          |
| Ops & Infra | Message Broker                   | MB     | Middleware                        | Service Broker           |
| Ops & Infra | Message Queue                    | MQ     | Tech Service, Middleware          |                          |
| Ops & Infra | Mobile Device                    | MD     | User Interface, System<br> Device |                          |
| Ops & Infra | OS (*Operating System*)          | OS     | Node, Node Property               |                          |
| Ops & Infra | PC Device                        | PC     | User Interface, System<br> Device |                          |
| Ops & Infra | Platform                         | PL     | Domain                            |                          |
| Ops & Infra | Queue Manager                    | QU     | Middleware                        | Service Broker           |
| Ops & Infra | Region                           | RG     | Location, Domain                  |                          |
| Ops & Infra | Router                           | RT     | Middleware, Extension             | Switch, Hub              |
| Ops & Infra | Runtime Application              | RA     | Deployment Package, Application   |                          |
| Ops & Infra | Signal                           | SG     | Connection                        | Directional Relationship |
| Ops & Infra | Streaming                        | SA     | Data Service                      | Workflow                 |
| Ops & Infra | Virtual Node                     | VN     | Virtual Service                   |                          |
| Ops & Infra | Firewall                         | FI     | Middleware, Extension             |                          |
| Ops & Infra | Server                           | SR     | Middleware                        |                          |
| Ops & Infra | Device                           | DV     | System                            |                          |
| Ops & Infra | Storage                          | SE     | Data Store, Extension             |                          |
| Ops & Infra | Virtual Server                   | VE     | Virtual Service, Middleware       |                          |
| Ops & Infra | Security (Threat & Preventation) | TH     | Requirement, Governance           |                          |
| Ops & Infra | Rack                             | RC     | Extension                         |                          |
