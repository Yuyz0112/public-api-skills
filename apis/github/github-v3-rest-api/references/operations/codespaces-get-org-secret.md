# GET /orgs/{org}/codespaces/secrets/{secret_name}

**Resource:** [codespaces](../resources/codespaces.md)
**Get an organization secret**
**Operation ID:** `codespaces/get-org-secret`

Gets an organization development environment secret without revealing its encrypted value.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[codespaces-org-secret](../schemas/codespaces-org-secret/codespaces-org-secret.md)

