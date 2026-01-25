# GET /accounts/{account_id}/iam/resource_groups

**Resource:** [Account Resource Groups](../resources/Account-Resource-Groups.md)
**List Resource Groups**
**Operation ID:** `account-resource-group-list`

List all the resource groups for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | iam_account_identifier | Yes |  |
| `id` | query | any | No |  |
| `name` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Resource Groups response |
| 4XX | List Resource Groups response failure |

## Security

- **api_token**
- **api_email**
- **api_key**
