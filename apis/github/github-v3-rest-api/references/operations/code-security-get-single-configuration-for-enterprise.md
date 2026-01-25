# GET /enterprises/{enterprise}/code-security/configurations/{configuration_id}

**Resource:** [code-security](../resources/code-security.md)
**Retrieve a code security configuration of an enterprise**
**Operation ID:** `code-security/get-single-configuration-for-enterprise`

Gets a code security configuration available in an enterprise.

The authenticated user must be an administrator of the enterprise in order to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `read:enterprise` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[code-security-configuration](../schemas/code-security-configuration/code-security-configuration.md)

