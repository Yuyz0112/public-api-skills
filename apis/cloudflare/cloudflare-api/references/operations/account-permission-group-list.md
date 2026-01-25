# GET /accounts/{account_id}/iam/permission_groups

**Resource:** [Account Permission Groups](../resources/Account-Permission-Groups.md)
**List Account Permission Groups**
**Operation ID:** `account-permission-group-list`

List all the permissions groups for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | iam_account_identifier | Yes |  |
| `id` | query | string | No |  |
| `name` | query | string | No |  |
| `label` | query | string | No |  |
| `page` | query | number | No |  |
| `per_page` | query | number | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Permission Groups response |
| 4XX | List Permission Groups response failure |

**Success Response Schema:**

[iam_collection_permission_groups_response](../schemas/iam/iam-collection-permission-groups-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
