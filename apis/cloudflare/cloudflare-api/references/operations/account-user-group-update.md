# PUT /accounts/{account_id}/iam/user_groups/{user_group_id}

**Resource:** [Account User Groups](../resources/Account-User-Groups.md)
**Update User Group**
**Operation ID:** `account-user-group-update`

Modify an existing user group.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | iam_account_identifier | Yes |  |
| `user_group_id` | path | iam_user_group_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [iam_update_user_group_body](../schemas/iam/iam-update-user-group-body.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update User Group response |
| 4XX | Update User Group response failure |

## Security

- **api_email**
- **api_key**
