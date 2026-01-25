# POST /accounts/{account_id}/iam/user_groups/{user_group_id}/members

**Resource:** [Account User Groups](../resources/Account-User-Groups.md)
**Add User Group Members**
**Operation ID:** `account-user-group-member-create`

Add members to a User Group.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | iam_account_identifier | Yes |  |
| `user_group_id` | path | iam_user_group_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Add User Group Member response |
| 4XX | Add User Group Member response failure |

## Security

- **api_email**
- **api_key**
