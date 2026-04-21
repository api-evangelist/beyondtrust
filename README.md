# BeyondTrust (beyondtrust)
BeyondTrust is a cybersecurity company specializing in privileged access management (PAM) and vulnerability management solutions. Their products help organizations prevent data breaches, malware attacks, and insider threats by identifying and controlling the access of privileged users, accounts, and credentials across the enterprise.

**URL:** [https://docs.beyondtrust.com/](https://docs.beyondtrust.com/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Access, Access Management, Compliance, Credentials, Privileged Access, Security, Secrets, Zero Trust

## Timestamps

- **Created:** 2025-02-17
- **Modified:** 2026-04-19

## APIs

### BeyondTrust Password Safe API
The BeyondTrust Password Safe API provides programmatic access to privileged credential management, secrets management, and access request workflows. It enables organizations to implement just-in-time privileged access and integrate credential retrieval into automation pipelines.

**Human URL:** [https://docs.beyondtrust.com/](https://docs.beyondtrust.com/)

#### Tags:

 - Privileged Access Management, Secrets Management, Security, Zero Trust, Credentials

#### Properties

- [Documentation](https://docs.beyondtrust.com/)
- [OpenAPI](openapi/beyondtrust-password-safe-api.yaml)

## Common Properties

- [Portal](https://docs.beyondtrust.com/)
- [GettingStarted](https://docs.beyondtrust.com/)
- [GitHubOrganization](https://github.com/BeyondTrust)

## Features

| Name | Description |
|------|-------------|
| Privileged Password Management | Automatically discover, manage, and rotate passwords for privileged accounts across systems. |
| Just-In-Time Privileged Access | Grant time-limited, approval-based access to privileged accounts minimizing standing privileges. |
| Secrets Safe | Store, manage, and retrieve application secrets, API keys, and credentials securely. |
| Session Management | Record, monitor, and control privileged remote sessions for audit and compliance. |
| Endpoint Privilege Management | Remove admin rights from endpoints while allowing approved applications to run. |
| Privileged Remote Access | Provide secure remote access to privileged systems without VPN or exposed credentials. |
| Vulnerability Management | Identify and prioritize vulnerabilities across the attack surface. |
| AD Bridge | Extend Active Directory authentication and group policies to Unix and Linux systems. |

## Use Cases

| Name | Description |
|------|-------------|
| Zero Standing Privileges | Eliminate persistent privileged access by granting just-in-time credentials on demand. |
| DevOps Secrets Management | Retrieve credentials and secrets programmatically in CI/CD pipelines without hardcoded credentials. |
| Privileged Account Discovery | Automatically discover and on-board all privileged accounts across hybrid environments. |
| Compliance Reporting | Generate audit trails for all privileged access to meet SOX, PCI-DSS, and HIPAA requirements. |
| Ransomware Prevention | Prevent lateral movement by removing local admin rights and controlling privileged access. |
| Third-Party Vendor Access | Grant temporary, monitored access to vendors and contractors without sharing credentials. |

## Integrations

| Name | Description |
|------|-------------|
| ServiceNow | Integrate access requests with ServiceNow ITSM workflows for approval management. |
| Active Directory | Sync users, groups, and managed accounts from Active Directory. |
| AWS | Manage privileged access to AWS IAM roles and EC2 instances. |
| Azure | Integrate with Azure Active Directory and manage Azure privileged identities. |
| HashiCorp Vault | Bridge BeyondTrust and HashiCorp Vault for secrets management. |
| Splunk | Forward audit logs and session recordings to Splunk for SIEM analysis. |
| Terraform | Manage BeyondTrust Password Safe resources as infrastructure as code. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [BeyondTrust Password Safe API](openapi/beyondtrust-password-safe-api.yaml)

### JSON Schema

- [beyondtrust-create-request-body-schema.json](json-schema/beyondtrust-create-request-body-schema.json)
- [beyondtrust-create-secret-request-schema.json](json-schema/beyondtrust-create-secret-request-schema.json)
- [beyondtrust-credential-response-schema.json](json-schema/beyondtrust-credential-response-schema.json)
- [beyondtrust-managed-account-schema.json](json-schema/beyondtrust-managed-account-schema.json)
- [beyondtrust-managed-system-schema.json](json-schema/beyondtrust-managed-system-schema.json)
- [beyondtrust-request-schema.json](json-schema/beyondtrust-request-schema.json)
- [beyondtrust-secret-schema.json](json-schema/beyondtrust-secret-schema.json)
- [beyondtrust-secret-with-value-schema.json](json-schema/beyondtrust-secret-with-value-schema.json)
- [beyondtrust-session-response-schema.json](json-schema/beyondtrust-session-response-schema.json)
- [beyondtrust-sign-app-in-request-schema.json](json-schema/beyondtrust-sign-app-in-request-schema.json)
- [beyondtrust-update-request-body-schema.json](json-schema/beyondtrust-update-request-body-schema.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [BeyondTrust Password Safe API](capabilities/shared/beyondtrust.yaml) — 14 operations for access requests, credential retrieval, managed accounts, managed systems, and secrets management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Privileged Access Management](capabilities/privileged-access-management.yaml) | BeyondTrust | 9 | Security Engineer, DevOps Engineer |

## Vocabulary

- [BeyondTrust Vocabulary](vocabulary/beyondtrust-vocabulary.yaml) — Unified taxonomy mapping 4 resources, 6 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [BeyondTrust Spectral Rules](rules/beyondtrust-spectral-rules.yml) — 24 rules across 9 categories enforcing BeyondTrust API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
