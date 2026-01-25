# GET /orgs/{org}/code-security/configurations

**Resource:** [code-security](../resources/code-security.md)
**Get code security configurations for an organization**
**Operation ID:** `code-security/get-configurations-for-org`

Lists all code security configurations available in an organization.

The authenticated user must be an administrator or security manager for the organization to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `read:org` scope to use this endpoint.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `target_type` | query | enum: global, all | No | The target type of the code security configuration |
| `per_page` | query | integer | No | The number of results per page (max 100). For more information, see "[Using pagination in the REST API](https://docs.github.com/rest/using-the-rest-api/using-pagination-in-the-rest-api)." |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

Array of [code-security-configuration](../schemas/code-security-configuration/code-security-configuration.md)

