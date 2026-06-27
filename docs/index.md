# ESA Model

A Brief Introduction to the Enterprise Solution Architecture (ESA) Model

## Overview

Enterprise Solution Architecture (ESA) bridges **enterprise architecture** (EA) and **solution design and implementation** (SWD). It is an end-to-end architecture with **significant** concerns in mind and **simplicity** as an approach.

ESA cuts off the extreme ends of enterprise solutions. Traditionally, the top end includes detailed strategic planning & business architecture, and the bottom end includes detailed software design and infrastructure design. In the AI era, both ends are made much easier with AI assistance: EA now serves as the enterprise solution context curator, and SWD can be handled largely with AI. In contrast, ESA still plays a critical role as a model spec guidance and human governance for complex enterprise solutions.

AI is powerful in pattern recognition and pattern matching, but the architectural modeling process is pretty much for humans to direct and understand. The modern architecture requires a simple yet clear set of architectural elements across different levels or segments. ESA fits the role and serves as a **unified model** at an enterprise solution architecture level.

ESA sticks to an **S3 principle**: simple, significant, and systematic. The systematics or holistic approach is grounded in simplicity and significance.

## ESA Profile Modes

ESA is suitable for most types of IT solution architecture. It can be used widely as a single model spec and tools. The following table lists its primary usage and user groups.

| \#  | Profile Mode                                                      | Purpose                                                                                                                              | User Group                                                 |
| --- | ----------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------- |
| 1   | [Base Model](esa-base-elements.md)                                | Serves as a foundational model for effective consideration of enterprise solution architectural concerns following the S3 principle. | ESA architects                                             |
| 2   | [Standard Model](esa-element-list.md) (Base + Assistive Elements) | Provides a complete list of commonly used ESA elements in typical complex enterprise solutions.                                      | ESA architects                                             |
| 3   | [Lean Mode](esa-lean-mode-elements.md) (12 elements)              | Offers a simple set of elements for easier adoption and a quick ESA modeling                                                         | Agile practitioners, agile architects, and the like        |
| 4   | [EA Profile](esa-ea-profile-elements.md) (Enterprise Arch)        | Provides a list of elements at the enterprise architecture level in a simpler approach                                               | EA modelers and ArchiMate users.                           |
| 5   | [SWD Profile](esa-swd-profile-elements.md) (Software Design)      | Provides a list of elements for software design                                                                                      | UML users                                                  |
| 6   | [SWA Profile](esa-swa-profile-elements.md) (Software Arch)        | Provides a list of elements for software architectural design                                                                        | Software architects                                        |
| 7   | [AI Solution Profile](esa-ai-solution-elements.md)                | Provides a list of AI-specific and AI-related elements for a practical AI solution architecture                                      | AI solution architects                                     |
| 8   | [IS Profile](esa-is-elements.md) (Integration & Scalability)      | Provides a list of elements primarily used in integration or high-availability (HA) solutions                                        | Integration architects, ESA architects, and HA architects. |
| 9   | [BA Profile](esa-business-arch-elements.md) (Business Arch)       | Provides a list of elements for business architecture in a focused and simpler manner                                                | Business architects and enterprise architects              |
| 10  | [Infra Profile](esa-infra-arch-elements.md) (Infrastructure Arch) | Provides a list of elements for infrastructure architecture in a blueprint and guidance approach                                     | Infrastructure architects and network architects           |

ESA adopts an element-first approach. The foundational elements serve to judge your ESA model. For the completeness and soundness of your ESA model:

- You need to consider metric, functional, and operational elements from the enterprise, case scenario, and system perspectives.

- Your architectural tradeoffs and governance mechanisms need to be clearly reflected in the model.

- Typical end-to-end walk-through validation(s) are required to reach consensus among key stakeholders.

- Each profile model, as part of the holistic ESA model, needs to be validated from the foundational model.

The assistive and extension elements are primarily used for more granular specification and easy understanding. The tools will do the mapping with their corresponding foundational elements.

## ESA Views

ESA has a simple set of view specifications. As an agile architecture, ESA is more flexible in view definition. The following is a list of ESA views for your reference.

| Area          | ESA View                       | Note     |
| ------------- | ------------------------------ | -------- |
| Enterprise    | Capability                     |          |
| Enterprise    | Organization                   | Optional |
| Case Scenario | Use Case Model or Process View |          |
| Case Scenario | Page Flow View                 | Optional |
| Overview      | Enterprise Solution Overview   |          |
| Overview      | Pattern                        |          |
| Overview      | Metrics                        |          |
| Overview      | DevOps                         | Optional |
| Overview      | Validation                     |          |
| Functional    | Service Interaction            |          |
| Functional    | Service Relationship           |          |
| Functional    | Service Component Realization  | Optional |
| Operational   | Deployment Mapping             |          |
| Operational   | Operational View               |          |

These views reflect the overall ESA viewpoints. You can also use other views in commonly used model specifications. For example, when you use the SWD mode, you can reference the UML views.

Note that in ESA, the data architecture is not treated as a separate view, because it's cross-cutting, and should be clearly embodied in the ESA model views. The data service is the central part of the solution architecture, and should be given holistic consideration.

## Source

- *Agile Enterprise Solution Architecture - An IT Service-Based Modeling Approach*/Gu, Sean. Vernal Press, 2021/2026.
