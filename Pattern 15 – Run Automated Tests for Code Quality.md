# Pattern 15 – Run Automated Tests for Code Quality

## Title

Run automated tests for code quality 

## Patlet

Running automated tests prior to contributions review by maintaining team will reduce load on the maintaining team, enhance code quality, and give the contributor a clear understanding of quality requirements.

## Problem

The momentum of adding new features to code must be maintained to prevent code from going stale (i.e., going out of date). Additionally, developers assume that the code has value if it is being constantly updated, Otherwise, they risk losing interest in contributing.

## Context

- Most developers lack time to contribute on a regular basis to keep code fresh(P09).
- Existence of a multitude of innovative projects driven by few committed people makes it difficult for contributors to prioritize with their limited time.
- Code is not updated due to lack of feature requests from product manager and no technical requirement from the developer team (P08).

## Forces

- IS projects which are high use but low maintenance risk not being updated when changes are needed (P20).

## Solutions

- Implementation of multiple code scanning processes (such as pre-commit hooks, unit tests etc) in the development pipeline irrespective of whether code contributor is from within the team or external (P01, P09).
- Integration of automated tools such as SonarQube, Jenkins, and Action Runners from GitHub into the platform (P09).

## Resulting Context

- Results in a fast feedback loop, detection of security vulnerabilities, confidence in the stability and quality of code (P03, P08 P09, P17, and P20).

## Limitation/Blockers

- A balance must be struck between adding new features and managing changes to the product. Constant addition of features can be viewed as more work by the client (P04).
- Project team needs to develop the automated testcase (P08).

## Known Instances

- This pattern has been identified by 5 panelists (P03, P04, P08, P09, and P20) to have been implemented in their organizations.
