# DELETE /accounts/{account_id}/iam/user_groups/{user_group_id}/members/{member_id}

**Resource:** [Account User Groups](../resources/Account-User-Groups.md)
**Remove User Group Member**
**Operation ID:** `account-user-group-member-delete`

Remove a member from User Group

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | iam_account_identifier | Yes |  |
| `user_group_id` | path | iam_user_group_identifier | Yes |  |
| `member_id` | path | iam_user_group_member_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete User Group Member response |
| 4XX | Delete User Group response failure |

## Security

- **api_email**
- **api_key**
