# DELETE /accounts/{account_id}/iam/user_groups/{user_group_id}

**Resource:** [Account User Groups](../resources/Account-User-Groups.md)
**Remove User Group**
**Operation ID:** `account-user-group-delete`

Remove a user group from an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | iam_account_identifier | Yes |  |
| `user_group_id` | path | iam_user_group_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Remove User Group response |
| 4XX | Remove User Group response failure |

**Success Response Schema:**

[iam_api-response-single-id](../schemas/iam/iam-api-response-single-id.md)

## Security

- **api_email**
- **api_key**
