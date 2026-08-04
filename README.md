# BeyondTrust (beyondtrust)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
