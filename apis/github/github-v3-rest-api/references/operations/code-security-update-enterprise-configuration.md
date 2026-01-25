# PATCH /enterprises/{enterprise}/code-security/configurations/{configuration_id}

**Resource:** [code-security](../resources/code-security.md)
**Update a custom code security configuration for an enterprise**
**Operation ID:** `code-security/update-enterprise-configuration`

Updates a code security configuration in an enterprise.

The authenticated user must be an administrator of the enterprise in order to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `admin:enterprise` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |

**Success Response Schema:**

[code-security-configuration](../schemas/code-security-configuration/code-security-configuration.md)

