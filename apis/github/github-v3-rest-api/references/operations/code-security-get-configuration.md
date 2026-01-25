# GET /orgs/{org}/code-security/configurations/{configuration_id}

**Resource:** [code-security](../resources/code-security.md)
**Get a code security configuration**
**Operation ID:** `code-security/get-configuration`

Gets a code security configuration available in an organization.

The authenticated user must be an administrator or security manager for the organization to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `write:org` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[code-security-configuration](../schemas/code-security-configuration/code-security-configuration.md)

