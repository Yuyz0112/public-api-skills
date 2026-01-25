# GET /enterprises/{enterprise}/code-security/configurations

**Resource:** [code-security](../resources/code-security.md)
**Get code security configurations for an enterprise**
**Operation ID:** `code-security/get-configurations-for-enterprise`

Lists all code security configurations available in an enterprise.

The authenticated user must be an administrator of the enterprise in order to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `read:enterprise` scope to use this endpoint.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `per_page` | query | integer | No | The number of results per page (max 100). For more information, see "[Using pagination in the REST API](https://docs.github.com/rest/using-the-rest-api/using-pagination-in-the-rest-api)." |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

Array of [code-security-configuration](../schemas/code-security-configuration/code-security-configuration.md)

