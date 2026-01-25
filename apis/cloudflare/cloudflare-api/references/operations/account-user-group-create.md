# POST /accounts/{account_id}/iam/user_groups

**Resource:** [Account User Groups](../resources/Account-User-Groups.md)
**Create User Group**
**Operation ID:** `account-user-group-create`

Create a new user group under the specified account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | iam_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [iam_create_user_group_body](../schemas/iam/iam-create-user-group-body.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Add User Group response |
| 4XX | Add User Group response failure |

## Security

- **api_email**
- **api_key**
