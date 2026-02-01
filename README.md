# Hybrid Governance SSM Blueprint

This repository demonstrates AWS Systems Manager as a centralized governance control plane
for regulated hybrid environments.

## Hybrid Governance Architecture

![Hybrid SSM Control Plane](./diagrams/hybrid-ssm-control-plane.png)

## Key Capabilities
- Session Manager (No SSH)
- Patch Compliance Enforcement
- Centralized Audit Logging (CloudTrail)
- Hybrid Fleet Management (On-Prem + Cloud)

This repository includes real-world enterprise case studies demonstrating governance-first cloud operations:

- **Hybrid Governance with AWS Systems Manager (On-Prem + AWS)**
  Securely managing on-prem infrastructure using AWS SSM with centralized audit logging.
  → `docs/case-studies/hybrid-ssm-onprem.md`

- **Cross-Cloud Operations: OCI Compute Managed via AWS SSM**
  Extending AWS SSM as a unified control plane to manage OCI workloads and deploy applications securely.
  → `docs/case-studies/aws-ssm-oci-control-plane.md`
