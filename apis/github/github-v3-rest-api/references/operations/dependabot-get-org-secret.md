# GET /orgs/{org}/dependabot/secrets/{secret_name}

**Resource:** [dependabot](../resources/dependabot.md)
**Get an organization secret**
**Operation ID:** `dependabot/get-org-secret`

Gets a single organization secret without revealing its encrypted value.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[organization-dependabot-secret](../schemas/organization-dependabot-secret/organization-dependabot-secret.md)

