# GET /accounts/{account_id}/iam/user_groups/{user_group_id}/members

**Resource:** [Account User Groups](../resources/Account-User-Groups.md)
**List User Group Members**
**Operation ID:** `account-user-group-member-list`

List all the members attached to a user group.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | iam_account_identifier | Yes |  |
| `user_group_id` | path | iam_user_group_identifier | Yes |  |
| `page` | query | number | No |  |
| `per_page` | query | number | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List User Group Members |
| 4XX | User Group Details response failure |

## Security

- **api_email**
- **api_key**
