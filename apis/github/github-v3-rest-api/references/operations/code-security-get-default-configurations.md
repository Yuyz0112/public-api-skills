# GET /orgs/{org}/code-security/configurations/defaults

**Resource:** [code-security](../resources/code-security.md)
**Get default code security configurations**
**Operation ID:** `code-security/get-default-configurations`

Lists the default code security configurations for an organization.

The authenticated user must be an administrator or security manager for the organization to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `read:org` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[code-security-default-configurations](../schemas/code-security-default-configurations/code-security-default-configurations.md)

