# GET /enterprises/{enterprise}/code-security/configurations/defaults

**Resource:** [code-security](../resources/code-security.md)
**Get default code security configurations for an enterprise**
**Operation ID:** `code-security/get-default-configurations-for-enterprise`

Lists the default code security configurations for an enterprise.

The authenticated user must be an administrator of the enterprise in order to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `read:enterprise` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[code-security-default-configurations](../schemas/code-security-default-configurations/code-security-default-configurations.md)

