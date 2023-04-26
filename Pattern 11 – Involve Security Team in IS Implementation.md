# Pattern 11 – Involve Security Team in IS Implementation

## Title

Involve security team in IS implementation 

## Patlet

The concerns of the security team regarding security of open repositories and lack of clarity regarding security policies can restrict access to code. This can be mitigated by creating awareness of the secure access guidelines by means of training sessions for contributors. Additionally, the lack of clarity in security policies around access and sharing levels can be resolved by involving the security team in the InnerSource implementation phase (C8).

## Problem

InnerSource implementation needs free sharing of code for collaboration whereas security concerns around code leakage and confidentiality require restricted access to the code. Also, a lack of clarity in security policies around access and sharing levels can be a security challenge.

## Context

- The core benefit of InnerSource i.e., openness is lost if code is not readily accessible by developers (P07). Additionally, a Single Sign On (SSO) type system needs to be in place for ease of access.
- Operational safety can be compromised if deficiencies exist in the security framework (P01).
- InnerSource projects need to be complaint with security to prevent leakage and conform with the engineering best practices of the organization (P04, P08).
- Due to lack of clear rules around repository access, visibility, and creation, there exist a multitude of visibility and access settings for repositories (P09).

## Forces

- Strong security concerns around leakage of customer data, injection of malicious code, and industrial sabotage can prevent open code.
- Inherited security constraints from existing projects make it difficult to reuse existing tools repositories (P07).
- Lack of awareness around security issues can lead to contributors inadvertently leaving confidential data in shared repositories.

## Solutions

- Awareness of the secure access guidelines can be created by means of dedicated training sessions (P11, P23).
- Another technique is to require developers to specify access (either shared or closed) every time they create a new repository.
- An appropriate security policy can be created by involving the security team in the IS implementation phase. This can be done via the creation of an IS task force with representatives from Security, Legal, Engineering, and the ISPO (P04, P23).

## Resulting Context

- This minimizes the risk of maintaining teams accidently receiving confidential data in shared repositories (P04).
- Developers become comfortable with creating InnerSource repositories which comply with security requirements (P08).
- This will reduce security risks as there is clarity around security policies and enable creation of secure repositories (P04, P08).

## Limitation/Blockers

- Development of a clear and consistent security policy needs communication with the security team and security experts with open-source experience (P08).

## Known Instances

- This pattern has been identified by 5 panelists (P04, P08, P11, P23, and P25) to have been implemented in their organizations.
