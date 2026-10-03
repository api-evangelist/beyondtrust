---
name: beyondtrust-authentication-sign-in-out
description: Sign a user into BeyondTrust and then sign them out.
api: openapi/beyondtrust-authentication-api-openapi.yml
operations:
- signAppIn
- signAppOut
generated: '2026-10-03'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/beyondtrust-authentication-api-openapi.yml ; every operationId checked against the contract
---

# beyondtrust-authentication-sign-in-out

Sign a user into BeyondTrust and then sign them out.

## Steps

1. 1. Call `signAppIn` with the required request body fields as defined in the contract.
2. 2. Call `signAppOut` with the required request body fields as defined in the contract.

## Rules

- Auth: Include the API key in the `Authorization` header (apiKeyAuth).
