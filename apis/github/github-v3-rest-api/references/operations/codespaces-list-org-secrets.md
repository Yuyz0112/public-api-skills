# GET /orgs/{org}/codespaces/secrets

**Resource:** [codespaces](../resources/codespaces.md)
**List organization secrets**
**Operation ID:** `codespaces/list-org-secrets`

Lists all Codespaces development environment secrets available at the organization-level without revealing their encrypted
values.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

