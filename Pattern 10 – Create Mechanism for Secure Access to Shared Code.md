# Pattern 10 – Create Mechanism for Secure Access to Shared Code

## Title

Create mechanism for secure access to shared code 

## Patlet

There is a conflict between security requirements of restricted access to code and InnerSource principles of open access. This conflict can be resolved by: a) Creation of a defined set of rules governing code confidentiality; b) Clear definitions of different sharing levels of repositories; and c) Use of automated tools to scan shared repositories for confidential information.

## Problem

InnerSource implementation needs free sharing of code for collaboration whereas security concerns and policies require restricted access to the code.

## Context

- The core benefit of InnerSource i.e., openness is lost if code is not readily accessible by developers (P07).

- Security policies must be considered to prevent leakage and unauthorised access to code (P08).
- In organizations where InnerSource is not the norm, contributions can be limited to projects which are perceived to be publicly accessible (P11).

## Forces

- Existing tooling and repositories can have security constraints which inhibit code openness (P07).
- Strong security concerns around leakage of customer data, injection of malicious code, and industrial sabotage can prevent open code.
- Concerns that open code will expose flaws in the security framework (P01).
- Project tools such as JIRA are closed by default (P10).

## Solutions

- Access can be secured by clearly defining the different sharing levels of repositories. Repositories can be classified as (P17, P23): a) Public - open source: accessible for all software developers in the world; b) Shared - inner source: accessible for all software developers in the organization; c) Internal – Accessible only to a legal entity within the organization such as a BU; and d) Closed – closed source: only accessible to named individuals in the organization.
- To prevent unauthorized access further measures can be taken such as: Single Sign-On (SSO), 2-Factor Authentication, and rotation of access tokens (P23). Sensitive repositories can be closed by default but with metadata available via an IS portal.
- Time limited read-only access can be granted to collaborators through an automated approval process (P04). This prevents the maintaining team from becoming bogged down in administration and simultaneously keeps the code secure.
- Delegation of access level decisions to projects (P17).
- A security agreement can be created governing shared repositories which prohibits storage of passwords, tokens, client data, usernames, business critical algorithms, and distribution of code from shared repositories (P23).
- Automated tools can be used to scan the repository for any stored confidential data (such as passwords, tokens etc), known vulnerabilities in dependencies and prevent commits with such data (P04, P17).

## Resulting Context

- This minimizes the risk of maintaining teams accidently receiving confidential data in shared repositories (P04).
- Security requirements are met without reverting to closed code and the access levels prevent unintentional modifications.

## Limitation/Blockers

- The restrictive security policies can be a symptom of deficiencies in the security framework in which scenario this solution will be inapplicable (P01).
- Restricting access to code is against InnerSource principles as all repositories should be open and it is better to build long term trust (P01, P25).
- It is difficult to scale the process of curating and classifying data based on security levels (P04).
- Access mechanism can lead to developer dissatisfaction and impact discoverability (P04).
- The development and maintenance of automated tools presents an additional overhead (P08).

## Known Instances

- This pattern has been identified by 6 panelists (P03, P04,P08, P11, P17, and P23) to have been implemented in their organizations.
