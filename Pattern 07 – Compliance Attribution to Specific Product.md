# Pattern 7 – Compliance Attribution to Specific Product

## Title

Compliance attribution to specific product 

## Patlet

Software which needs to comply with regulatory requirements needs domain knowledge and attribution of compliance requirements to the product which might be outside the expertise of the contributing teams. Specific regulatory requirements can be complied with by attributing compliance to a specific product and associating with the repository used to build the product.

## Problem

Regulatory or taxation requirements specific to the industry sector (e.g., finance, healthcare) require a refined understanding and application of the compliance requirements to products. If the maintenance team is working on software which is subject to stringent requirements around quality management and traceability, this might prevent contributions from other teams in the organization.

## Context

- Collaboration in InnerSource projects is, to a large degree, cross-divisional and international (P09).
- In sectors with strong regulatory requirements, it is very important to integrate compliance in processes around InnerSource and Open Source (P14).

## Forces

- If business units find it difficult to ensure compliance across cross-divisional and multi-region projects, they can be tempted to limit collaboration between teams.
- If the maintenance team is working on software which is subject to stringent requirements around quality management and traceability, this might prevent contributions from other teams in the organization (P04, P23).

## Solutions

- The responsibility of complying with regulatory requirements is with the projects or components which use InnerSource-d software (P09, P11). In cases where there are different components, each component is responsible for complying with requirements.

## Resulting Context

- Distributing compliance responsibilities at the project and component level ensures compliance and takes the burden off from contributors (P09).

## Limitation/Blockers

- This pattern is not applicable when compliance is built into the organization's engineering processes which means all projects whether InnerSource-d or not need to comply with requirements (P01, P04).

## Known Instances

- This pattern has been identified by three panelists (P09, P11, and P25) to have been implemented in their organizations.
