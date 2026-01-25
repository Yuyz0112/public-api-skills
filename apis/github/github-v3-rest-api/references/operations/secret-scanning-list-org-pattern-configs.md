# GET /orgs/{org}/secret-scanning/pattern-configurations

**Resource:** [secret-scanning](../resources/secret-scanning.md)
**List organization pattern configurations**
**Operation ID:** `secret-scanning/list-org-pattern-configs`

Lists the secret scanning pattern configurations for an organization.

Personal access tokens (classic) need the `read:org` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[secret-scanning-pattern-configuration](../schemas/secret-scanning-pattern-configuration/secret-scanning-pattern-configuration.md)

