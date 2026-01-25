# GET /accounts/{account_id}/iam/user_groups/{user_group_id}

**Resource:** [Account User Groups](../resources/Account-User-Groups.md)
**User Group Details**
**Operation ID:** `account-user-group-details`

Get information about a specific user group in an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | iam_account_identifier | Yes |  |
| `user_group_id` | path | iam_user_group_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | User Group Details response |
| 4XX | User Group Details response failure |

## Security

- **api_email**
- **api_key**
