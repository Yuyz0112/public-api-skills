# GET /enterprises/{enterprise}/code-security/configurations/{configuration_id}/repositories

**Resource:** [code-security](../resources/code-security.md)
**Get repositories associated with an enterprise code security configuration**
**Operation ID:** `code-security/get-repositories-for-enterprise-configuration`

Lists the repositories associated with an enterprise code security configuration in an organization.

The authenticated user must be an administrator of the enterprise in order to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `read:enterprise` scope to use this endpoint.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `per_page` | query | integer | No | The number of results per page (max 100). For more information, see "[Using pagination in the REST API](https://docs.github.com/rest/using-the-rest-api/using-pagination-in-the-rest-api)." |
| `status` | query | string | No | A comma-separated list of statuses. If specified, only repositories with these attachment statuses will be returned.

Can be: `all`, `attached`, `attaching`, `removed`, `enforced`, `failed`, `updating`, `removed_by_enterprise` |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

Array of [code-security-configuration-repositories](../schemas/code-security-configuration-repositories/code-security-configuration-repositories.md)

