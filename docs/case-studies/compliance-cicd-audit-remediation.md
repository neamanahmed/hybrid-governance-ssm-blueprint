# Case Study — Compliance Audit Remediation in CI/CD (Jenkins + AWS CodeDeploy)

## Context

In regulated enterprises, CI/CD automation must operate within strict governance boundaries.

Even technically correct pipelines can fail compliance if they violate:

- Data residency rules
- Source code handling policies
- Audit controls

This case study documents a real compliance-driven remediation of a CI/CD workflow using **Jenkins** and **AWS CodeDeploy**.

---

## Problem (Audit Finding)

An internal organizational audit identified a major compliance issue:

- Source code was being stored or processed in a cloud environment
- Corporate policy required source code to remain within the organization’s premises


This created immediate risk:

- Policy violation
- Audit exposure
- Need for architectural correction

---

## Constraints

Key constraints included:

- Source code must remain on-premises
- Deployment automation must continue
- Changes must satisfy audit and security teams
- Delivery must remain reliable and repeatable

---

## Architecture Decision

To comply with governance requirements, I redesigned the pipeline:

- Jenkins remained the controlled build system
- Deployment execution moved through AWS CodeDeploy
- Source artifacts were handled in a compliant manner
- Auditability and separation of duties were improved

---

## Solution Overview

The remediation approach included:

- Secure CI execution within policy boundaries
- Controlled deployment automation via CodeDeploy
- Alignment with enterprise governance rules

This ensured:

- Automation without compliance compromise
- Clear separation between build and deploy stages

---

## Security and Compliance Controls

Key controls enforced:

- No uncontrolled source persistence outside premises
- Deployment traceability through AWS deployment services
- Audit-aligned CI/CD workflow structure

---

## Outcome

This remediation delivered:

- Restored compliance with corporate source code policy
- Continued CI/CD automation with governance alignment
- Improved audit readiness and operational trust

---

## What This Demonstrates

This case study highlights capability in:

- DevSecOps under regulatory constraints
- Audit-driven engineering remediation
- Secure enterprise CI/CD architecture
- Banking-grade governance mindset

