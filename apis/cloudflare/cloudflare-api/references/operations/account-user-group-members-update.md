# PUT /accounts/{account_id}/iam/user_groups/{user_group_id}/members

**Resource:** [Account User Groups](../resources/Account-User-Groups.md)
**Update User Group Members**
**Operation ID:** `account-user-group-members-update`

Replace the set of members attached to a User Group.

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
| 200 | Update User Group Members response |
| 4XX | Update User Group response failure |

## Security

- **api_email**
- **api_key**
