# GET /accounts/{account_id}/iam/user_groups

**Resource:** [Account User Groups](../resources/Account-User-Groups.md)
**List User Groups**
**Operation ID:** `account-user-group-list`

List all the user groups for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | iam_account_identifier | Yes |  |
| `id` | query | iam_user_group_identifier | No | ID of the user group to be fetched. |
| `name` | query | string | No |  |
| `fuzzyName` | query | string | No |  |
| `page` | query | number | No |  |
| `per_page` | query | number | No |  |
| `direction` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List User Group response |
| 4XX | List User Group response failure |

## Security

- **api_email**
- **api_key**
- **api_email**
- **api_key**
