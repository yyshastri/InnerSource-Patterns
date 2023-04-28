# Pattern 8 – Clear Demarcation of Responsibility to Comply with Requirements

## Title

Clear demarcation of responsibility to comply with requirements 

## Patlet

Software which needs to comply with regulatory requirements needs domain knowledge and can discourage contributions from other teams. In globally distributed organizations, compliance responsibilities can be distributed between the team who maintain the source code and the collaborators who could be using the code for specific product in their region.

## Problem

Regulatory or taxation requirements specific to industry sector (e.g., finance, healthcare) require a refined understanding and application of the compliance requirements to products. If the maintenance team is working on software which is subject to stringent requirements around quality management and traceability, this might prevent contributions from other teams in the organization.

## Context

- Collaboration in InnerSource projects is, to a large degree, cross-divisional and international (P09).
- In sectors with strong regulatory requirements, it is very important to integrate compliance in processes around InnerSource and Open Source (P14).

## Forces

- If the maintenance team is working on software which is subject to stringent requirements around quality management and traceability, this might prevent contributions from other teams in the organization (P04, P23).

## Solutions

- The contributing guidelines make it clear that responsibility for compliance is with the maintaining team and not with contributors from other parts of the organization (P01, P11, P23). This avoids reluctance of people to contribute to projects.

## Resulting Context

- Distributing compliance responsibilities at the project and component level ensures compliance and takes the burden off from contributors (P09).

## Limitation/Blockers

- This pattern is not applicable when compliance is built into the organization's engineering processes which means all projects whether InnerSource-d or do not need to comply with requirements (P01, P04).

## Known Instances

- This pattern has been identified by three panelists (P09, P11, and P25) to have been implemented in their organizations.

