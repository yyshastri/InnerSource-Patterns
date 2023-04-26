# Pattern 14 – Create a Unified Code Repository

## Title

Create a unified code repository 

## Patlet

Existing technology infrastructure can pose problems with code transparency and the interconnections with different elements can further complicate this scenario. Creation of a unified source code inventory which collects IS and legacy repositories in one place will help in preventing duplication and enhance transparency.

## Problem

Technology framework covers infrastructure areas such as development environment, tool stacks, and platforms. One of the issues is the organization trying to adapt the existing tool stack to InnerSource. Another issue is a lack of transparency which makes it difficult to scan code bases for duplication, poor code, and technical debt. The dynamic nature of the infrastructure with a complex web of relationships between different elements (projects, repositories, products etc.) also causes issues.

## Context

- Visibility of code assets is needed to prevent stale code and code duplication.
- Having a good API for the tool stack is essential to extract the relevant project information, do automation, and monitoring for IS projects (P11).
- Lack of transparency can create barriers where contributors are not able to see if their contributions have passed Continuous Integration (CI) (P20).

## Forces

- Multiple business units each with their own platforms (e.g., GitLab, Azure DevOps) leads to fragmented tooling and problems in adopting IS (P17, P23).

## Solutions

- Creation of a unified source code inventory which collects IS and legacy repositories in one place will help in preventing duplication and enhance transparency.

## Resulting Context

- Code contribution and code scanning inside organization becomes simple with a unified repository (P03, P23).
- IS implementation becomes easier when compared to adapting IS to fragmented repositories (P08).

## Limitation/Blockers

- In case of large organizations, the effort of identifying duplicate code and assigning to shared repositories outweighs the benefits (P01, P04,P09,P11).
- Discoverability of the new shared repository can be an issue (P04).
- Tool migration requires dedicated time, effort, and support (P23).

## Known Instances

- This pattern has been identified by 5 panelists (P03, P08, P09, P17, P18, P23,and P25) to have been implemented in their organizations.
