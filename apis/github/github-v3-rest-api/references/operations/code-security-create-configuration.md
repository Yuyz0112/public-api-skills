# POST /orgs/{org}/code-security/configurations

**Resource:** [code-security](../resources/code-security.md)
**Create a code security configuration**
**Operation ID:** `code-security/create-configuration`

Creates a code security configuration in an organization.

The authenticated user must be an administrator or security manager for the organization to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `write:org` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Successfully created code security configuration |

**Success Response Schema:**

[code-security-configuration](../schemas/code-security-configuration/code-security-configuration.md)

