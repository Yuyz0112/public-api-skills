# PATCH /orgs/{org}/code-security/configurations/{configuration_id}

**Resource:** [code-security](../resources/code-security.md)
**Update a code security configuration**
**Operation ID:** `code-security/update-configuration`

Updates a code security configuration in an organization.

The authenticated user must be an administrator or security manager for the organization to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `write:org` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response when a configuration is updated |
| 204 | Response when no new updates are made |

**Success Response Schema:**

[code-security-configuration](../schemas/code-security-configuration/code-security-configuration.md)

