# DELETE /accounts/{account_id}/iam/resource_groups/{resource_group_id}

**Resource:** [Account Resource Groups](../resources/Account-Resource-Groups.md)
**Remove Resource Group**
**Operation ID:** `account-resource-group-delete`

Remove a resource group from an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | iam_account_identifier | Yes |  |
| `resource_group_id` | path | iam_resource_group_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Remove Resource Group response |
| 4XX | Remove Member response failure |

**Success Response Schema:**

[iam_api-response-single-id](../schemas/iam/iam-api-response-single-id.md)

## Security

- **api_token**
- **api_email**
- **api_key**
