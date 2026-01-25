# GET /accounts/{account_id}/iam/permission_groups/{permission_group_id}

**Resource:** [Account Permission Groups](../resources/Account-Permission-Groups.md)
**Permission Group Details**
**Operation ID:** `account-permission-group-details`

Get information about a specific permission group in an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | iam_account_identifier | Yes |  |
| `permission_group_id` | path | iam_permission_group_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Permission Group Details response |
| 4XX | Permission Group Details response failure |

**Success Response Schema:**

[iam_single_permission_groups_response](../schemas/iam/iam-single-permission-groups-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
