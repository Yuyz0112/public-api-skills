# GET /accounts/{account_id}/iam/resource_groups/{resource_group_id}

**Resource:** [Account Resource Groups](../resources/Account-Resource-Groups.md)
**Resource Group Details**
**Operation ID:** `account-resource-group-details`

Get information about a specific resource group in an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | iam_account_identifier | Yes |  |
| `resource_group_id` | path | iam_resource_group_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Resource Group Details response |
| 4XX | Resource Group Details response failure |

## Security

- **api_token**
- **api_email**
- **api_key**
