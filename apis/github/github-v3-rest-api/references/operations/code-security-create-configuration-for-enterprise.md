# POST /enterprises/{enterprise}/code-security/configurations

**Resource:** [code-security](../resources/code-security.md)
**Create a code security configuration for an enterprise**
**Operation ID:** `code-security/create-configuration-for-enterprise`

Creates a code security configuration in an enterprise.

The authenticated user must be an administrator of the enterprise in order to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `admin:enterprise` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Successfully created code security configuration |
| 400 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[code-security-configuration](../schemas/code-security-configuration/code-security-configuration.md)

